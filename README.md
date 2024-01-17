ismpc_walking-controller-superbuild
==

This repository is an extension repository for [mc-rtc-superbuild](https://github.com/mc-rtc/mc-rtc-superbuild)

It builds:

- Choreonoid fully equipped with HRP robots
- All dependencies of ismpc_walking
- ismpc_walking controller

Usage
--

```bash
git clone https://github.com/mc-rtc/mc-rtc-superbuild
git clone git@github.com:antodld/ispmc-walking-superbuild mc-rtc-superbuild/extensions/ismpc-walking-superbuild
cmake -S mc-rtc-superbuild -B mc-rtc-superbuild/build -DSOURCE_DESTINATION=$HOME/devel/src -DBUILD_DESTINATION=$HOME/devel/build 
cmake --build mc-rtc-superbuild/build --config RelWithDebInfo
```

Options
--

The following options are provided by this extension:

- `INTERNAL_MACHINE` (default: `OFF`)
