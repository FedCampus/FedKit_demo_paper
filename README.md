# AAAI Conference Demonstration Program

- [ ] ML model deployment pipeline.
    - [ ] Android.
        - [ ] Rename `dyn_flower_android_drf` to `FedKit`.
            - [ ] Follow up on upstream Android SDK (Steven).
    - [ ] iOS.
        - [ ] Dynamic model loading and backend connection.
        - [ ] **iOS basic demo to train with Flower server (Johnny, July 24)**.
- [ ] HealthKit demo.
    - [ ] User-facing functionality.
        - [ ] UI.
            - [ ] *FedAnalysis functionality (Beilong, July 27)*.
            - [ ] Port UI to Flutter.
                - [ ] Make basic training demo work with Flutter (Steven, July 25).
            - [ ] **Recruit dedicated UI people (Steven, WIP)**.
        - [ ] *Integrate background service (Steven)*.
            - [ ] **Integrate ML model (Steven)**.
                - [ ] **Data collection API to load training data
                    (Beilong, July 25)**.
- [ ] Literature review.

## Learning

Beilong:

- [ ] Kotlin coroutines.
    - [ ] Kotlin basics.

Johnny:

- [ ] iOS development basics.

Steven:

- [ ] Flutter.
- [ ] iOS development basics.

## Deferred

- [ ] ML model deployment pipeline.
    - [ ] Android.
        - [ ] Ensure background jobs run (Steven).
            Note: `AlarmManager` or `JobService`.
- [ ] HealthKit demo.
    - [ ] ML model: Transformer predicting workout probability (Beilong).
        - [ ] Basic transformer using HealthKit data (Beilong).
- [ ] Benchmarking with simulated heterogeneity.
    - [ ] Benchmark-app-specific instruction w/ backend (Steven).
    - [ ] On-device automatic benchmark.
        - [ ] Simulation.
            - [ ] Non-IID training options[^1].
                - [ ] Basic simulation for assigned model and data.
    - [ ] Benchmark the ML model for HealthKit demo (Steven).
- [ ] Backend deployment (Johnny).
    - [ ] HTTPS for backend server.
    - [ ] SSL for Flower server.

[^1]: <https://github.com/TL-System/plato/tree/2974ade33e7c2a9b596d64f96486252f2f4feb42/plato/samplers>
