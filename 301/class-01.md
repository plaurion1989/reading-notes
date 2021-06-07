# Component-based Architecture
Component based architecture divides the problem into sub-problems associated with component partitions.
components are reusable and self-deployable binary units.
## What is a Component?
A component is a software object  that interacts with other components that has specific functionality or sets of functionality.
### Views of a Component
- **Object-oriented view**; a set of one or more cooperating classes.
- **Conventional view**; module of a program that integrates the processing logic.
- **Process-related view**; Components that are selected from a library and used to populate the architecture.
### Characteristics of Components
1. Reusability
1. Replaceable
1. Not context specific
1. Extensible
1. Encapsulated
1. Independent
## Component-Level Desigh Guidelines
>  Attains architectural component names from the problem domain and ensures that they have meaning to all stakeholders who view the architectural model.
>  Extracts the business process entities that can exist independently without any associated dependency on other entities.
>  Recognizes and discover these independent entities as new components.
>  Uses infrastructure component names that reflect their implementation-specific meaning.
>  Models any dependencies from left to right and inheritance from top to bottom.
>  Model any component dependencies as interfaces rather than representing them as a direct component-to-component dependency.
## Advantages
- Ease of Deployment
- Reduced Cost
- Ease of Development
- Reusable
- Modification of technical complexity
- Reliablity
- System maintenance and evolution
- Independent
