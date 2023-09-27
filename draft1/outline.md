# Draft 1 Outline

- Introduction
    - Background
        - FL
        - Smartphone good for FL
        - What we need for FL on smartphone
    - Related work in mobile FL lack stuff
        - (Checklist table)
        - Cross-platform training support
        - Customizing FL in production
    - Brief introduction to FedKit
        - FedKit features
        <!-- TODO: - Our research app in production (Key contributions) -->
- System Description
    - Architecture Overview
        - Client-server relationship
        - 2 innovations: the following
    - Cross-Platform FL Model Pipeline (detailed)
        - Description: cross-platform FL on smartphones
        - Three steps
            - (Figure)
            - Model conversion to native format (TFLite & Core ML)
            - Unified on-device training APIs using native ML frameworks
            - Cross-platform parameter aggregation
    - Flexible In-Production FL Customization
        - Motivation
            - FL frameworks assume models bundled with app
            - Researchers would want to update the model after the app is deployed
        - How it is done: FL workflow with a preparation stage
            - (Figure of structure with workflow, numbered)
            - Continuous Model Deployment
                - Model request
            - Parallel FL Session Support
                - FL Server setup
            - Flexible FL Training
                - Model checkpointing & resumption
                - Training Telemetry
- Use Case: FedCampus
    - Describe the app
    - How the app is deployed
        - (Figure of the setup)

## Not Mentioned

- Cross platform communication support with Flutter
- Model checkpointing
- Telemetry collection

Implementation details

- FedMCRNN model
- Client cache model in file system
- Android trainer takes generic input & output

## Removed

- Background training scheduling
- Simple HealthKit model
- Benchmark app
- Conclusion and Future Work
