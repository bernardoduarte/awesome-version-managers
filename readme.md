# Awesome Version Managers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Version Managers

## Contents

- [Version Managers](#version-managers)
  - [Generic](#generic)
  - [Python](#python)
  - [Node.js](#nodejs)
  - [Ruby](#ruby)
  - [Go](#go)
  - [Rust](#rust)
  - [Java](#java)
  - [JVM](#jvm)
  - [Swift](#swift)
  - [PHP](#php)
  - [Perl](#perl)
  - [Lua](#lua)
  - [Elixir](#elixir)
  - [Erlang](#erlang)
  - [Julia](#julia)
  - [Crystal](#crystal)
  - [Flutter](#flutter)
  - [Scala](#scala)
  - [Terraform](#terraform)
  - [Solidity](#solidity)
  - [Xcode](#xcode)
  - [CMake](#cmake)
  - [Unity](#unity)
  - [Godot](#godot)
  - [R](#r)
  - [Zig](#zig)
  - [Neovim](#neovim)

## Version Managers

### Generic

- [anyenv](https://github.com/anyenv/anyenv) - A version manager wrapper allowing maintenance of multiple version managers.
- [asdf-vm](https://github.com/asdf-vm/asdf) - An extendable version manager using a plugin structure to handle new version managers.
- [rtx](https://github.com/jdxcode/rtx) - An `asdf` drop-in replacement written in Rust.
- [proto](https://github.com/moonrepo/proto) - A pluggable next-generation version manager for multiple programming languages as unified toolchain.

### Python

- [pyenv](https://github.com/pyenv/pyenv) - A tool that allows you to switch between multiple versions of Python.
- [pyenv-win](https://github.com/pyenv-win/pyenv-win) - A porting of pyenv for Windows.
- [pyflow](https://github.com/David-OConnor/pyflow) - A multipurpose Python environment manager.
- [pythonz](https://github.com/saghul/pythonz) - A program to automate the building and installation of Python versions.

### Node.js

- [fnm](https://github.com/Schniz/fnm) - Fast and simple Node.js version manager built in Rust
- [nvm](https://github.com/nvm-sh/nvm) - A version manager for Node.js, designed to be installed per user, and invoked per shell.
- [nvm-windows](https://github.com/coreybutler/nvm-windows) - Same of nvm, but for Windows.
- [n](https://github.com/tj/n) - An interactive manager that has no subshells and no profile setup.
- [volta](https://github.com/volta-cli/volta) - A JavaScript tool manager, designed to provide seamless, fully isolated node environments.
- [nodenv](https://github.com/nodenv/nodenv) - A tool that can automatically select the appropriate node version for a given project and doesn't require shell integration or overriding of builtin commands.
- [nvs](https://github.com/jasongin/nvs) - A cross-platform utility for switching between different versions and forks of Node.js.
- [nodebrew](https://github.com/hokaccha/nodebrew) - A simple Node.js version manager.
- [nve](https://github.com/ehmicky/nve) - Run any command on specific Node.js versions.
- [chnode](https://github.com/tkareine/chnode) - A lightweight Node.js version switcher that allows for auto-switching by updating the PATH, inspired by chruby.
- [pnpm](https://github.com/pnpm/pnpm) - A fast and disk space efficient package manager that can also manage Node.js versions via it's env command.
- [nvm-rust](https://github.com/beeequeue/nvm-rust) - A cross platform Node.js version manager made in Rust.

### Ruby

- [rbenv](https://github.com/rbenv/rbenv) - A manager that focus on switching Ruby versions.
- [rbenv-win](https://github.com/nak1114/rbenv-win) - A porting of rbenv to Windows.
- [rvm](https://github.com/rvm/rvm) - A tool that is loaded into the shell, overrides some commands and also manages gemsets.
- [uru](https://bitbucket.org/jonforums/uru) - A lightweight, multi-platform command line tool that helps you use the multiple rubies, like MRI, JRuby and Rubinius.
- [chruby](https://github.com/postmodern/chruby) - A Ruby version switcher that allows for auto-switching, updates PATH and has around 100 lines of code.
- [frum](https://github.com/TaKO8Ki/frum) - A fast and modern Ruby version manager written in Rust that is also cross-platform.

### Go

- [gvm](https://github.com/moovweb/gvm) - An interface to manage Go versions.
- [goenv](https://github.com/syndbg/goenv) - Version manager like pyenv and rbenv, but for Go.
- [g](https://github.com/stefanmaric/g) - A simples Go version manager inspired by `n`.

### Rust

- [rustup](https://github.com/rust-lang/rustup) - A manager that installs Rust from official release channels and allows to switch between stable, beta, and nightly compilers.

### Java

- [jenv](https://github.com/linux-china/jenv) - A cross-platform tool for managing parallel Versions of JDKs which allows for installing, switching, removing and listing candidates.
- [jEnv](https://github.com/jenv/jenv) - A version switcher for Java that does not handle installation. 
- [jabba](https://github.com/shyiko/jabba) - A cross-platform Java manager that allows for installation and switching of JDKs.

### JVM
- [SDKMAN!](https://github.com/sdkman/sdkman-cli) - Install Software Development Kits for the JVM such as Java, Scala, Kotlin and Groovy. Ant, Gradle, Grails, Maven, SBT, Spark, Spring Boot, Vert.x and many others also supported.

### Swift

- [swiftenv](https://github.com/kylef/swiftenv) - A Swift manager that changes version per user, set a per-project version and allows you to override the version with an environmental variable.
- [swiftly](https://github.com/swift-server/swiftly) - A CLI tool for installing, managing, and switching between Swift toolchains, written in Swift.

### PHP

- [phpbrew](https://github.com/phpbrew/phpbrew) - A utility that builds and installs multiple version of PHP in your HOME directory allowing of switching between them.
- [phpenv](https://github.com/phpenv/phpenv) - A version manager that operates binaries on the user directory and utilizes shims. 

### Perl

- [perlbrew](https://github.com/gugod/App-perlbrew) - A tool that manages multiple Perl environments and allows switching between them.
- [plenv](https://github.com/tokuhirom/plenv) - A manager that installs multiple versions on the home directory, uses shims and allows to set local version per directory.

### Lua

- [luaver](https://github.com/DhavalKapil/luaver) - A helper to manage and switch between different versions of Lua, LuaJIT and Luarocks.
- [lenv](https://github.com/mah0x211/lenv) - A Lua version manager that allows installation and switching between multiple versions.

### Elixir

- [kiex](https://github.com/taylor/kiex) - A utility that allows build and switch between different Elixir versions.
- [exenv](https://github.com/askagirl/exenv-1) - A Elixir version manager based on rbenv.

### Erlang

- [evm](https://github.com/robisonsantos/evm) - A tool that allows you to install multiple versions of erlang on your system and switch between them.

### Julia

- [juliavm](https://github.com/pmargreff/juliavm) - A CLI tool which allows you to install, manage, and work with Julia environments and switch between them.
- [jlenv](https://github.com/HiroakiMikami/jlenv) - A Julia version manager based on rbenv.

### Crystal

- [crenv](https://github.com/crenv/crenv) - A Crystal version manager based on rbenv.


### Flutter

- [fvm](https://github.com/leoafarias/fvm) - A version manager allowing to reference Flutter SDK version on a per-project basis, allows you to have multiple versions installed.

### Scala

- [svm](https://github.com/yuroyoro/svm) - A version manager that switches and installs multiple Scala versions.

### Terraform

- [tfenv](https://github.com/tfutils/tfenv) - A Terraform version manager inspired by rbenv.

### Solidity

- [svm-rs](https://github.com/roynalnaruto/svm-rs) - A Solidity compiler version manager made in Rust.

### Xcode

- [xcodes](https://github.com/XcodesOrg/xcodes) - A command-line tool to install and switch between multiple versions of Xcode.
- [Xcodes.app](https://github.com/XcodesOrg/XcodesApp) - An app that offers the easiest way to install and switch between multiple versions of Xcode.

### CMake

- [cvm](https://github.com/ParagonPawns/cmake-version-manager) - A cross platform command-line tool that help manage currently installed versions of CMake.

### Unity

- [uvm](https://github.com/Larusso/unity-version-manager) - A tool which allows to install and manage multiple Unity versions on a system from the command-line that is also compatible with Unity-Hub.

### Godot

- [Godots](https://github.com/MakovWait/godots) - An app that manages your Godot versions and projects with support for all platforms while also allowing for theming.
- [Godot Manager](https://github.com/eumario/godot-manager) - An app made in C# that can manage the engine versions of Godot from the official Github repository, as well as getting updates from new releases.
- [Hourglass](https://gitlab.com/jwestman/hourglass) - A project manager that can also manage multiple versions of Godot engine with just a few clicks and that supports custom engine builds.
- [GVM](https://github.com/noidexe/godot-version-manager) - A simple app that can install and remove any version of Godot, even the alpha, beta, rc and dev versions.

### R

- [rig](https://github.com/r-lib/rig) - A cross platform R version manager with no system requirements on any platform.

### Zig

- [zvm](https://github.com/tristanisham/zvm) - A version manager made in Go that works on Linux, BSD, MacOS, *nix systems including Windows.
- [zigup](https://github.com/marler8997/zigup) - A Zig version manager made entirely with Zig.

### Neovim

- [bob](https://github.com/MordechaiHadad/bob) - A cross-platform and easy-to-use Neovim version manager, allowing for easy switching between versions right from the command line.

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
