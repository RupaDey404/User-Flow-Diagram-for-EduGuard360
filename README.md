#diagram of attendance

```mermaid
    flowchart TD
    A[Login] --> B{Role}
    B -->|Admin| C[Setup Attendance]
    B -->|Teacher| D[Mark Attendance]
    B -->|Student| E[View Attendance]

```