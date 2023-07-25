# Questions for Mr Yang

## Context: Prof Luo asks Mr Yang

> Y总，我带的几个学生做了个基于华为手表health kit的数据隐私保护的APP，现在做的差不多了，还有一些问题在完善，打算9月份在大学内部上线？想问问你明天有时间么，给你介绍下，也想请你给我们提一些建议

## Questions

- Launch: Which part should we finish first to launch fast?
- Marketing: How do we attract first-time users?
- Cross-platform app development: both native vs Flutter.
- Frontend: How do we develop UI efficiently, or find people to do so?
- Keep-alive: How do we properly keep the app alive when the device is idle as most modified "OS" actively kill background apps that are not in the whitelists?
- Active time length: As the training needs to happen when the device is idle (nights, charging), what is an ideal load distribution across time so we do not interrupt the user too much?
- As both platforms encrypt health data when the device is locked, and training happens mostly when the device is locked, we'll have to "cache" the health data in a local database, what is the best way of doing that as reading health data too frequently may cause alerts on-device and might affect user experience.

## 问题

- 上线：作为一个app，哪些部分最重要，应该优先完成？
- 推广：如何吸引首批使用者？
- 跨平台开发：原生 vs Flutter。
- 前端：如何高效地开发 UI，外包可行性如何？
- 保活：国产安卓会主动终止后台应用程序，如何保持后台活动？
- 后台活动时间分布：我们需要在设备空闲时训练（睡眠，充电）。合理的负载分布是什么样的，这样我们不会过多地打扰用户？

## Notes

- Continuous integration.
- Identify our users.
    - Students who are interested in their health-related position among peers,
        but want to preserve individual privacy.
- UI component library.
- Alarm users to train on foreground.
