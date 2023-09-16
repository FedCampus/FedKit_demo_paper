# Draft 1 Outline

- Introduction
    - What is mobile FL
    - Related work in mobile FL
    - What is missing for on-smartphone FL research to be practical
        - Cross-platform training support
        - Ability to change the model & algorithm
    - Brief introduction to FedKit
        - FedKit features
            - (Checklist figure)
        - Our research app in production
- System Description
    - Architecture Overview
        - Client-server relationship
        - FL Workflow
        - (Figure of structure with workflow, numbered)
    - On-Smartphone Training (long)
        - Most ML frameworks don't support on-smartphone training
        - Only TensorFlow and Core ML work
        - Model conversion is the only way to go about models
    - Handling ML Models
        - Model Update from the Backend
            - Researchers would want to update the model
            - How it is done
        - Cross-Platform Model Support
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
