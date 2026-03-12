# CAMS+GenAI DSL Metamodel

The CAMS+GenAI DSL defines the structural elements used to model adaptive context-aware mobile systems. The metamodel supports prompt-driven model synthesis and automated code generation.

## Core Elements

### Context
Represents the contextual environment in which the application operates.

Attributes:
- name
- description

### Sensor
Represents a data source providing contextual information.

Attributes:
- name
- type
- frequency
- source

### Rule
Defines adaptation logic triggered by contextual conditions.

Attributes:
- name
- condition
- action
- priority

### Policy
Represents system-level governance constraints influencing adaptation behavior.

Attributes:
- name
- objective
- constraint

### PromptTemplate
Defines reusable prompt structures used for generative model synthesis.

Attributes:
- name
- contextBlock
- constraintBlock
- objectiveBlock

### ConstraintSet
Defines syntactic and semantic constraints that generated DSL models must satisfy.

Attributes:
- syntaxRules
- semanticRules
- platformConstraints

### InferencePolicy
Defines reasoning strategies used to trigger adaptation decisions.

Attributes:
- reasoningType
- triggerCondition
