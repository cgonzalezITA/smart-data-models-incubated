# EquivalentInjection


## Description
This class represents equivalent injections (generation or load).  Voltage regulation is allowed only at the point of connection.

## Data Model
  - properties:
    - ReactiveCapabilityCurve:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : The equivalent injection using this reactive capability curve. Default: None
    - maxP:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Maximum active power of the injection. Default: 0.0
    - maxQ:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Used for modeling of infeed for load flow exchange. Not used for short circuit modeling.  If maxQ and minQ are not used ReactiveCapabilityCurve can be used. Default: 0.0
    - minP:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Minimum active power of the injection. Default: 0.0
    - minQ:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Used for modeling of infeed for load flow exchange. Not used for short circuit modeling.  If maxQ and minQ are not used ReactiveCapabilityCurve can be used. Default: 0.0
    - regulationCapability:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Specifies whether or not the EquivalentInjection has the capability to regulate the local voltage. Default: False
    - r:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Positive sequence resistance. Used to represent Extended-Ward (IEC 60909). Usage : Extended-Ward is a result of network reduction prior to the data exchange. Default: 0.0
    - r0:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Zero sequence resistance. Used to represent Extended-Ward (IEC 60909). Usage : Extended-Ward is a result of network reduction prior to the data exchange. Default: 0.0
    - r2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Negative sequence resistance. Used to represent Extended-Ward (IEC 60909). Usage : Extended-Ward is a result of network reduction prior to the data exchange. Default: 0.0
    - x:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Positive sequence reactance. Used to represent Extended-Ward (IEC 60909). Usage : Extended-Ward is a result of network reduction prior to the data exchange. Default: 0.0
    - x0:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Zero sequence reactance. Used to represent Extended-Ward (IEC 60909). Usage : Extended-Ward is a result of network reduction prior to the data exchange. Default: 0.0
    - x2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Negative sequence reactance. Used to represent Extended-Ward (IEC 60909). Usage : Extended-Ward is a result of network reduction prior to the data exchange. Default: 0.0
    - regulationStatus:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Specifies the default regulation status of the EquivalentInjection.  True is regulating.  False is not regulating. Default: False
    - regulationTarget:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : The target voltage for voltage regulation. Default: 0.0
    - p:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Equivalent active power injection. Load sign convention is used, i.e. positive sign means flow out from a node. Starting value for steady state solutions. Default: 0.0
    - q:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Equivalent reactive power injection. Load sign convention is used, i.e. positive sign means flow out from a node. Starting value for steady state solutions. Default: 0.0