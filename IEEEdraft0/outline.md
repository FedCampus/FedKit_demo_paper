# IEEE INFOCOM Draft 0 Outline

- Motivation and Analysis
    - Background
        - FL
        - Lack of real-world mobile FL experiments
        - Problem and goal: mobile FL platform for continuous real-world experiments
    - Analysis and why existing solutions don't work
        - (Checklist table)
        - What we need for FL on smartphone
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
    - Flexible MLOps in Production
        - Motivation
            - FL frameworks assume models bundled with app
            - Researchers would want to update the model after the app is deployed
        - How it is done: FL workflow with a preparation stage
            - (Figure of structure with workflow, numbered)
            - Continuous Cross-Platform Model Delivery
                - Model request
                - Decouple clients and models
                - Cross-platform model conversion
            - Customizable Continuous FL Training
                - Parallel FL Session Support
                - FL Server setup
                - Customization by Flower
- Demonstration
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
