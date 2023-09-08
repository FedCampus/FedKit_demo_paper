# AAAI Conference Demonstration Program

- [ ] ML model deployment pipeline.
    - [ ] Android.
    - [ ] iOS.
- [ ] HealthKit demo.
    - [ ] **Alpha testing within group**.
- [ ] Deployment.
- [ ] Literature review.

## Learning

Johnny:

- [ ] iOS development basics.
- [ ] Flutter.

## Done

- [ ] ML model deployment pipeline.
    - [ ] iOS.
        - [x] Dynamic model loading and backend connection.
        - [x] iOS basic demo to train with Flower server (~~Johnny~~ Steven).
            - [x] iOS on-device training (Steven).
            - [x] Move more functionality to Flutter (Steven, Aug 11).
    - [ ] Android.
        - [x] Rename `dyn_flower_android_drf` to `FedKit`.
            - [x] Fix Docker CI (Johnny, July 29).
            - [x] Clean up `dyn_flower_android_drf` (Steven, July 27).
        - [x] Fix NaN in loss (Steven, July 29).
    - [x] CI to check style and test `dyn_flower_android_drf` (Steven, July 27).
    - [x] Make basic training demo work with Flutter (Steven, July 25).
- [ ] HealthKit demo.
    - [ ] Alpha testing within group.
        - [x] Huawei Health installation issue.
    - [x] Fix CI failing due to out of quota (~~Johnny~~ by paying).
    - [x] User-facing functionality.
        - [x] Fix Docker CI (Steven, Aug 9).
        - [x] Refactor HealthKit data collection (Steven & Beilong).
        - [x] UI.
            - [x] FedAnalysis functionality (Beilong).
                - [x] Basic FedAnalysis in Flutter (Beilong, Aug 7).
                - [x] FedAnalysis functionality basics (Beilong, July 28).
            - [x] Port UI to Flutter (Beilong & Luyao).
                - [x] Basic UI in Flutter (Renyuan & Luyao & Beilong, Aug 11).
                - [x] Recruit dedicated UI people (Steven, Aug 1).
                - [x] Make basic training demo work with Flutter (Steven, July 25).
                - [x] Try making Flutter work on Android (Steven, July 16).
        - [x] Integrate background service (Steven).
            - [x] Integrate ML model (Steven).
                - [x] Data collection API to load training data
                    (Beilong, July 25).
        - [x] What to provide: idea (Beilong, July 11).
    - [x] Use Fedkit in the Android side (Steven, July 30).
    - [x] ML model (Beilong).
    - [x] Refactor & clean up (Beilong, July 8).
    - [x] Basic CI tests (Steven).
- [ ] Deployment.
    - [x] Fix telemetry routes database error (~~Johnny, ASAP~~ Steven, July 29).
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
