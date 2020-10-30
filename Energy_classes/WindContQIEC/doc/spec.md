# WindContQIEC


## Description
Q control model.  Reference: IEC Standard 61400-27-1 Section 6.6.5.6.

## Data Model
  - properties:
    - iqh1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Maximum reactive current injection during dip (i). It is type dependent parameter. Default: 0.0
    - iqmax:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Maximum reactive current injection (i). It is type dependent parameter. Default: 0.0
    - iqmin:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Minimum reactive current injection (i). It is type dependent parameter. Default: 0.0
    - iqpost:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Post fault reactive current injection (). It is project dependent parameter. Default: 0.0
    - kiq:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Reactive power PI controller integration gain (). It is type dependent parameter. Default: 0.0
    - kiu:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage PI controller integration gain (). It is type dependent parameter. Default: 0.0
    - kpq:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Reactive power PI controller proportional gain (). It is type dependent parameter. Default: 0.0
    - kpu:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage PI controller proportional gain (). It is type dependent parameter. Default: 0.0
    - kqv:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage scaling factor for LVRT current (). It is project dependent parameter. Default: 0.0
    - qmax:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Maximum reactive power (q). It is type dependent parameter. Default: 0.0
    - qmin:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Minimum reactive power (q). It is type dependent parameter. Default: 0.0
    - rdroop:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Resistive component of voltage drop impedance (). It is project dependent parameter. Default: 0.0
    - tiq:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Time constant in reactive current lag (T). It is type dependent parameter. Default: 0
    - tpfilt:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Power measurement filter time constant (). It is type dependent parameter. Default: 0
    - tpost:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Length of time period where post fault reactive power is injected (). It is project dependent parameter. Default: 0
    - tqord:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Time constant in reactive power order lag (). It is type dependent parameter. Default: 0
    - tufilt:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage measurement filter time constant (). It is type dependent parameter. Default: 0
    - udb1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage dead band lower limit (). It is type dependent parameter. Default: 0.0
    - udb2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage dead band upper limit (). It is type dependent parameter. Default: 0.0
    - umax:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Maximum voltage in voltage PI controller integral term (u). It is type dependent parameter. Default: 0.0
    - umin:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Minimum voltage in voltage PI controller integral term (u). It is type dependent parameter. Default: 0.0
    - uqdip:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage threshold for LVRT detection in q control (). It is type dependent parameter. Default: 0.0
    - uref0:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : User defined bias in voltage reference (), used when  =. It is case dependent parameter. Default: 0.0
    - windLVRTQcontrolModesType:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Types of LVRT Q control modes (). It is project dependent parameter. Default: None
    - windQcontrolModesType:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Types of general wind turbine Q control modes ().  It is project dependent parameter. Default: None
    - xdroop:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Inductive component of voltage drop impedance (). It is project dependent parameter. Default: 0.0
    - WindTurbineType3or4IEC:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Wind turbine type 3 or 4 model with which this reactive control mode is associated. Default: None