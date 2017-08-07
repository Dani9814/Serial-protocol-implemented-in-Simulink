# Serial-protocol-implemented-in-Simulink

This is a report that shows how to implement custom serial arduino protocol in Simulink.

This is protocol structure:

|Header |Type|Linear Velocity|Angular velocity|Checksum| 
|-------|----|---------------|----------------|--------|
|       |    |   Int 16      |     Int 16     |        |
|       |    | Two bytes     |  Two bytes     |  LSB   |
|   200 | 1  | LSB-> 3  MSB->0| LSB->4  MSB-> 0   |   7    |         


