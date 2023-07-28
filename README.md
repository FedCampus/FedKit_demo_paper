# AAAI Conference Demonstration Program

- [ ] ML model deployment pipeline.
    - [ ] Android.
        - [ ] Rename `dyn_flower_android_drf` to `FedKit`.
    - [ ] iOS.
        - [ ] Dynamic model loading and backend connection.
        - [ ] *iOS basic demo to train with Flower server (Johnny)*.
    - [ ] **Fix Docker CI (Johnny, ASAP)**.
- [ ] HealthKit demo.
    - [ ] **Alpha testing within group**.
    - [ ] User-facing functionality.
        - [ ] UI.
            - [x] *FedAnalysis functionality (Beilong, July 29)*.
            - [ ] Port UI to Flutter.
                - [ ] **Recruit dedicated UI people (Steven, WIP)**.
- [ ] Deployment.
    - [ ] **Investigate telemetry routes database error (Johnny, ASAP)**.
- [ ] Literature review.

## Learning

Beilong:

- [ ] Flutter.

Johnny:

- [ ] iOS development basics.
- [ ] Flutter.

Steven:

- [ ] Flutter.
- [ ] iOS development basics.

## Done

- [ ] ML model deployment pipeline.
    - [ ] Android.
        - [ ] Rename `dyn_flower_android_drf` to `FedKit`.
            - [x] Clean up `dyn_flower_android_drf` (Steven, July 27).
    - [x] CI to check style and test `dyn_flower_android_drf` (Steven, July 27).
    - [x] Make basic training demo work with Flutter (Steven, July 25).
- [ ] HealthKit demo.
    - [ ] User-facing functionality.
        - [x] Refactor HealthKit data collection (Steven & Beilong).
        - [ ] UI.
            - [ ] Port UI to Flutter.
                - [x] Make basic training demo work with Flutter (Steven, July 25).
                - [x] Try making Flutter work on Android (Steven, July 16).
        - [x] Integrate background service (Steven).
            - [x] Integrate ML model (Steven).
                - [x] Data collection API to load training data
                    (Beilong, July 25).
        - [x] What to provide: idea (Beilong, July 11).
    - [x] ML model (Beilong).
    - [x] Refactor & clean up (Beilong, July 8).
- [ ] Deployment.
    - [x] Change Flower server to send parameters via HTTP to workaround uWSGI.
        (Steven, July 26).
    - [x] Deploy FA backend on our machine (Johnny, Beilong, July 27).
        (server: 10.200.20.31:8005)
        - [x] **Collect FA backend to a repo (Beilong, July 26)**.

## Deferred

- [ ] ML model deployment pipeline.
    - [ ] Android.
        - [ ] Ensure background jobs run (Steven).
            Note: `AlarmManager` or `JobService`.
        - [ ] Follow up on upstream Android SDK (Steven).
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
