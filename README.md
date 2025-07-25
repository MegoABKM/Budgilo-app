graph TD
    A[UI Layer - Flutter] --> B[State Management];
    A --> C[Navigation];
    A --> D[Local Database];

    subgraph B [State Management]
        B1[Riverpod]
        B2[StateNotifierProvider]
    end

    subgraph C [Navigation & Services]
        C1[GetX]
    end

    subgraph D [Local Database]
        D1[Hive]
        D2[Type Adapters]
    end

    E[App Features] --> F[UI Components];
    F --> F1[Lottie Animations];
    F --> F2[FL Chart];
    F --> F3[Responsive UI];

    E --> G[Core Logic];
    G --> G1[Multi-Language Support];
    G --> G2[Custom Themes];
    G --> G3[Data Reports];
