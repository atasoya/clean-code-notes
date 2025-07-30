Clean system design avoids getting mixed with frameworks and infrastructure.

### Seperation of Concerns
We should seperate infrastructure concers like databases or external APIs from the bussiness rules so our code becomes more testable and adaptable.

### Use Layers
Layers like UI layer, business logic layer & data access layer. Using layers enables us to use interfaces to swap databaes or change UI frameworks without massive rewrites.

### Plugins Architecture
We should make the application logic core and all other external parts are plugged in. Main entry point should act like plugin assembler.
