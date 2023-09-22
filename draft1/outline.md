# Draft 1 Outline

- Introduction
    - What is on-smartphone FL
    - Significance[^1]
        - Academic: enable real-world cross-platform research
        - Industrial: use data on smartphones
    - Related work in mobile FL
        - (Chart of FL frameworks' platform support)
    - Difficulties in practical on-smartphone FL research
        - Cross-platform training support
        - Customizing FL in production
    - Brief introduction to FedKit
        - FedKit features
            - (Checklist figure)
        - Our research app in production (Key contributions)
- System Description
    - Architecture Overview
        - Client-server relationship
        - 2 innovations: the following
    - Cross-Smartphone-Platform FL (detailed)
        - Description: cross-platform FL on smartphones
        - Three steps
            - Model conversion to native format (TFLite & Core ML)
                - (Figure of model conversion)
            - Unified on-device training interface using native ML frameworks
            - Cross-platform parameter aggregation
    - Flexible In-Production FL Customization
        - FL frameworks assume models bundled with app
        - Researchers would want to update the model after the app is deployed
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

[^1]: <https://github.com/FedCampus/AAAI_conf_demo/pull/2#discussion_r1328039222>
