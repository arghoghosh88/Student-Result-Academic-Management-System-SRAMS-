flowchart TD
    A[Start] --> B[Login Menu]
    B --> |Admin Login| C{Admin Credentials Valid?}
    C --> |Yes| D[Admin Menu]
    C --> |No| B
    B --> |Faculty Login| E{Faculty Credentials Valid?}
    E --> |Yes| F[Faculty Menu]
    E --> |No| B
    B --> |Student Login| G{Student Found in File?}
    G --> |Yes| H[Student Menu]
    G --> |No| B
    D --> D1[Add Faculty Info]
    D --> D2[Add Student Info]
    D --> D3[Calculate Total Marks]
    D --> D4[Calculate CGPA]
    D --> D5[Fix Student Names]
    D --> D6[Copy File]
    D --> D7[Student Panel]
    D --> D8[Faculty Panel]
    F --> F1[Set Password]
    F --> F2[Enter Marks]
    H --> H1[View Details]
    H --> H2[Edit Info]
    H --> H3[View Routine]
    H --> H4[View Result / CGPA]
    D1 --> D
    D2 --> D
    D3 --> D
    D4 --> D
    D5 --> D
    D6 --> D
    D7 --> H
    D8 --> F
    F1 --> F
    F2 --> F
    H1 --> H
    H2 --> H
    H3 --> H
    H4 --> H
    H --> B
