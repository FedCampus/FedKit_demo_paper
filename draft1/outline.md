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
    - Architecture Overview
        - Client-server relationship
        - FL Workflow
        - (Figure of structure with workflow, numbered)
    - Cross-platform Federated Learning (long)
        - Most ML frameworks don't support on-smartphone training [Simple Chart], & Why it is significant
        - Only TensorFlow and Core ML work
        - [Describe the proposed framework] We propose a novel framework that uses model conversion to enable cross-platform federated learning on smartphones with different operating systems and hardware configurations. 
    - Handling ML Models (Should this section be merged with the previous section?)
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
