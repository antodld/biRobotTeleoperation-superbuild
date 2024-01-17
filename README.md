biRobotTeleoperation-superbuild
==

This repository is an extension repository for [mc-rtc-superbuild](https://github.com/mc-rtc/mc-rtc-superbuild)

It builds:

- Choreonoid fully equipped with HRP robots
- All dependencies of mc_biRobotTeleop
- mc_biRobotTeleop controller

Usage
--

```bash
git clone https://github.com/mc-rtc/mc-rtc-superbuild
git clone git@github.com:antodld/biRobotTeleoperation-superbuild mc-rtc-superbuild/extensions/biRobotTeleoperation-superbuild
cmake -S mc-rtc-superbuild -B mc-rtc-superbuild/build -DSOURCE_DESTINATION=$HOME/devel/src -DBUILD_DESTINATION=$HOME/devel/build 
cmake --build mc-rtc-superbuild/build --config RelWithDebInfo
```

Options
--

The following options are provided by this extension:

- `INTERNAL_MACHINE` (default: `OFF`)
