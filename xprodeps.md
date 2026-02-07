# spdlog dependencies

|project|license [^_l]|description [dependencies]|version|source|diff [^_d]|
|-------|-------------|--------------------------|-------|------|----------|
|<a id='spdlog' />[spdlog](https://github.com/gabime/spdlog/wiki)|[MIT](https://github.com/gabime/spdlog?tab=License-1-ov-file 'MIT License')|Fast C++ logging library [deps: _fmt_]| |[upstream](https://github.com/gabime/spdlog 'github.com/gabime/spdlog')|  [patch]|
|<a id='fmt' />[fmt](https://fmt.dev/)|[MIT](https://github.com/fmtlib/fmt?tab=MIT-1-ov-file#readme 'MIT License')|A modern formatting library|[xpv11.2.0.15](https://github.com/externpro/fmt/releases/tag/xpv11.2.0.15 'release')|[repo](https://github.com/externpro/fmt 'github.com/externpro/fmt') [upstream](https://github.com/fmtlib/fmt 'github.com/fmtlib/fmt')|[diff](https://github.com/externpro/fmt/compare/11.2.0...xpv11.2.0.15 'github.com/externpro/fmt/compare/11.2.0...xpv11.2.0.15') [patch]|

![deps](xprodeps.svg 'dependencies')

Dependency version check: all 1 parent-manifest versions match pinned versions.

|diff  |description|
|------|-----------|
|patch |diff modifies/patches existing cmake|
|intro |diff introduces cmake|
|auto  |diff adds cmake to replace autotools/configure/make|
|native|diff adds cmake but uses existing build system|
|bin   |diff adds cmake to repackage binaries built elsewhere|
|fetch |diff adds cmake and utilizes FetchContent|

[^_l]: see [SPDX License List](https://spdx.org/licenses/ '') for a list of commonly found licenses
[^_d]: see table above with description of diff
