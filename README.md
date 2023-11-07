# ttt

graph TD
A[Java Code] -->|Compiled| B(Bytecode)
B --> C{Run}
C -->|bytecode| D[Windows JVM] 
D --> K[Windows Instructions]
C -->|bytecode| E[Unix  JVM]
E --> L[Unix Instructions]
C -->|bytecode| F[Linux  JVM]
F --> M[Linux Instructions]
C -->|bytecode| G[Any other platform  JVM]
G --> N[Linux Instructions]
