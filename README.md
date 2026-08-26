# Awesome cross platform nodejs with stars

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logo_dark.svg"/>
    <img alt="awesome-cross-platform-nodejs logo" src="logo.svg" width="500"/>
  </picture>
  <br>
  <a href="https://awesome.re">
	  <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
  <p>A curated list of awesome developer tools for writing cross-platform Node.js code.</p>
</div>

## Contents

* [Resources](#resources)
* [Applications](#applications)
  * [Development environment](#development-environment)
  * [Continuous integration](#continuous-integration)
  * [Virtualization](#virtualization)
  * [Compatibility](#compatibility)
  * [Databases](#databases)
* [Libraries](#libraries)
  * [OS identification](#os-identification)
  * [Shell](#shell)
  * [Environment](#environment)
  * [Filesystem](#filesystem)
  * [Signals](#signals)
  * [Processes](#processes)
  * [Streams](#streams)
  * [Desktop UI](#desktop-ui)
  * [Windows registry](#windows-registry)
* [Known issues](#known-issues)
* [Support](#support)

## Resources

* [Microsoft Node.js Guidelines](https://github.com/Microsoft/nodejs-guidelines) ⚠️ Archived - Tips, tricks, and resources for working with Node.js on Microsoft platforms.
* [Cross-platform Node.js guide](https://github.com/ehmicky/cross-platform-node-guide) ⭐ 1,421 | 🐛 0 | 🌐 JavaScript | 📅 2025-05-25 - How to write cross-platform Node.js code.
* [Cross-platform terminal characters](https://github.com/ehmicky/cross-platform-terminal-characters) ⭐ 249 | 🐛 0 | 🌐 JavaScript | 📅 2025-05-25 - All the characters that work on most terminals and most operating systems.
* [Core Node.js documentation](https://nodejs.org/en/docs/) - Especially the [`os`](https://nodejs.org/api/os.html), [`path`](https://nodejs.org/api/path.html), [`fs`](https://nodejs.org/api/fs.html), [`process`](https://nodejs.org/api/process.html) and [`child_process`](https://nodejs.org/api/child_process.html) modules.
* [Writing Cross-Platform Node.js](http://shapeshed.com/writing-cross-platform-node/) - Great tutorial covering many common issues that arise when writing cross-platform code: path creation, script execution, newline characters.

## Applications

### Development environment

* [nvm](https://github.com/creationix/nvm) ⭐ 94,749 | 🐛 398 | 🌐 Shell | 📅 2026-08-18 / [n](https://github.com/tj/n) ⭐ 19,510 | 🐛 4 | 🌐 Shell | 📅 2026-08-22 - Node version manager for macOS/Linux.
* [nvm-windows](https://github.com/coreybutler/nvm-windows) ⭐ 47,474 | 🐛 86 | 🌐 Go | 📅 2026-08-26 - Manage multiple installations of Node.js on a Windows computer.
* [windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) ⚠️ Archived - Install C++ Build Tools for Windows using npm.
* [npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) ⚠️ Archived - Upgrade npm on Windows.
* [Node.js](https://nodejs.org/en/download/) - Node.js installer for various platforms.

### Continuous integration

* [AppVeyor](http://www.appveyor.com/) - Focused on Windows. Free tiers are available for OSS projects.
* [Travis](https://travis-ci.org/) - Windows/macOS/Linux. Free for OSS projects.
* [Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines/) - Windows/macOS/Linux. Free for OSS projects with 10 parallel jobs.
* [Github Action](https://github.com/features/actions) - Windows/macOS/Linux. GitHub Actions makes it easy to automate all your software workflows.
* [Gitlab CI](https://docs.gitlab.com/ee/ci/) - Windows/macOS/Linux. GitLab CI/CD is a tool built into GitLab for software development.

### Virtualization

* [ievms](https://github.com/amichaelparker/ievms) ⭐ 68 | 🐛 0 | 🌐 Shell | 📅 2018-08-16 - Automated installer for the free virtual machine images that Microsoft provides for testing on multiple versions of IE. These images can be useful for cross-platform testing various technologies, however make sure you read and understand Microsofts' licensing.
* [VirtualBox](https://www.virtualbox.org/wiki/Downloads) - General purpose software for running x86 virtual machines.
* [Docker](https://www.docker.com/) - Software platform to create, deploy and manage virtualized application containers on a common operating system, with an ecosystem of allied tools.

### Compatibility

* [Wine](https://www.winehq.org/) - Run Windows API calls on Linux, Mac, BSD and Solaris.
* [Cygwin](https://www.cygwin.com/) - Run POSIX on Windows.
* [WSL](https://docs.microsoft.com/en-us/windows/wsl/install-win10) - Run the Linux command line on Windows (ELF binary execution, system calls, filesystem, Bash, core utilities, common applications).
* [MinGW](http://www.mingw.org/) - `gcc` on Windows.
* [msys](http://www.mingw.org/wiki/msys) / [Git Bash](https://gitforwindows.org/) - Bash on Windows.

### Databases

* [Redis](https://github.com/tporadowski/redis) ⭐ 10,251 | 🐛 82 | 🌐 C | 📅 2026-08-22 - Native port of Redis for Windows.

## Libraries

### OS identification

* [systeminformation](https://github.com/sebhildebrandt/systeminformation) ⭐ 3,129 | 🐛 103 | 🌐 JavaScript | 📅 2026-08-26 - Hardware/software system information.
* [is-wsl](https://github.com/sindresorhus/is-wsl) ⭐ 198 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-15 - Detect whether current platform is WSL (Windows Subsystem for Linux).
* [os-name](https://github.com/sindresorhus/os-name) ⭐ 149 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-02 - Get the name of the current operating system.
* [getos](https://github.com/retrohacker/getos) ⭐ 79 | 🐛 6 | 🌐 JavaScript | 📅 2023-01-06 - Retrieve the current OS, including Linux distribution.
* [is-windows](https://github.com/jonschlinkert/is-windows) ⚠️ Archived - Detect whether the current platform is Windows.

### Shell

* [shelljs](https://github.com/shelljs/shelljs) ⭐ 14,399 | 🐛 105 | 🌐 JavaScript | 📅 2026-08-12 - Cross-platform Unix shell commands.
* [execa](https://github.com/sindresorhus/execa) ⭐ 7,592 | 🐛 1 | 🌐 JavaScript | 📅 2026-07-31 - Cross-platform implementation of `child_process.{execFile,exec}`.
* [node-windows](https://github.com/coreybutler/node-windows) ⭐ 2,936 | 🐛 73 | 🌐 JavaScript | 📅 2024-10-01 - Windows support for Node.js scripts (daemons, eventlog, UAC, etc).
* [clipboardy](https://github.com/sindresorhus/clipboardy) ⭐ 1,983 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-23 / [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) ⭐ 509 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-03 - Cross-platform copy/paste.
* [cross-spawn](https://github.com/IndigoUnited/node-cross-spawn) ⭐ 1,171 | 🐛 31 | 🌐 JavaScript | 📅 2024-11-18 - Cross-platform implementation of `child_process.spawn()`.
* [log-symbols](https://github.com/sindresorhus/log-symbols) ⭐ 772 | 🐛 1 | 🌐 JavaScript | 📅 2025-05-21 - Colored symbols for various log levels with Windows fallbacks.
* [figures](https://github.com/sindresorhus/figures) ⭐ 634 | 🐛 0 | 🌐 JavaScript | 📅 2024-10-28 - Unicode symbols with Windows fallbacks.
* [gulp-execa](https://github.com/ehmicky/gulp-execa) ⭐ 56 | 🐛 0 | 🌐 JavaScript | 📅 2025-11-08 - Cross-platform command execution in Gulp.js.

### Environment

* [cross-env](https://github.com/kentcdodds/cross-env) ⚠️ Archived - Set environment variables cross-platform.
* [which](https://github.com/npm/node-which) ⭐ 352 | 🐛 7 | 🌐 JavaScript | 📅 2026-07-02 - Cross-platform implementation of Unix's `which`.
* [user-home](https://github.com/sindresorhus/user-home) ⚠️ Archived - Get the path to the user home directory. Cross-platform.
* [username](https://github.com/sindresorhus/username) ⭐ 145 | 🐛 0 | 🌐 JavaScript | 📅 2023-11-14 - Get the current username.
* [osenv](https://github.com/npm/osenv) ⚠️ Archived - Cross-platform environment variables.
* [is-elevated](https://github.com/sindresorhus/is-elevated) ⭐ 44 | 🐛 0 | 🌐 JavaScript | 📅 2021-08-11 - Check if the process is running with elevated privileges.

### Filesystem

* [chokidar](https://github.com/paulmillr/chokidar) ⭐ 12,224 | 🐛 45 | 🌐 TypeScript | 📅 2026-08-16 - Improved cross-platform file watching.
* [fs-extra](https://github.com/jprichardson/node-fs-extra) ⭐ 9,595 | 🐛 13 | 🌐 JavaScript | 📅 2026-07-23 - Combines `graceful-fs` with better JSON file reading and promises.
* [rimraf](https://github.com/isaacs/rimraf) ⭐ 5,851 | 🐛 10 | 🌐 TypeScript | 📅 2026-05-15 / [del](https://github.com/sindresorhus/del) ⭐ 1,344 | 🐛 16 | 🌐 JavaScript | 📅 2026-07-21 - Delete files and folders. Cross-platform.
* [graceful-fs](https://github.com/isaacs/node-graceful-fs) ⭐ 1,302 | 🐛 49 | 🌐 JavaScript | 📅 2025-10-25 - Improves the `fs` module, especially on Windows.
* [make-dir](https://github.com/sindresorhus/make-dir) ⭐ 481 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-10 - Cross-platform `mkdir -p`.
* [cpy](https://github.com/sindresorhus/cpy) ⭐ 439 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-23 - Copy files. Cross-platform.
* [readdirp](https://github.com/paulmillr/readdirp) ⭐ 421 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-06 - Recursive version of `fs.readdir()`.
* [dev-null-cli](https://github.com/sindresorhus/dev-null-cli) ⭐ 93 | 🐛 0 | 🌐 JavaScript | 📅 2021-10-14 - Cross-platform `/dev/null`.
* [global-cache-dir](https://github.com/ehmicky/global-cache-dir) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2025-05-25 - Get the global OS-specific cache directory.
* [any-path](https://github.com/bcoe/any-path) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2015-12-21 - Use Windows and POSIX paths interchangeably when fetching values from an object.

### Signals

* [fkill](https://github.com/sindresorhus/fkill) ⭐ 797 | 🐛 2 | 🌐 JavaScript | 📅 2026-01-14 - Kill processes. Cross-platform.
* [human-signals](https://github.com/ehmicky/human-signals) ⭐ 286 | 🐛 0 | 🌐 JavaScript | 📅 2025-05-25 - Human-friendly process signals.
* [signal-exit](https://github.com/tapjs/signal-exit) ⭐ 200 | 🐛 11 | 🌐 TypeScript | 📅 2025-10-25 - Cross-platform `exit` handler.

### Processes

* [ps-list](https://github.com/sindresorhus/ps-list) ⭐ 287 | 🐛 4 | 🌐 JavaScript | 📅 2026-02-03 - Get running processes.
* [process-exists](https://github.com/sindresorhus/process-exists) ⭐ 62 | 🐛 1 | 🌐 JavaScript | 📅 2021-11-04 - Check if a process exists.

### Streams

* [random-bytes-readable-stream](https://github.com/sindresorhus/random-bytes-readable-stream) ⭐ 77 | 🐛 0 | 🌐 JavaScript | 📅 2021-08-12 - Cross-platform `fs.createReadStream('/dev/urandom')`.
* [noop-stream](https://github.com/sindresorhus/noop-stream) ⭐ 50 | 🐛 0 | 🌐 JavaScript | 📅 2023-05-27 - Cross-platform `fs.createReadStream('/dev/null')`.

### Desktop UI

* [node-notifier](https://github.com/mikaelbr/node-notifier) ⭐ 5,845 | 🐛 128 | 🌐 JavaScript | 📅 2024-06-24 - Cross-platform desktop notifications.
* [open](https://github.com/sindresorhus/open) ⭐ 3,497 | 🐛 3 | 🌐 JavaScript | 📅 2026-08-13 - Opens stuff like websites, files, executables. Cross-platform.

### Windows registry

* [node-winreg](https://github.com/fresc81/node-winreg) ⭐ 218 | 🐛 20 | 🌐 JavaScript | 📅 2025-02-19 - Access the Windows registry.
* [windows-registry-node](https://github.com/CatalystCode/windows-registry-node) ⭐ 117 | 🐛 22 | 🌐 JavaScript | 📅 2019-12-10 - Access/modify the Windows registry and set file associations.
* [rage-edit](https://github.com/MikeKovarik/rage-edit) ⭐ 56 | 🐛 4 | 🌐 JavaScript | 📅 2021-08-20 - Access/modify the Windows registry.

## Known issues

* [cmd.exe unicode woes](https://github.com/nodejs/node-v0.x-archive/issues/7940) ⚠️ Archived - By default, `cmd.exe` does not display Unicode characters on Windows.
* [spawn issues](https://github.com/nodejs/node-v0.x-archive/issues/2318) ⚠️ Archived - `child_process.spawn()` behavior is not consistent between Windows and Linux.
* [exec() behavior between shells](https://github.com/isaacs/spawn-wrap#contracts-and-caveats) ⭐ 41 | 🐛 22 | 🌐 JavaScript | 📅 2026-05-21 - Depending on the shell being used, e.g., bash vs. dash, `child_process.exec()` has inconsistent exit behavior.

## See also

* [awesome-desktop-js](https://github.com/styfle/awesome-desktop-js) ⭐ 870 | 🐛 6 | 📅 2026-05-09 - List of tools to build JavaScript applications on the desktop.

## Support

If you found an error or would like to add more information, *don't hesitate* to
[submit an issue on GitHub](../../issues).

Everyone is welcome regardless of personal background. We enforce a
[Code of conduct](CODE_OF_CONDUCT.md) in order to promote a positive and
inclusive environment.

## Contributing

This project was made with ❤️. The simplest way to give back is by starring and
sharing it online.

If the documentation is unclear or has a typo, please click on the page's `Edit`
button (pencil icon) and suggest a correction.

If you would like to help us fix an error or add more information, please check
our [guidelines](contributing.md). Pull requests are welcome!

Thanks go to these wonderful people:

<!-- ALL-CONTRIBUTORS-LIST:START -->

<!-- prettier-ignore -->

<table><tr><td align="center"><a href="https://twitter.com/benjamincoe"><img src="https://avatars3.githubusercontent.com/u/194609?v=4" width="100px;" alt="Benjamin E. Coe"/><br /><sub><b>Benjamin E. Coe</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=bcoe" title="Code">💻</a> <a href="#ideas-bcoe" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=bcoe" title="Documentation">📖</a></td><td align="center"><a href="https://twitter.com/ehmicky"><img src="https://avatars2.githubusercontent.com/u/8136211?v=4" width="100px;" alt="ehmicky"/><br /><sub><b>ehmicky</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=ehmicky" title="Code">💻</a> <a href="#ideas-ehmicky" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=ehmicky" title="Documentation">📖</a></td><td align="center"><a href="https://sindresorhus.com"><img src="https://avatars1.githubusercontent.com/u/170270?v=4" width="100px;" alt="Sindre Sorhus"/><br /><sub><b>Sindre Sorhus</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=sindresorhus" title="Code">💻</a> <a href="#ideas-sindresorhus" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=sindresorhus" title="Documentation">📖</a></td><td align="center"><a href="https://fb.com/RemoveU"><img src="https://avatars1.githubusercontent.com/u/19208123?v=4" width="100px;" alt="Hongarc"/><br /><sub><b>Hongarc</b></sub></a><br /><a href="#design-Hongarc" title="Design">🎨</a> <a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=Hongarc" title="Documentation">📖</a> <a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=Hongarc" title="Code">💻</a></td><td align="center"><a href="https://kentcdodds.com"><img src="https://avatars0.githubusercontent.com/u/1500684?v=4" width="100px;" alt="Kent C. Dodds"/><br /><sub><b>Kent C. Dodds</b></sub></a><br /><a href="#ideas-kentcdodds" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://nz.linkedin.com/in/jsonc11"><img src="https://avatars0.githubusercontent.com/u/5185660?v=4" width="100px;" alt="Jason Cooke"/><br /><sub><b>Jason Cooke</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=Jason-Cooke" title="Documentation">📖</a></td><td align="center"><a href="http://aronhafner.com"><img src="https://avatars0.githubusercontent.com/u/3322693?v=4" width="100px;" alt="Aron Hafner"/><br /><sub><b>Aron Hafner</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=alonalon" title="Documentation">📖</a></td></tr><tr><td align="center"><a href="https://github.com/ShPelles"><img src="https://avatars0.githubusercontent.com/u/43875468?v=4" width="100px;" alt="ShPelles"/><br /><sub><b>ShPelles</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=ShPelles" title="Documentation">📖</a></td><td align="center"><a href="https://github.com/Frederick-S"><img src="https://avatars1.githubusercontent.com/u/1182395?v=4" width="100px;" alt="Xiaodan Mao"/><br /><sub><b>Xiaodan Mao</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=Frederick-S" title="Documentation">📖</a></td><td align="center"><a href="https://github.com/jamestalmage"><img src="https://avatars0.githubusercontent.com/u/4082216?v=4" width="100px;" alt="James Talmage"/><br /><sub><b>James Talmage</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=jamestalmage" title="Documentation">📖</a></td><td align="center"><a href="http://sylvain.pontoreau.com"><img src="https://avatars3.githubusercontent.com/u/3357643?v=4" width="100px;" alt="Sylvain PONTOREAU"/><br /><sub><b>Sylvain PONTOREAU</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=spontoreau" title="Documentation">📖</a></td><td align="center"><a href="https://www.ceriously.com"><img src="https://avatars1.githubusercontent.com/u/229881?v=4" width="100px;" alt="Steven"/><br /><sub><b>Steven</b></sub></a><br /><a href="#ideas-styfle" title="Ideas, Planning, & Feedback">🤔</a></td></tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) ⭐ 8,093 | 🐛 89 | 🌐 MDX | 📅 2026-08-21 specification.

## License

[![License](https://img.shields.io/github/license/bcoe/awesome-cross-platform-nodejs.svg?color=4cc61e\&logo=github)](https://creativecommons.org/licenses/by-sa/4.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-26._
