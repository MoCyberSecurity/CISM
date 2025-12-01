flowchart TB
    %% Program Lifecycle
    A[Program Charter] --> B[Define Scope]
    B --> C[Develop Policies & Standards]
    C --> D[Implement Controls & Processes]
    D --> E[Operational Activities & Monitoring]
    E --> F[Security Metrics & Reporting]
    F --> G[Continuous Improvement]
    G --> B

    %% Core Components
    subgraph Components
        P1[Processes: Risk, Compliance, Ops]
        P2[Technologies: Firewalls, IDS/IPS, DLP, GRC]
        P3[Assets: Hardware, Software, Data, Personnel]
    end

    D --> P1
    D --> P2
    D --> P3

    %% Roles
    subgraph Roles
        R1[Executive Leadership: Approve Charter & Funding]
        R2[Security Program Manager: Implement & Monitor]
        R3[Department Owners: Operational Support]
    end

    A --> R1
    D --> R2
    B --> R3

    %% Data Governance
    subgraph Data_Governance
        DG1[Backup & Recovery]
        DG2[Data Classification Policies]
        DG3[DLP & DRM]
    end

    D --> DG1
    D --> DG2
    D --> DG3

    %% Metrics
    subgraph Metrics
        M1[KRIs]
        M2[KGIs]
        M3[KPIs]
    end

    F --> M1
    F --> M2
    F --> M3

    click A "https://github.com/MoCyberSecurity/CISM/blob/main/Domain3_Program_Development/Domain3_Program_Development.md" "View Domain 3 details on GitHub"
