# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="4.0.0-alpha.2"></a>
# [4.0.0-alpha.2](https://github.com/embark-framework/embark/compare/v4.0.0-alpha.1...v4.0.0-alpha.2) (2018-11-21)


### Bug Fixes

* **@embark/core:** don't expect `balance` on `accounts` ([4961f70](https://github.com/embark-framework/embark/commit/4961f70)), closes [#1067](https://github.com/embark-framework/embark/issues/1067)
* **@embark/core:** ensure 0x0 address are extended to full zero addresses ([d3f6b43](https://github.com/embark-framework/embark/commit/d3f6b43)), closes [#956](https://github.com/embark-framework/embark/issues/956)
* **@embark/webserver:** load embark-ui sources from the correct path ([96f7688](https://github.com/embark-framework/embark/commit/96f7688))
* **blockchain:** fix setting proxy to false not applying ([f50f106](https://github.com/embark-framework/embark/commit/f50f106))
* **ci:** make CI happy again by updating http paths to master branch ([af1bc90](https://github.com/embark-framework/embark/commit/af1bc90))
* **cmd:** removes -h as an option for host for the simulator ([43be2a2](https://github.com/embark-framework/embark/commit/43be2a2))
* **cockpit:** disable autocomplete in Login component ([3ddcd1f](https://github.com/embark-framework/embark/commit/3ddcd1f))
* **cockpit:** fix aside not opening correctly and typos ([a714e07](https://github.com/embark-framework/embark/commit/a714e07))
* **contracts:** replace $accounts for onDeploy too ([8831dfb](https://github.com/embark-framework/embark/commit/8831dfb))
* **contracts_manager:** fix object contract arguments ([6b61c8a](https://github.com/embark-framework/embark/commit/6b61c8a))
* **deployment:** add a message when the errror is about the input ([7a5035e](https://github.com/embark-framework/embark/commit/7a5035e))
* **ipc:** sends requests and events only when connected ([cabfa93](https://github.com/embark-framework/embark/commit/cabfa93)), closes [#1063](https://github.com/embark-framework/embark/issues/1063)
* **module/authenticator:** do not display log if no webserver ([97829c0](https://github.com/embark-framework/embark/commit/97829c0))
* **simulator:** adds `node` to sim command to comply with Windows ([1a29a8f](https://github.com/embark-framework/embark/commit/1a29a8f))
* **simulator:** change port depending of the type in config ([51e39c5](https://github.com/embark-framework/embark/commit/51e39c5))
* **simulator:** use config's gas limit if no option provided ([3353a05](https://github.com/embark-framework/embark/commit/3353a05)), closes [#1054](https://github.com/embark-framework/embark/issues/1054)
* **tests:** fix tests that fetched files from devleop ([ea2a656](https://github.com/embark-framework/embark/commit/ea2a656))
* **ui:** switch aside ([66e431c](https://github.com/embark-framework/embark/commit/66e431c))
* **ui:** white screen on text editor ([10caddd](https://github.com/embark-framework/embark/commit/10caddd))
* **whisper:** fix disabling whisper crashing blockchain ([b48d29a](https://github.com/embark-framework/embark/commit/b48d29a)), closes [#1027](https://github.com/embark-framework/embark/issues/1027)
* runtime environment needs to support locally installed embark ([23f19a0](https://github.com/embark-framework/embark/commit/23f19a0))


### Features

* add CRUD to file explorer ([f82d3de](https://github.com/embark-framework/embark/commit/f82d3de))
* add debug button to transaction and contract log ([184e1e2](https://github.com/embark-framework/embark/commit/184e1e2))
* adds support for swarm imports in Solidity ([62607b0](https://github.com/embark-framework/embark/commit/62607b0)), closes [#766](https://github.com/embark-framework/embark/issues/766)
* Allow parallel deploy ([3406ae8](https://github.com/embark-framework/embark/commit/3406ae8))
* **@embark/console:** determine suggestions automatically for a js object of the type 'command.' ([f206062](https://github.com/embark-framework/embark/commit/f206062))
* introduce function support for deploy lifecycle hooks ([8b68bec](https://github.com/embark-framework/embark/commit/8b68bec)), closes [#1029](https://github.com/embark-framework/embark/issues/1029)
* permanently save logs/events ([51b8224](https://github.com/embark-framework/embark/commit/51b8224))
* run coverage for bytecode and deployedBytecode ([f84d7f1](https://github.com/embark-framework/embark/commit/f84d7f1))
* strategy for deployment ([f9f4c28](https://github.com/embark-framework/embark/commit/f9f4c28))
* **@embark/cli:** add --template option to embark demo cli command ([89e3eb6](https://github.com/embark-framework/embark/commit/89e3eb6))
* **@embark/console:** better determine suggestions for any js object not just with the dot.' ([d427e62](https://github.com/embark-framework/embark/commit/d427e62))
* **cockpit:** add searching ENS names in search bar ([dca52d0](https://github.com/embark-framework/embark/commit/dca52d0))
* **cockpit:** make editor resizable ([1030607](https://github.com/embark-framework/embark/commit/1030607))
