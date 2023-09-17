# Draft 1 Outline

- Introduction
    - What is mobile FL & why it is important
    - Related work in mobile FL
    - What is missing for on-smartphone FL research to be practical
        - Cross-platform training support
        - Ability to change the model & algorithm
    - Brief introduction to FedKit
        - FedKit features
            - (Checklist figure)
        - Our research app in production (Key contributions)
- System Description
    - Basic Architecture
        - Client-server relationship
    - Cross-Smartphone-Platform FL Training (detailed)
        - Description: cross-platform FL on smartphones with different OS and
            hardware configurations
        - Significance of cross-smartphone-platform training
            - They are needed for on-smartphone FL to be practical
            - Most ML frameworks don't support on-smartphone training
                - Only TensorFlow and Core ML are usable
                - No cross-smartphone-platform support from them
        - How it is done
            - Model conversion
                - (Figure of model conversion)
            - Unified parameter transmission allows simultaneous
                cross-platform FL
                <!-- TODO: Better naming. -->
    - Maximal ML Model Control from the Backend
        - FL frameworks assume models bundled with app
        - Researchers would want to update the model
        - How it is done: FL workflow with a preparation stage
            - (Figure of structure with workflow, numbered)
            - How we serve different models for different platform
- Experiment
    - Describe the app
    - How the app is deployed
        - (Figure of the setup)
- Conclusion and Future Work

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
