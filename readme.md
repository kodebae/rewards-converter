# :airplane: Credit Rewards Converter :airplane:
This is the project repo for the JPMC Software Engineering Lite Program, consult the program instructions for more information.

## Project Setup and Development Process:

### JVM Selection: 
* * Project setup, selected an appropriate Java Virtual Machine (JVM) version to ensure compatibility with project requirements.
### Build System Configuration: 
* * Post-JVM selection, reconfigured and reloaded Maven to synchronize project dependencies and build configurations. This step was to ensure the project's build environment was correctly aligned with the chosen JVM. Wasn't sure about this, so it was precautionary.
### Converter Logic Implementation:
*  * Research: Conducted a bit of research on the mechanics of a credit card reward conversion system, focusing on the conversion rate from cash to airline miles.
* * Maths: Implemented the conversion logic using the rate of 0.0035 dollars per mile. This involved:
* * * Dividing cash values by the conversion rate to calculate equivalent miles.
* * Addressing precision issues in floating-point arithmetic to ensure accurate results.
### Validation and Testing:
* * Verified the conversion calculations by running tests, the system accurately converts between cash and miles based on the specified rate.
### Outcome: 
* * Successfully set up the development environment, integrated the build system, and implemented a functional reward converter with accurate mathematical operations.