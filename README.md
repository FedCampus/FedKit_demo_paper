# AAAI Conference Demonstration Program

- [ ] ML model deployment pipeline.
    - [ ] Android.
        - [ ] Rename `dyn_flower_android_drf` to `FedKit`.
            - [ ] Follow up on upstream Android SDK (Steven).
    - [ ] iOS.
        - [ ] Dynamic model loading and backend connection.
        - [ ] **iOS basic demo to train with Flower server (Johnny, July 20)**.
- [ ] HealthKit demo.
    - [ ] User-facing functionality.
        - [ ] UI.
            - [ ] *FedAnalysis functionality (Beilong, July 21)*.
            - [ ] Port UI to Flutter.
        - [ ] *Integrate background service (Steven)*.
            - [ ] **Integrate ML model (Steven, July 19)**.
                - [ ] **Data collection API to load training data
                    (Beilong, July 19)**.
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
- [ ] Backend deployment (Johnny).
    - [ ] HTTPS for backend server.
    - [ ] SSL for Flower server.
