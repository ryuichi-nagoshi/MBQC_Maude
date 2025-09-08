## Dependencies
Maude is a language and system for specification and programming based on equational logic and rewriting logic. To get started, download Maude from [this page](https://maude.cs.illinois.edu/w/index.php/The_Maude_System) and follow the installation steps.

## How to install
- Clone the source code to your computer and move into the project root (`MBQC_Maude`).
- Move (or copy) all `.maude` files from the `test` directory into the project root (`MBQC_Maude`).
- Launch Maude and load the `.maude` file that specifies the pattern you want to verify.

Example: to verify the quantum teleportation pattern, run in the Maude CLI:
```
in Teleport.maude
```

## Case Studies
We have successfully verified several patterns using this tool.

- Hadamard gate
- Quantum Teleportation
- X-rotation
- Z-rotation
- CNOT gate
- General rotation
- GHZ
