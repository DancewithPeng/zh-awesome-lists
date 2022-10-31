# Awesome Rust [![build badge](https://github.com/rust-unofficial/awesome-rust/actions/workflows/rust.yml/badge.svg?branch=main)](https://github.com/rust-unofficial/awesome-rust/actions/workflows/rust.yml) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/rust-unofficial/awesome-rust/)

A curated list of Rust code and resources.

If you want to contribute, please read [this](CONTRIBUTING.md).

## Table of contents

<!-- toc -->

- [Applications](#applications)
  * [Audio and Music](#audio-and-music)
  * [Cryptocurrencies](#cryptocurrencies)
  * [Database](#database)
  * [Emulators](#emulators)
  * [Games](#games)
  * [Graphics](#graphics)
  * [Image processing](#image-processing)
  * [Industrial automation](#industrial-automation)
  * [Observability](#observability)
  * [Operating systems](#operating-systems)
  * [Productivity](#productivity)
  * [Security tools](#security-tools)
  * [Simulation](#simulation)
  * [System tools](#system-tools)
  * [Task scheduling](#task-scheduling)
  * [Text editors](#text-editors)
  * [Text processing](#text-processing)
  * [Utilities](#utilities)
  * [Video](#video)
  * [Virtualization](#virtualization)
  * [Web](#web)
  * [Web Servers](#web-servers)
- [Development tools](#development-tools)
  * [Build system](#build-system)
  * [Debugging](#debugging)
  * [Deployment](#deployment)
  * [Embedded](#embedded)
  * [FFI](#ffi)
  * [Formatters](#formatters)
  * [IDEs](#ides)
  * [Profiling](#profiling)
  * [Services](#services)
  * [Static analysis](#static-analysis)
  * [Testing](#testing)
  * [Transpiling](#transpiling)
- [Libraries](#libraries)
  * [Artificial Intelligence](#artificial-intelligence)
    + [Genetic algorithms](#genetic-algorithms)
    + [Machine learning](#machine-learning)
  * [Astronomy](#astronomy)
  * [Asynchronous](#asynchronous)
  * [Audio and Music](#audio-and-music-1)
  * [Authentication](#authentication)
  * [Automotive](#automotive)
  * [Bioinformatics](#bioinformatics)
  * [Caching](#caching)
  * [Cloud](#cloud)
  * [Command-line](#command-line)
  * [Compression](#compression)
  * [Computation](#computation)
  * [Concurrency](#concurrency)
  * [Configuration](#configuration)
  * [Cryptography](#cryptography)
  * [Data processing](#data-processing)
  * [Data streaming](#data-streaming)
  * [Data structures](#data-structures)
  * [Data visualization](#data-visualization)
  * [Database](#database-1)
  * [Date and time](#date-and-time)
  * [Distributed systems](#distributed-systems)
  * [Domain driven design](#domain-driven-design)
  * [Email](#email)
  * [Encoding](#encoding)
  * [Filesystem](#filesystem)
  * [Functional Programming](#functional-programming)
  * [Game development](#game-development)
  * [Geospatial](#geospatial)
  * [Graphics](#graphics-1)
  * [GUI](#gui)
  * [Image processing](#image-processing-1)
  * [Language specification](#language-specification)
  * [Logging](#logging)
  * [Macro](#macro)
  * [Markup language](#markup-language)
  * [Mobile](#mobile)
  * [Network programming](#network-programming)
  * [Parsing](#parsing)
  * [Peripherals](#peripherals)
  * [Platform specific](#platform-specific)
  * [Scripting](#scripting)
  * [Simulation](#simulation-1)
  * [Task scheduling](#task-scheduling-1)
  * [Template engine](#template-engine)
  * [Text processing](#text-processing-1)
  * [Text search](#text-search)
  * [Unsafe](#unsafe)
  * [Virtualization](#virtualization-1)
  * [Web programming](#web-programming)
- [Registries](#registries)
- [Resources](#resources)
- [License](#license)

<!-- tocstop -->

## Applications

See also [Rust — Production](https://www.rust-lang.org/production) organizations running Rust in production.

* [alacritty](https://github.com/alacritty/alacritty) — 跨平台、GPU增强的终端模拟器
* [asm-cli-rust](https://github.com/cch123/asm-cli-rust) — 用rust编写的交互式程序集shell。
* [cloudflare/boringtun](https://github.com/cloudflare/boringtun) — 用户空间WireGuard VPN实现[！[build badge](https://img.shields.io/badge/crates.io-v0.2.0-orange.svg)](https://crates.io/crates/boringtun)
* [datafusion](https://github.com/apache/arrow-datafusion) — Apache Arrow DataFusion和Ballista查询引擎
* [denoland/deno](https://github.com/denoland/deno) — 使用V8、Rust和Tokio[！[Build Status]构建的安全JavaScript/TypeScript运行时(https://github.com/denoland/deno/workflows/ci/badge.svg?branch=master&event=push)](https://github.com/denoland/deno/actions)
* [Factotum](https://github.com/snowplow/factotum) — [以编程方式运行数据管道的系统](https://snowplow.io/blog/introducing-factotum-data-pipeline-runner/)[！[构建徽章](https://api.travis-ci.org/snowplow/factotum.svg?branch=master)](https://travis-ci.org/snowplow/factotum)
* [fcsonline/drill](https://github.com/fcsonline/drill) — 受Ansible语法[！[build badge]启发的HTTP负载测试应用程序(https://api.travis-ci.org/fcsonline/drill.svg?branch=master)](https://travis-ci.org/fcsonline/drill)
* [fend](https://github.com/printfn/fend) - 任意精度单位感知计算器[！[build](https://github.com/printfn/fend/workflows/build/badge.svg)](https://github.com/printfn/fend)
* [Fractalide](https://github.com/fractalide/fractalide) — 简单Rust微服务
* [habitat](https://github.com/habitat-sh/habitat) — 由Chef创建的用于构建、部署和管理应用程序的工具。
* [Herd](https://github.com/imjacobclark/Herd) — 一个实验性HTTP负载测试应用程序
* [jedisct1/flowgger](https://github.com/awslabs/flowgger) — 快速、简单、轻便的数据采集器
* [kalker](https://github.com/PaddiM8/kalker) - 一种科学计算器，支持用户定义的变量、函数、求导、积分和复数的数学语法。跨平台+WASM支持[！[Build Status](https://github.com/PaddiM8/kalker/workflows/Release/badge.svg)](https://github.com/PaddiM8/kalker/actions)
* [kytan](https://github.com/changlan/kytan) — 高性能对等VPN
* [linkerd/linkerd2-proxy](https://github.com/linkerd/linkerd2-proxy) — Kubernetes的超轻服务网。
* [MaidSafe](https://github.com/maidsafe) — 一个去中心化的平台。
* [mdBook](https://crates.io/crates/mdbook) — 从markdown文件创建书籍的命令行实用程序[！[Build Status](https://github.com/rust-lang/mdBook/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/mdBook/actions)
* [nicohman/eidolon](https://github.com/nicohman/eidolon) — linux和macosx的steam和drm免费游戏注册和启动程序[！[build badge](https://api.travis-ci.org/nicohman/eidolon.svg?branch=master)](https://travis-ci.org/nicohman/eidolon)
* [notty](https://github.com/withoutboats/notty) — 一种新型终端
* [Pijul](https://pijul.org) — 基于补丁的分布式版本控制系统
* [rx](https://github.com/cloudhead/rx) — Vi灵感现代像素艺术编辑器
* [Servo](https://github.com/servo/servo) — 原型web浏览器引擎
* [shuttle](https://github.com/shuttle-hq/shuttle) — 为Rust构建的无服务器平台
* [SWC](https://github.com/swc-project/swc) — 超快TypeScript/JavaScript编译器
* [tiny](https://github.com/osa1/tiny) — 终端IRC客户端
* [trust-dns](https://crates.io/crates/trust-dns) — DNS服务器[！[生成状态](https://github.com/bluejekyll/trust-dns/workflows/test/badge.svg?branch=main)](https://github.com/bluejekyll/trust-dns/actions?query=workflow%3Atest)
* [wasmer](https://github.com/wasmerio/wasmer) — 一个安全快速的WebAssembly运行时，支持WASI和Emscripten[！[Build Status](https://github.com/wasmerio/wasmer/workflows/build/badge.svg?style=flat-正方形）](https://github.com/wasmerio/wasmer/actions)
* [Weld](https://github.com/serayuzgur/weld) — 完全伪造的REST API生成器[！[build badge](https://api.travis-ci.org/serayuzgur/weld.svg?branch=master)](https://travis-ci.org/serayuzgur/weld)
* [wezterm](https://github.com/wez/wezterm) — GPU加速的跨平台终端模拟器和多路复用器
* [zellij](https://github.com/zellij-org/zellij) — 包含电池的终端多路复用器（工作区）

### Audio and Music

* [enginesound](https://github.com/DasEtwas/enginesound) — 一个GUI和命令行应用程序，用于按程序生成半真实的引擎声音。具有深度配置、可变采样率和频率分析窗口。
* [Glicol](https://github.com/chaosprint/glicol) — 用Rust编写的面向图形的实时编码语言，用于浏览器中的协作音乐。
* [ncspot](https://github.com/hrkfdn/ncspot) - 跨平台ncurses Spotify客户端，灵感来自ncmpc等。[！[构建徽章](https://github.com/hrkfdn/ncspot/workflows/Build/badge.svg)](https://github.com/hrkfdn/ncspot/actions?query=workflow%3ABuild)
* [Polaris](https://github.com/agersant/polaris) — 音乐流应用程序。[！[构建徽章](https://api.travis-ci.org/agersant/polaris.svg?branch=master)](https://travis-ci.org/agersant/polaris)
* [Spotify TUI](https://github.com/Rigellute/spotify-tui) — 用Rust编写的终端Spotify客户端！[持续集成](https://github.com/Rigellute/spotify-tui/workflows/Continuous%20Integration/badge.svg?branch=master)
* [Spotifyd](https://github.com/Spotifyd/spotifyd) — 作为UNIX守护程序运行的开源Spotify客户端！[持续集成](https://github.com/Spotifyd/spotifyd/workflows/Continuous%20Integration/badge.svg?branch=master)

### Cryptocurrencies

* [Akula](https://github.com/akula-bft/akula) - Rust Ethereum执行层（EL）客户端（WIP）
* [Bitcoin Satoshi's Vision](https://github.com/brentongunning/rust-sv) [[sv](https://crates.io/crates/sv)]-用于与比特币SV合作的Rust库。
* [ChainX](https://github.com/chainx-org/ChainX) — Polkadot上的完全去中心化链间加密资产管理。
* [CITA](https://github.com/citahub/cita) — 面向企业用户的高性能区块链内核。
* [coinbase-pro-rs](https://github.com/inv2004/coinbase-pro-rs) — Rust中的Coinbase pro客户端，支持sync/async/websocket[！[build badge](https://api.travis-ci.org/inv2004/coinbase-pro-rs.svg?branch=master)](https://travis-ci.org/inv2004/coinbase-pro-rs)
* [Diem](https://github.com/diem/diem) — 吴廷琰的使命是建立一个简单的全球货币和金融基础设施，为数十亿人赋能。
* [electrumrs](https://github.com/romanz/electrs) — 在Rust中高效地重新实现Electrum Server。
* [ethabi](https://github.com/rust-ethereum/ethabi) - 对智能合约调用进行编码和解码。
* [ethaddrgen](https://github.com/Limeth/ethaddrgen) — Rust[！[build badge]定制以太坊虚荣地址生成器(https://api.travis-ci.org/Limeth/ethaddrgen.svg?branch=master)](https://travis-ci.org/Limeth/ethaddrgen)
* [ethers-rs](https://github.com/gakonst/ethers-rs) - 在Rust中完成以太坊和Celo库和钱包实现！[生成状态](https://github.com/gakonst/ethers-rs/workflows/Tests/badge.svg)
* [etk](https://github.com/quilt/etk) - etk是一组用于编写、读取和分析EVM字节码的工具。
* [Forest](https://github.com/ChainSafe/forest) - Rust Filecoin实现[！[Build Status](https://img.shields.io/circleci/build/gh/ChainSafe/forest/main?branch=master)](https://app.circleci.com/pipelines/github/ChainSafe/forest?branch=main)
* [Foundry](https://github.com/foundry-rs/foundry) - Foundry是一个快速、便携和模块化的工具包，用于以太坊应用程序开发，使用Rust！[生成状态](https://img.shields.io/github/workflow/status/foundry-rs/foundry/test?style=flat-正方形）
* [Grin](https://github.com/mimblewimble/grin/) — MimbleWimble协议的演进
* [hdwallet](https://github.com/jjyr/hdwallet) [[hdwallet](https://crates.io/crates/hdwallet)]-BIP-32 HD钱包相关密钥导出实用程序。
* [Holochain](https://github.com/holochain/holochain) — 可扩展的P2P替代区块链，适用于您一直想要构建的所有分布式应用程序。[！[检测关键检查失败](https://github.com/holochain/holochain/actions/workflows/check_run_detect_release_pr_failure.yml/badge.svg)](https://github.com/holochain/holochain/actions/workflows/check_run_detect_release_pr_failure.yml)
* [ibc-rs](https://github.com/informalsystems/hermes) - [Interblockchain Communication]的Rust实现(https://ibcprotocol.org/)协议
* [infincia/bip39-rs](https://github.com/infincia/bip39-rs) [[bip39](https://crates.io/crates/bip39)]-BIP39的Rust实现。
* [interBTC](https://github.com/interlay/interbtc) — 无信任和完全去中心化的比特币连接波尔卡多和草间弥撒。
* [Joystream](https://github.com/Joystream/joystream) — 用户管理的视频平台[！[Build Status](https://api.travis-ci.org/Joystream/joystream.svg?branch=master)](https://travis-ci.org/Joystream/joystream)
* [Lighthouse](https://github.com/sigp/lighthouse) — Rust Ethereum共识层（CL）客户端[！[构建状态](https://github.com/sigp/lighthouse/workflows/test-suite/badge.svg?branch=master)](https://github.com/sigp/lighthouse/actions)
* [mev-inspect-rs](https://github.com/flashbots/mev-inspect-rs) - Rust中的以太坊MEV检查器
* [near/nearcore](https://github.com/near/nearcore) — 低端移动设备的去中心化智能合约平台。
* [Nervos CKB](https://github.com/nervosnetwork/ckb) — Nervos CKB是一个公共无许可区块链，是Nervos网络的公共知识层。
* [Nimiq](https://github.com/nimiq/core-rs) — Nimiq节点的Rust实现
* [opensea-rs](https://github.com/gakonst/opensea-rs) - Rust绑定和CLI到Opensea API和Contracts。
* [Parity-Bitcoin](https://github.com/paritytech/parity-bitcoin) — Parity比特币客户端[！[build badge](https://api.travis-ci.org/paritytech/parity-bitcoin.svg?branch=master)](https://app.travis-ci.com/github/paritytech/parity-bitcoin)
* [Phala-Network/phala-blockchain](https://github.com/Phala-Network/phala-blockchain) — 基于Intel SGX和Substrate的机密智能合约区块链
* [Polkadot](https://github.com/paritytech/polkadot) — 具有池安全性的异构多链技术
* [revm](https://github.com/bluealloy/revm) - Revolutionary Machine（revm）是一个用rust编写的快速以太坊虚拟机。
* [rust-bitcoin](https://github.com/rust-bitcoin/rust-bitcoin) — 支持反序列化、解析和执行与比特币相关的数据结构和网络消息的库。
* [rust-lightning](https://github.com/lightningdevkit/rust-lightning) [![Crate](https://img.shields.io/crates/v/lightning.svg?logo=rust)](https://crates.io/crates/lightning) — 用Rust编写的比特币闪电库。主机箱“闪电”不处理网络、持久性或任何其他I/O。因此，它与运行时无关，但用户必须实现基本的网络逻辑、链交互和磁盘存储。打开连接板条箱。
* [Solana](https://github.com/solana-labs/solana) — 使用历史证明，速度惊人、高度可扩展的区块链。
* [Substrate](https://github.com/paritytech/substrate) — 用Rust编写的通用模块化区块链模板
* [svm-rs](https://github.com/roynalnaruto/svm-rs) - Solidity编译器版本管理器。
* [tendermint-rs](https://github.com/informalsystems/tendermint-rs) - Tendermint区块链数据结构和客户端的Rust实现
* [wagyu](https://github.com/AleoHQ/wagyu) [[wagyu](https://crates.io/crates/wagyu)]-用于生成加密货币钱包的Rust库[！[build badge](https://api.travis-ci.com/AleoHQ/wagyu.svg?branch=master)](https://api.travis-ci.com/AleoHQ/wagyu.svg?branch=master)
* [zcash](https://github.com/zcash/zcash) — Zcash是“Zerocash”协议的一个实现。

### Database

* [Databend](https://github.com/datafuselabs/databend) - 具有云原生架构的现代实时数据处理和分析DBMS[！[发布](https://github.com/datafuselabs/databend/actions/workflows/databend-release.yml/badge.svg)](https://github.com/datafuselabs/databend/actions/workflows/databend-release.yml)
* [indradb](https://crates.io/crates/indradb) — 基于Rust的图形数据库[！[build badge](https://api.travis-ci.org/indradb/indradb.svg?branch=master)](https://travis-ci.org/indradb/indradb)
* [Lucid](https://github.com/lucid-kv/lucid) — 通过HTTP API访问高性能分布式KV存储。[！[生成状态](https://github.com/lucid-kv/lucid/workflows/Lucid/badge.svg?branch=master)](https://github.com/lucid-kv/lucid/actions?workflow=Lucid)
* [Materialize](https://github.com/MaterializeInc/materialize) - 实时数据流支持的流式SQL数据库：heavy_dollar_sign:[！[Build status](https://badge.buildkite.com/97d6604e015bf633d1c2a12d166bb46f3b43a927d3952c999a.svg?branch=main)](https://buildkite.com/materialize/tests)
* [noria](https://github.com/mit-pdos/noria) [[诺里亚](https://crates.io/crates/noria)]-动态变化的、部分有状态的web应用程序后端数据流[！[build badge](https://api.travis-ci.org/mit-pdos/noria.svg?branch=master)](https://travis-ci.org/mit-pdos/noria)
* [ParityDB](https://github.com/paritytech/parity-db) — 快速可靠的数据库，针对读取操作进行了优化
* [PumpkinDB](https://github.com/PumpkinDB/PumpkinDB) — 事件源数据库引擎
* [Qdrant](https://github.com/qdrant/qdrant) - 具有扩展过滤支持的开源矢量相似性搜索引擎[！[Tests](https://github.com/qdrant/qdrant/workflows/Tests/badge.svg)](https://github.com/qdrant/qdrant/actions)
* [RisingWaveLabs/RisingWave](https://github.com/RisingWaveLabs/risingwave) - 云中的下一代流数据库[！[CI](https://github.com/RisingWaveLabs/risingwave/actions/workflows/main.yml/badge.svg)](https://github.com/RisingWaveLabs/risingwave/actions/workflows/main.yml/badge.svg?branch=main)
* [seppo0010/rsedis](https://github.com/seppo0010/rsedis) — Rust[！[build badge]中的Redis重新实现(https://api.travis-ci.org/seppo0010/rsedis.svg?branch=master)](https://travis-ci.org/seppo0010/rsedis)
* [Skytable](https://github.com/skytable/skytable) — 多模型NoSQL数据库！[GitHub工作流状态](https://img.shields.io/github/workflow/status/skytable/skytable/Tests?style=flat-正方形）
* [sled](https://crates.io/crates/sled) — 一个（beta版）现代嵌入式数据库[！[Build Status](https://github.com/spacejam/sled/workflows/Rust/badge.svg?branch=master)](https://github.com/spacejam/sled/actions?workflow=Rust)
* [SurrealDB](https://github.com/surrealdb/surrealdb) — 可扩展的分布式文档图形数据库[！[Build Status](https://img.shields.io/github/workflow/status/surrealdb/surrealdb/Continuous%20integration/main)](https://github.com/surrealdb/surrealdb/actions)
* [TerminusDB](https://github.com/terminusdb/terminusdb-store) - 开源图形数据库和文档存储[！[Build Status](https://github.com/terminusdb/terminusdb-store/workflows/Build/badge.svg?branch=master)](https://github.com/terminusdb/terminusdb-store/actions)
* [tikv](https://github.com/tikv/tikv) — Rust[！[Build Status]中的分布式KV数据库(https://ci.pingcap.net/job/tikv_ghpr_test/badge/icon)](https://ci.pingcap.net/job/tikv_ghpr_test/)
* [vorot93/libmdbx-rs](https://github.com/vorot93/libmdbx-rs) [[mdbx系统](https://crates.io/crates/mdbx-sys)]-MDBX的Rust绑定，这是一个“快速、紧凑、功能强大、嵌入式、事务性密钥值数据库，具有许可证”。这是mozilla/lmdb-rs的一个分支，带有补丁，可以与libmdbx一起使用。
* [WooriDB](https://github.com/naomijub/wooridb) - 受Crux和Datomic启发的通用时间序列数据库。

### Emulators

See also [crates matching keyword 'emulator'](https://crates.io/keywords/emulator).

* CHIP-8
  * [ColinEberhardt/wasm-rust-chip8](https://github.com/ColinEberhardt/wasm-rust-chip8) — 用Rust编写的WebAssembly CHIP-8仿真器
  * [starrhorne/chip8-rust](https://github.com/starrhorne/chip8-rust) — 又一个rust chip8模拟器
* Commodore 64
  * [kondrak/rust64](https://github.com/kondrak/rust64) — [！[构建徽章](https://api.travis-ci.org/kondrak/rust64.svg?branch=master)](https://travis-ci.org/kondrak/rust64)
* Flash Player
  * [Ruffle](https://github.com/ruffle-rs/ruffle) — Ruffle是一个用Rust编程语言编写的Adobe Flash Player模拟器。Ruffle使用WebAssembly面向桌面和web。[！[Build Status Rust](https://img.shields.io/github/workflow/status/ruffle-rs/ruffle/Test%20Rust?label=Rust%20Build&logo=github)](https://github.com/ruffle-rs/ruffle/actions?workflow=Test%20Rust)[！[生成状态网站](https://img.shields.io/github/workflow/status/ruffle-rs/ruffle/Test%20Web?label=Web%20Build&logo=github)](https://github.com/ruffle-rs/ruffle/actions?workflow=Test%20Web)
* Gameboy
  * [Gekkio/mooneye-gb](https://github.com/Gekkio/mooneye-gb) — [！[构建徽章](https://api.travis-ci.org/Gekkio/mooneye-gb.svg?branch=master)](https://travis-ci.org/Gekkio/mooneye-gb)
  * [mohanson/gameboy](https://github.com/mohanson/gameboy) — 全功能跨平台GameBoy模拟器。永远的男孩！。
  * [mvdnes/rboy](https://github.com/mvdnes/rboy) — [！[构建徽章](https://api.travis-ci.org/mvdnes/rboy.svg?branch=master)](https://travis-ci.org/mvdnes/rboy)
* Gameboy Advance
  * [michelhe/rustboyadvance-ng](https://github.com/michelhe/rustboyadvance-ng) - RustboyAdvance ng是一款具有桌面、android和[WebAssembly]的Gameboy Advance模拟器(https://michelhe.github.io/rustboyadvance-ng/)支持。[！[构建徽章](https://github.com/michelhe/rustboyadvance-ng/workflows/Deploy/badge.svg?branch=master)](https://github.com/michelhe/rustboyadvance-ng/actions?query=workflow%3ADeploy)
* GameMaker
  * [OpenGMK](https://github.com/OpenGMK/OpenGMK) — OpenGMK是对专有GameMakerClassic引擎的现代改写，提供了一个完整的运行程序源代码、一个反编译程序、一个TASing框架和用于自己处理游戏数据的库。
* Intel 8080 CPU
  * [mohanson/i8080](https://github.com/mohanson/i8080) — 基于Rust的Intel 8080 cpu仿真器
* NES
  * [koute/pinky](https://github.com/koute/pinky) — [！[构建徽章](https://api.travis-ci.org/koute/pinky.svg?branch=master)](https://travis-ci.org/koute/pinky)
  * [pcwalton/sprocketnes](https://github.com/pcwalton/sprocketnes)
* ZX Spectrum
  * [rustzx/rustzx](https://github.com/rustzx/rustzx) — [！[RustZX CI](https://github.com/rustzx/rustzx/actions/workflows/ci.yml/badge.svg)](https://github.com/rustzx/rustzx/actions/workflows/ci.yml)

### Games

See also [Games Made With Piston](https://github.com/PistonDevelopers/piston/wiki/Games-Made-With-Piston).

* [citybound](https://github.com/citybound/citybound) — 你应得的城市模拟人
* [cristicbz/rust-doom](https://github.com/cristicbz/rust-doom) — 末日的渲染器，可能会发展成为一款可玩游戏[！[build badge](https://api.travis-ci.org/cristicbz/rust-doom.svg?branch=master)](https://travis-ci.org/cristicbz/rust-doom)
* [doukutsu-rs](https://github.com/doukutsu-rs/doukutsu-rs) — 洞穴故事引擎的Rust重新实现，并进行了一些增强。
* [garkimasera/rusted-ruins](https://github.com/garkimasera/rusted-ruins) — 具有像素艺术的可扩展开放世界流氓游戏[！[构建徽章](https://api.travis-ci.org/garkimasera/rusted-ruins.svg?branch=master)](https://travis-ci.org/garkimasera/rusted-ruins)
* [gorilla-devs/ferium](https://github.com/gorilla-devs/ferium) — Ferium是一个快速且功能丰富的CLI程序，用于从Modrinth、CurseForge和GitHub版本下载和更新Minecraft mod，以及从Modrinch和CurseForke下载和更新modpacks！[费里建造](https://github.com/gorilla-devs/ferium/actions/workflows/build.yml/badge.svg?branch=main)
* [lifthrasiir/angolmois-rust](https://github.com/lifthrasiir/angolmois-rust) — 一款支持BMS格式的极简音乐视频游戏[！[build badge](https://api.travis-ci.org/lifthrasiir/angolmois-rust.svg?branch=master)](https://travis-ci.org/lifthrasiir/angolmois-rust)
* [mara214/rsnake](https://github.com/mara214/rsnake) — 蛇用铁锈书写。
* [ozkriff/zemeroth](https://github.com/ozkriff/zemeroth) — 一款小型2D回合制六边形战略游戏[！[build badge](https://api.travis-ci.org/ozkriff/zemeroth.svg?branch=master)](https://travis-ci.org/ozkriff/zemeroth)
* [rhex](https://github.com/dpc/rhex) — 六边形ascii roguelike
* [rsaarelm/magog](https://github.com/rsaarelm/magog) — Rust中的流氓游戏
* [SoftbearStudios/mk48](https://github.com/SoftbearStudios/mk48) — 《Mk48.io》是一款在线多人海军战斗游戏
* [swatteau/sokoban-rs](https://github.com/swatteau/sokoban-rs) — Sokoban实施
* [thetawavegame/thetawave-legacy](https://github.com/thetawavegame/thetawave-legacy) - 一款太空射击游戏，力求成为新游戏开发者做出首次贡献的切入点！[构建徽章](https://github.com/thetawavegame/thetawave-legacy/actions/workflows/ci.yml/badge.svg?branch=master)
* [Thinkofname/rust-quake](https://github.com/Thinkofname/rust-quake) — Rust中的地震贴图渲染器
* [ttyperacer/terminal-typeracer](https://gitlab.com/ttyperacer/terminal-typeracer) - 为终端编写的单人打字测试游戏
* [Veloren](https://gitlab.com/veloren/veloren) — 一款开放世界、开源的多人体素RPG游戏，目前正在alpha开发中[！[build badge](https://gitlab.com/veloren/veloren/badges/master/pipeline.svg)](https://gitlab.com/veloren/veloren/-/pipelines)
* [Zone of Control](https://github.com/ozkriff/zoc) — 回合制六边形战略游戏[！[构建徽章](https://api.travis-ci.org/ozkriff/zoc.svg?branch=master)](https://travis-ci.org/ozkriff/zoc)

### Graphics

* [ivanceras/svgbob](https://github.com/ivanceras/svgbob) — 将ASCII图表转换为SVG图形[！[build badge](https://api.travis-ci.org/ivanceras/svgbob.svg?branch=master)](https://travis-ci.org/ivanceras/svgbob)
* [Limeth/euclider](https://github.com/Limeth/euclider) — 实时4D CPU光线跟踪器[！[构建徽章](https://api.travis-ci.org/Limeth/euclider.svg?branch=master)](https://travis-ci.org/Limeth/euclider)
* [RazrFalcon/resvg](https://github.com/RazrFalcon/resvg) — SVG渲染库。[！[构建徽章](https://api.travis-ci.org/RazrFalcon/resvg.svg?branch=master)](https://travis-ci.org/RazrFalcon/resvg)
* [turnage/valora](https://crates.io/crates/valora) — 一个生成性美术的图书馆！[锈蚀](https://github.com/turnage/valora/workflows/Rust/badge.svg?branch=master)
* [Twinklebear/tray_rust](https://github.com/Twinklebear/tray_rust) — 光线跟踪器[！[构建徽章](https://api.travis-ci.org/Twinklebear/tray_rust.svg?branch=master)](https://travis-ci.org/Twinklebear/tray_rust)

### Image processing

* [Imager](https://github.com/imager-io/imager) — 自动图像优化。
* [shssoichiro/oxipng](https://github.com/shssoichiro/oxipng) [[xipng](https://crates.io/crates/oxipng)]-用Rust编写的多线程PNG优化器。[！[生成状态](https://github.com/shssoichiro/oxipng/workflows/oxipng/badge.svg)](https://github.com/shssoichiro/oxipng/actions?query=branch%3Amaster)[！[版本](https://img.shields.io/crates/v/oxipng.svg)](https://crates.io/crates/oxipng)

### Industrial automation

* [locka99/opcua](https://github.com/locka99/opcua) — 纯锈[OPC UA](https://opcfoundation.org/about/opc-technologies/opc-ua/)图书馆。
* [slowtec/tokio-modbus](https://github.com/slowtec/tokio-modbus) — A[东京](https://tokio.rs)-基于[modbus](https://modbus.org)图书馆。[！[生成状态](https://api.travis-ci.org/slowtec/tokio-modbus.svg?branch=master)](https://travis-ci.org/slowtec/tokio-modbus)

### Observability

* [avito-tech/bioyino](https://github.com/avito-tech/bioyino) — 高性能可扩展StatsD兼容服务器。
* [OpenTelemetry](https://crates.io/crates/opentelemetry) — OpenTelemetry提供了一组API、库、代理和收集器服务，用于从应用程序中捕获分布式跟踪和度量。您可以使用普罗米修斯、杰格和其他可观察性工具来分析它们。[！[GitHub操作CI](https://github.com/open-telemetry/opentelemetry-rust/workflows/CI/badge.svg?branch=master)](https://github.com/open-telemetry/opentelemetry-rust/actions?query=workflow%3ACI+分支%3主控）
* [Quickwit-oss/quickwit](https://github.com/quickwit-oss/quickwit) - 用于日志管理的云原生和高性价比搜索引擎。[！[CI](https://github.com/quickwit-oss/quickwit/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/quickwit-oss/quickwit/actions?query=workflow%3ACI)
* [Scaphandre](https://github.com/hubblo-org/scaphandre) - 功耗监控代理，用于跟踪主机和每个服务的功耗，并使设计系统和应用程序更具可持续性。设计适合任何监控工具链（已经支持prometheus、warp10、riemann…）。
* [vectordotdev/vector](https://github.com/vectordotdev/vector) — 高性能、日志、度量和事件路由器。

### Operating systems

See also [A comparison of operating systems written in Rust](https://github.com/flosse/rust-os-comparison).
* [0x59616e/SteinsOS](https://github.com/0x59616e/SteinsOS)  -armv8-a架构的操作系统。
* [redox-os/redox](https://gitlab.redox-os.org/redox-os/redox) — [！[构建徽章](https://api.travis-ci.org/redox-os/redox.svg?branch=master)](https://travis-ci.org/redox-os/redox)
* [thepowersgang/rust_os](https://github.com/thepowersgang/rust_os) — [！[构建徽章](https://api.travis-ci.org/thepowersgang/rust_os.svg?branch=master)](https://travis-ci.org/thepowersgang/rust_os)
* [theseus-os/Theseus](https://github.com/theseus-os/Theseus) — 一种安全的语言，单地址空间和单特权级别的操作系统，用纯Rust-[！[build badge]从头编写(https://img.shields.io/github/workflow/status/theseus-os/Theseus/Documentation?label=docs%20build)](https://www.theseus-os.com/Theseus/book/index.html)
* [tock/tock](https://github.com/tock/tock) — 基于Cortex-M的微控制器的安全嵌入式操作系统

### Productivity

* [Bartib](https://github.com/nikolassv/bartib) [[Bartib](https://crates.io/crates/bartib)]-命令行的简单时间跟踪器[！[Tests](https://github.com/nikolassv/bartib/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/nikolassv/bartib/actions/workflows/test.yml)
* [espanso](https://github.com/espanso/espanso) — 用Rust[！[CI]编写的跨平台文本扩展程序(https://github.com/espanso/espanso/actions/workflows/ci.yml/badge.svg?branch=dev&event=push)](https://github.com/espanso/espanso/actions/workflows/ci.yml)
* [eureka](https://crates.io/crates/eureka) — 一个CLI工具，无需离开终端即可输入和存储您的想法
* [pier-cli/pier](https://github.com/pier-cli/pier) — 一个中央存储库，用于管理（添加、搜索元数据等）您的所有单行程序、脚本、工具和CLI

### Security tools

* [AFLplusplus/LibAFL](https://github.com/AFLplusplus/LibAFL) - 高级模糊库-将您的模糊器一起放入Rust！跨核心和机器扩展。适用于Windows、Android、MacOS、Linux、no_std等[！[build and test](https://github.com/AFLplusplus/LibAFL/actions/workflows/build_and_test.yml/badge.svg)](https://github.com/AFLplusplus/LibAFL/actions/workflows/build_and_test.yml)
* [arvancloud/libinjection-rs](https://github.com/arvancloud/libinjection-rs) — [libinjection]的Rust绑定(https://github.com/client9/libinjection)[！[构建徽章](https://api.travis-ci.org/arvancloud/libinjection-rs.svg?branch=master)](https://travis-ci.org/arvancloud/libinjection-rs)
* [Cherrybomb](https://github.com/blst-security/cherrybomb) - 使用CLI工具停止半途而废的API规范，该工具通过验证API规范帮助您避免未定义的用户行为。
* [epi052/feroxbuster](https://github.com/epi052/feroxbuster) - 用Rust编写的简单、快速、递归的内容发现工具(
* [Inspektor](https://github.com/inspektor-dev/inspektor) - 用于实施访问策略的数据库协议感知代理👮
* [kpcyrd/authoscope](https://github.com/kpcyrd/authoscope) — 可编写脚本的网络身份验证破解程序[！[build badge](https://api.travis-ci.org/kpcyrd/authoscope.svg?branch=master)](https://travis-ci.org/kpcyrd/authoscope)
* [kpcyrd/rshijack](https://github.com/kpcyrd/rshijack) — TCP连接劫持者，shijack[！[build badge]的rust重写(https://api.travis-ci.org/kpcyrd/rshijack.svg?branch=master)](https://travis-ci.org/kpcyrd/rshijack)
* [kpcyrd/sn0int](https://github.com/kpcyrd/sn0int) — 半自动OSINT框架和包管理器[！[build badge](https://api.travis-ci.org/kpcyrd/sn0int.svg?branch=master)](https://travis-ci.org/kpcyrd/sn0int)
* [kpcyrd/sniffglue](https://github.com/kpcyrd/sniffglue) — 一个安全的多线程数据包嗅探器[！[build badge](https://api.travis-ci.org/kpcyrd/sniffglue.svg?branch=master)](https://travis-ci.org/kpcyrd/sniffglue)
* [ObserverWard](https://github.com/0x727/ObserverWard) — 基于社区的网络技术分析工具。
* [phra/rustbuster](https://github.com/phra/rustbuster) — 全面的Web模糊器和内容发现工具
* [ripasso](https://github.com/cortex/ripasso/) — 密码管理器，文件系统与pass兼容
* [rustscan/rustscan](https://github.com/RustScan/RustScan) — 使用此端口扫描工具使Nmap更快[！[build badge](https://github.com/RustScan/RustScan/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/RustScan/RustScan/actions?query=workflow%3A%22Continuous+集成%22）

### Simulation

* [hEngine](https://github.com/hashintel/hash/tree/main/packages/engine) - Rust实现的计算模拟引擎，支持大规模基于代理的建模，模拟逻辑用JavaScript和Python编写。

### System tools

* [ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide/) — 学习习惯的“cd”的快速替代品[！[release](https://github.com/ajeetdsouza/zoxide/workflows/.github/workflows/release.yml/badge.svg)](https://github.com/ajeetdsouza/zoxide/actions)
* [Alonely0/Voila](https://github.com/Alonely0/Voila) — Voila是一种通过CLI工具推出的特定于域的语言，用于以快速可靠的方式对大量文件和目录进行操作。[！[Linux构建](https://github.com/Alonely0/Voila/actions/workflows/linux-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/linux-ci.yml)[！[macOS构建](https://github.com/Alonely0/Voila/actions/workflows/mac-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/mac-ci.yml)[！[Windows内部版本](https://github.com/Alonely0/Voila/actions/workflows/windows-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/windows-ci.yml)
* [bandwhich](https://github.com/imsnif/bandwhich) — 终端带宽利用工具[！[build badge](https://api.travis-ci.com/imsnif/bandwhich.svg?branch=master)](https://app.travis-ci.com/github/imsnif/bandwhich)
* [bottom](https://github.com/ClementTsang/bottom) - 另一个跨平台的图形过程/系统监视器。[！[GitHub工作流状态（分支）](https://img.shields.io/github/workflow/status/ClementTsang/bottom/ci/master)](https://github.com/ClementTsang/bottom/actions?query=branch%3Amaster)
* [brocode/fblog](https://github.com/brocode/fblog) — 小型命令行JSON日志查看器[！[build badge](https://api.travis-ci.org/brocode/fblog.svg?branch=master)](https://travis-ci.org/brocode/fblog)
* [bustd](https://github.com/vrmiguel/bustd) - 轻量级进程杀手守护程序，用于处理Linux上的内存不足情况。[！[GitHub工作流状态（分支）](https://img.shields.io/github/workflow/status/vrmiguel/bustd/build-and-test)](https://github.com/vrmiguel/bustd/actions?query=branch%3Amaster)
* [buster/rrun](https://github.com/buster/rrun) — Linux的命令启动器，类似于gmrun[！[build badge](https://api.travis-ci.org/buster/rrun.svg?branch=master)](https://travis-ci.org/buster/rrun)
* [cantino/mcfly](https://github.com/cantino/mcfly) - 浏览你的贝壳历史。伟大的斯科特！[！[构建徽章](https://api.travis-ci.org/cantino/mcfly.svg?branch=master)](https://travis-ci.org/cantino/mcfly)
* [crabz](https://github.com/sstadick/crabz) - 多线程压缩和解压缩CLI工具[！[Build Status](https://github.com/sstadick/crabz/workflows/Check/badge.svg)](https://github.com/sstadick/crabz/actions?query=workflow%3ACheck)
* [cristianoliveira/funzzy](https://github.com/cristianoliveira/funzzy) — 受[entr]启发的可配置文件系统观察器(http://eradman.com/entrproject/)[！[构建徽章](https://api.travis-ci.org/cristianoliveira/funzzy.svg?branch=master)](https://travis-ci.org/cristianoliveira/funzzy)
* [dalance/procs](https://github.com/dalance/procs) — Rust[！[Regression]编写的“ps”的现代替换(https://github.com/dalance/procs/actions/workflows/regression.yml/badge.svg)](https://github.com/dalance/procs/actions/workflows/regression.yml)
* [ddh](https://github.com/darakian/ddh) — 快速重复文件查找器[！[build badge](https://api.travis-ci.org/darakian/ddh.svg?branch=master)](https://travis-ci.org/darakian/ddh)
* [diskonaut](https://github.com/imsnif/diskonaut) — 终端视盘空间导航器[！[build badge](https://api.travis-ci.com/imsnif/diskonaut.svg?branch=main)](https://app.travis-ci.com/github/imsnif/diskonaut)
* [dust](https://github.com/bootandy/dust) — 更直观的du版本
* [fselect](https://crates.io/crates/fselect) — 使用类似SQL的查询查找文件[！[build badge](https://api.travis-ci.org/jhspetersson/fselect.svg?branch=master)](https://travis-ci.org/jhspetersson/fselect)
* [gitui](https://github.com/extrawurst/gitui) - 用Rust编写的git快速终端客户端。[！[构建](https://github.com/extrawurst/gitui/workflows/CI/badge.svg?branch=master)](https://github.com/extrawurst/gitui/actions)
* [Kondo](https://github.com/tbillington/kondo) - 用于删除软件项目工件和回收磁盘空间的CLI和GUI工具
* [lotabout/rargs](https://github.com/lotabout/rargs) [[rargs](https://crates.io/crates/rargs)]-xargs+awk，支持模式匹配[！[build badge](https://api.travis-ci.org/lotabout/rargs.svg?branch=master)](https://travis-ci.org/lotabout/rargs)
* [lotabout/skim](https://github.com/lotabout/skim) — 纯铁锈色的模糊探测器[！[构建徽章](https://api.travis-ci.org/lotabout/skim.svg?branch=master)](https://travis-ci.org/lotabout/skim)
* [Luminarys/synapse](https://github.com/Luminarys/synapse) — 灵活快速的BitTorrent守护程序。[！[生成状态](https://api.travis-ci.org/Luminarys/synapse.svg?branch=master)](https://travis-ci.org/Luminarys/synapse)
* [m4b/bingrep](https://github.com/m4b/bingrep) — 通过各种操作系统和体系结构的二进制文件，并对其进行着色。[！[构建徽章](https://api.travis-ci.org/m4b/bingrep.svg?branch=master)](https://travis-ci.org/m4b/bingrep)
* [mitnk/cicada](https://github.com/mitnk/cicada) — 像bash一样的Unix shell[！[build badge](https://api.travis-ci.org/mitnk/cicada.svg?branch=master)](https://travis-ci.org/mitnk/cicada)
* [mmstick/concurr](https://github.com/mmstick/concurr) — GNU并行的替代方案，带有客户端-服务器架构
* [mmstick/fontfinder](https://github.com/mmstick/fontfinder) — 用于预览和安装谷歌字体的GTK3应用程序
* [mmstick/tv-renamer](https://github.com/mmstick/tv-renamer) — 带有可选GTK3前端的电视剧重命名应用程序。[！[构建徽章](https://api.travis-ci.org/mmstick/tv-renamer.svg?branch=master)](https://travis-ci.org/mmstick/tv-renamer)
* [mxseev/logram](https://github.com/mxseev/logram) — 将日志文件的更新推送到Telegram
* [nickgerace/gfold](https://github.com/nickgerace/gfold) [[折叠](https://crates.io/crates/gfold)]-帮助跟踪多个Git存储库的CLI工具[！[build](https://img.shields.io/github/workflow/status/nickgerace/gfold/merge/main)](https://github.com/nickgerace/gfold/actions?query=workflow%3Amerge+分支%3main）
* [nivekuil/rip](https://github.com/nivekuil/rip) - “rm”[！[build badge]的安全且符合人体工程学的替代品(https://api.travis-ci.org/nivekuil/rip.svg?branch=master)](https://travis-ci.org/nivekuil/rip)
* [ogham/exa](https://github.com/ogham/exa) — “ls”的替换[！[build badge](https://api.travis-ci.org/ogham/exa.svg?branch=master)](https://travis-ci.org/ogham/exa)
* [orhun/kmon](https://github.com/orhun/kmon) — Linux内核管理器和活动监视器！[https://github.com/orhun/kmon/actions](https://img.shields.io/github/workflow/status/orhun/kmon/Continuous%20Integration/master?label=build)
* [orhun/systeroid](https://github.com/orhun/systeroid) — 具有终端用户界面的sysctl（8）的更强大的替代方案！[https://github.com/orhun/systeroid/actions](https://img.shields.io/github/workflow/status/orhun/systeroid/Continuous%20Integration/main?label=build)
* [ouch](https://github.com/ouch-org/ouch) - 命令行上的无痛压缩和解压缩[！[GitHub工作流状态（分支）](https://img.shields.io/github/workflow/status/ouch-org/ouch/build-and-test)](https://github.com/ouch-org/ouch/actions?query=branch%3Amaster)
* [Peltoche/lsd](https://github.com/Peltoche/lsd) — 一个ls，有很多漂亮的颜色和很棒的图标[！[build](https://github.com/Peltoche/lsd/workflows/CICD/badge.svg?branch=master)](https://github.com/Peltoche/lsd/actions)
* [pop-os/popsicle](https://github.com/pop-os/popsicle) — GTK3和CLI实用程序，用于并行闪存多个USB设备
* [pop-os/system76-power](https://github.com/pop-os/system76-power/) — 带有CLI工具的Linux电源管理守护程序（DBus接口）。
* [pueue](https://github.com/nukesor/pueue) — 管理长期运行的shell命令。[！[GitHub操作工作流](https://github.com/nukesor/pueue/workflows/Test%20build/badge.svg?branch=master)](https://github.com/nukesor/pueue/actions)
* [redox-os/ion](https://github.com/redox-os/ion) — 下一代系统外壳[！[build badge](https://api.travis-ci.org/redox-os/ion.svg?branch=master)](https://travis-ci.org/redox-os/ion)
* [sharkdp/bat](https://github.com/sharkdp/bat) — 有翅膀的克隆猫。[！[CICD](https://github.com/sharkdp/bat/actions/workflows/CICD.yml/badge.svg?branch=master)](https://github.com/sharkdp/bat/actions/workflows/CICD.yml)
* [sharkdp/fd](https://github.com/sharkdp/fd) — 一个简单、快速、用户友好的替代方案。[！[CICD](https://github.com/sharkdp/fd/actions/workflows/CICD.yml/badge.svg)](https://github.com/sharkdp/fd/actions/workflows/CICD.yml)
* [sitkevij/hex](https://github.com/sitkevij/hex) — 一个彩色的hexdump终端实用程序。[！[构建徽章](https://api.travis-ci.org/sitkevij/hex.svg?branch=master)](https://travis-ci.org/sitkevij/hex)
* [trippy](https://github.com/fujiapple852/trippy) - 网络诊断工具[！[build badge](https://github.com/fujiapple852/trippy/workflows/CI/badge.svg)](https://github.com/fujiapple852/trippy/actions/workflows/ci.yml)
* [uutils/coreutils](https://github.com/uutils/coreutils) — GNU coreutils的跨平台Rust重写[[！[CID](https://github.com/uutils/coreutils/actions/workflows/CICD.yml/badge.svg)](https://github.com/uutils/coreutils/actions/workflows/CICD.yml)
* [watchexec](https://github.com/watchexec/watchexec) — 响应文件修改执行命令[！[build badge](https://api.travis-ci.org/watchexec/watchexec.svg?branch=master)](https://travis-ci.org/watchexec/watchexec)
* [XAMPPRocky/tokei](https://github.com/XAMPPRocky/tokei) — 计算代码行数[！[build badge](https://api.travis-ci.org/XAMPPRocky/tokei.svg?branch=master)](https://travis-ci.org/XAMPPRocky/tokei)

### Task scheduling

* [delicate](https://github.com/BinChengZhao/delicate) — 用rust编写的轻量级分布式任务调度平台。[！[生成状态](https://github.com/BinChengZhao/delicate/workflows/CI/badge.svg)](https://github.com/BinChengZhao/delicate/actions)

### Text editors

* [amp](https://amp.rs) — 灵感来自Vi/Vim。[！[构建徽章](https://api.travis-ci.org/jmacdonald/amp.svg?branch=master)](https://travis-ci.org/jmacdonald/amp)
* [gchp/iota](https://github.com/gchp/iota) — 一个简单的文本编辑器[！[build badge](https://api.travis-ci.org/gchp/iota.svg?branch=master)](https://travis-ci.org/gchp/iota)
* [helix](https://github.com/helix-editor/helix) — 受Neovim/Kakoune启发的后现代模态文本编辑器。[！[构建徽章](https://github.com/helix-editor/helix/actions/workflows/build.yml/badge.svg)](https://github.com/helix-editor/helix/actions)
* [ilai-deutel/kibi](https://github.com/ilai-deutel/kibi) — 一个小小的(≤1024 LOC）文本编辑器，具有语法突出显示、增量搜索等功能。[！[构建徽章](https://github.com/ilai-deutel/kibi/workflows/CI/badge.svg?branch=master)](https://github.com/ilai-deutel/kibi/actions?query=branch%3Amaster)
* [lapce](https://github.com/lapce/lapce) — 用Rust编写的快速强大的代码编辑器。[！[构建徽章](https://github.com/lapce/lapce/actions/workflows/release.yml/badge.svg)](https://github.com/lapce/lapce/actions/workflows/release.yml)
* [mathall/rim](https://github.com/mathall/rim) — 用Rust编写的类似Vim的文本编辑器
* [ox](https://github.com/curlpipe/ox) — 一个独立的Rust文本编辑器，在您的终端中运行！
* [Remacs](https://github.com/remacs/remacs) — 社区驱动的Emacs到Rust的端口。[！[构建徽章](https://api.travis-ci.org/remacs/remacs.svg?branch=master)](https://travis-ci.org/remacs/remacs)
* [vamolessa/pepper](https://github.com/vamolessa/pepper) [[胡椒](https://crates.io/crates/pepper)]-一个固执己见的模式编辑器，用于简化终端的代码编辑[！[build badge](https://github.com/vamolessa/pepper/workflows/rust/badge.svg?branch=master)](https://github.com/vamolessa/pepper)
* [xi-editor](https://github.com/xi-editor/xi-editor) — 一个现代编辑器，后端用Rust编写。

### Text processing

* [dominikwilkowski/cfonts](https://github.com/dominikwilkowski/cfonts) [[字体](https://crates.io/crates/cfonts)]-控制台的性感ANSI字体！[构建徽章](https://github.com/dominikwilkowski/cfonts/actions/workflows/testing.yml/badge.svg)
* [grex](https://github.com/pemistahl/grex) — 用于从用户提供的测试用例生成正则表达式的命令行工具和库[！[build badge](https://api.travis-ci.org/pemistahl/grex.svg?branch=master)](https://travis-ci.org/pemistahl/grex)
* [Lisprez/so_stupid_search](https://github.com/Lisprez/so_stupid_search) — 一个简单快速的人类字符串搜索工具
* [Melody](https://github.com/yoav-lavi/melody) - 一种编译为正则表达式的语言，旨在更易于阅读和维护[！[build badge](https://github.com/yoav-lavi/melody/actions/workflows/rust.yml/badge.svg)](https://github.com/yoav-lavi/melody/actions/workflows/rust.yml)[！[板条箱.io](https://img.shields.io/crates/v/melody_compiler?label=compiler)](https://crates.io/crates/melody_compiler)
* [phiresky/ripgrep-all](https://github.com/phiresky/ripgrep-all) — ripgrep，还可以在PDF、电子书、Office文档、zip、tar中搜索。gz等[！[构建状态](https://api.travis-ci.org/phiresky/ripgrep-all.svg?branch=master)](https://travis-ci.org/phiresky/ripgrep-all)
* [replicadse/complate](https://github.com/replicadse/complate) — 一种终端内文本模板工具，用于标准化消息（如GIT提交）。[！[板条箱.io](https://img.shields.io/crates/v/complate.svg)](https://crates.io/crates/complate)[！[板条箱.io](https://img.shields.io/crates/d/complate?label=crates.io%20downloads)](https://crates.io/crates/complate)[！[构建徽章](https://github.com/replicadse/complate/workflows/pipeline/badge.svg?branch=master)](https://github.com/replicadse/complate/actions)
* [ripgrep](https://crates.io/crates/ripgrep) — 将银色搜索器的可用性与grep[！[build badge]的原始速度相结合(https://api.travis-ci.org/BurntSushi/ripgrep.svg?branch=master)](https://travis-ci.org/BurntSushi/ripgrep)
* [ruplacer](https://github.com/your-tools/ruplacer) — 查找并替换源文件中的文本[！[运行测试](https://github.com/your-tools/ruplacer/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/your-tools/ruplacer/actions/workflows/test.yml)
* [sd](https://crates.io/crates/sd) — 直观的查找和替换CLI
* [sstadick/hck](https://github.com/sstadick/hck) - “cut”[！[build badge]的更快、更具特色的替换(https://github.com/sstadick/hck/workflows/Check/badge.svg?branch=master)](https://github.com/sstadick/hck)
* [vishaltelangre/ff](https://github.com/vishaltelangre/ff) — 按名称查找文件（ff）！[！[构建徽章](https://api.travis-ci.org/vishaltelangre/ff.svg?branch=master)](https://travis-ci.org/vishaltelangre/ff)
* [whitfin/bytelines](https://github.com/whitfin/bytelines) [[字节线](https://crates.io/crates/bytelines)]-将输入行读取为字节片，以提高效率。
* [whitfin/runiq](https://github.com/whitfin/runiq) — 从未排序的输入中筛选重复行的有效方法。
* [xsv](https://crates.io/crates/xsv) — 一个快速的CSV命令行工具（切片、索引、选择、搜索、采样等）[！[build badge](https://api.travis-ci.org/BurntSushi/xsv.svg?branch=master)](https://travis-ci.org/BurntSushi/xsv)

### Utilities

* [1History](https://github.com/1History/1History) — 将Firefox/Chrome/Safari历史记录备份到一个SQLite文件的命令行界面[！[Build Status](https://github.com/1History/1History/actions/workflows/CI.yml/badge.svg)](https://github.com/1History/1History/actions/workflows/CI.yml)
* [brycx/checkpwn](https://github.com/brycx/checkpwn) — 一个Have I Been Pwned（HIBP）命令行实用工具，可以让您轻松检查泄露的帐户和密码。
* [evansmurithi/cloak](https://github.com/evansmurithi/cloak) — 命令行OTP（一次性密码）验证器应用程序。
![CI](https://github.com/evansmurithi/cloak/workflows/CI/badge.svg) [![build badge](https://ci.appveyor.com/api/projects/status/9mlfpfru3ng4c689/branch/master?svg=true)](https://ci.appveyor.com/project/evansmurithi/cloak)
* [fcsonline/tmux-thumbs](https://github.com/fcsonline/tmux-thumbs) — 用Rust编写的tmux手指的闪电般快速版本，像vimium/vimperator一样复制/粘贴tmux。
* [guoxbin/dtool](https://github.com/guoxbin/dtool) — 一个有用的命令行工具集合，用于帮助开发，包括转换、编解码器、哈希、加密等。[！[Build Status](https://api.travis-ci.org/guoxbin/dtool.svg?branch=master)](https://travis-ci.org/guoxbin/dtool)
* [mprocs](https://github.com/pvolok/mprocs) — 用于运行多个进程的TUI
* [nomino](https://github.com/yaa110/nomino) — 开发人员的批重命名实用程序[！[Build Status](https://api.travis-ci.org/yaa110/nomino.svg?branch=master)](https://travis-ci.org/yaa110/nomino)
* [raftario/licensor](https://github.com/raftario/licensor) — 将许可证写入stdout[！[GitHub操作](https://github.com/raftario/licensor/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/raftario/licensor/actions/workflows/build.yml)
* [rustdesk/rustdesk](https://github.com/rustdesk/rustdesk) — 远程桌面软件，TeamViewer和AnyDesk的绝佳替代品。
* [tversteeg/emplace](https://github.com/tversteeg/emplace) — 同步多台计算机上安装的软件包
* [vamolessa/verco](https://github.com/vamolessa/verco) [[维科](https://crates.io/crates/verco)]-一个简单的Git/Hg tui客户端，专注于键盘快捷键
* [vaultwarden](https://github.com/dani-garcia/vaultwarden#readme) [![Build](https://github.com/dani-garcia/vaultwarden/actions/workflows/build.yml/badge.svg)](https://github.com/dani-garcia/vaultwarden/actions/workflows/build.yml) — 用Rust编写的Bitwarden服务器API的替代实现
* [yaa110/cb](https://github.com/yaa110/cb) — 管理剪贴板的命令行界面[！[Build Status](https://api.travis-ci.org/yaa110/cb.svg?branch=master)](https://travis-ci.org/yaa110/cb)

### Video

* [dertuxmalwieder/yaydl](https://github.com/dertuxmalwieder/yaydl) [[耶德尔](https://crates.io/crates/yaydl)]-一个简单的视频下载器
* [harlanc/xiu](https://github.com/harlanc/xiu) — 一个功能强大、安全的纯Trust实时服务器（rtmp/httpflv/hls/relay）。[！[生成状态](https://api.travis-ci.com/harlanc/xiu.svg?branch=master)](https://app.travis-ci.com/github/harlanc/xiu)[！[板条箱.io](https://img.shields.io/crates/v/xiu.svg)](https://crates.io/crates/xiu)
* [xiph/rav1e](https://github.com/xiph/rav1e) — 最快、最安全的AV1编码器。[！[构建徽章](https://api.travis-ci.org/xiph/rav1e.svg?branch=master)](https://travis-ci.org/xiph/rav1e)

### Virtualization

* [containers/youki](https://github.com/containers/youki) — Rust[！[build badge]中的容器运行时(https://github.com/containers/youki/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/containers/youki/actions)
* [firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker) — 用于容器工作负载的轻量级虚拟机[Firecracker Microvm](https://firecracker-microvm.github.io/)
* [tailhook/vagga](https://github.com/tailhook/vagga) — 没有守护程序的容器化工具[！[build badge](https://api.travis-ci.org/tailhook/vagga.svg?branch=master)](https://travis-ci.org/tailhook/vagga)

### Web

* [cfal/tobaru](https://github.com/cfal/tobaru) - 具有allowlists、IP和TLS SNI/ALPN规则路由、iptables支持、循环转发（负载平衡）和热重新加载的端口转发器。
* [LemmyNet/lemmy](https://github.com/LemmyNet/lemmy) — fediversity[！[Build Status]的链接聚合器/reddit克隆(https://cloud.drone.io/api/badges/LemmyNet/lemmy/status.svg)](https://cloud.drone.io/LemmyNet/lemmy)
* [MASQ-Project/Node](https://github.com/MASQ-Project/Node) — MASQ Node软件为全球用户提供了一个分散的节点网格网络，以访问正常的互联网内容-Tor&VPN之外的下一代技术发展[！[build badge](https://github.com/MASQ-Project/Node/actions/workflows/ci-matrix.yml/badge.svg)](https://github.com/MASQ-Project/Node/actions)
* [Plume-org/Plume](https://github.com/Plume-org/Plume) — ActivityPub联合博客应用程序[！[build badge](https://api.travis-ci.org/Plume-org/Plume.svg?branch=master)](https://travis-ci.org/Plume-org/Plume)
* [Revolt/backend](https://github.com/revoltchat/backend) - 使用现代网络技术构建的用户第一聊天平台。
* [spikecodes/libreddit](https://github.com/spikecodes/libreddit) - Reddit的另一个私有前端

### Web Servers

* [mufeedvh/binserve](https://github.com/mufeedvh/binserve) — 一个速度极快的静态web服务器，在一个二进制文件中具有路由、模板和安全性，您可以用零代码[！[build badge](https://github.com/mufeedvh/binserve/workflows/CICD/badge.svg?branch=master)](https://github.com/mufeedvh/binserve/actions)
* [orhun/rustypaste](https://github.com/orhun/rustypaste) — 最小的文件上传/粘贴服务！[https://github.com/orhun/rustypaste/actions](https://img.shields.io/github/workflow/status/orhun/rustypaste/Continuous%20Integration/master?label=build)
* [ronanyeah/rust-hasura](https://github.com/ronanyeah/rust-hasura) — 演示如何使用[Hasura]将RustGraphQL服务器用作远程模式(https://hasura.io/) ![锈蚀](https://github.com/ronanyeah/rust-hasura/workflows/Rust/badge.svg?branch=master)
* [static-web-server](https://github.com/static-web-server/static-web-server) — 一个用于静态文件服务的快速异步web服务器。⚡ [！[CI](https://github.com/static-web-server/static-web-server/actions/workflows/devel.yml/badge.svg)](https://github.com/static-web-server/static-web-server/actions/workflows/devel.yml?query=branch%3Amaster)
* [svenstaro/miniserve](https://github.com/svenstaro/miniserve) — 一个小型的、独立的跨平台CLI工具，允许您通过HTTP[！[build badge]获取二进制文件并提供一些文件(https://github.com/svenstaro/miniserve/workflows/CI/badge.svg?branch=master)](https://github.com/svenstaro/miniserve/actions)
* [thecoshman/http](https://github.com/thecoshman/http) — Host This Things Please-一个基本的http服务器，用于快速简单地托管文件夹[！[build badge](https://api.travis-ci.org/thecoshman/http.svg?branch=master)](https://travis-ci.org/thecoshman/http)
* [TheWaWaR/simple-http-server](https://github.com/TheWaWaR/simple-http-server) — 简单静态http服务器
* [wyhaya/see](https://github.com/wyhaya/see) — 静态HTTP文件服务器[！[生成状态](https://api.travis-ci.org/wyhaya/see.svg?branch=master)](https://travis-ci.org/wyhaya/see)

## Development tools

* [bacon](https://github.com/Canop/bacon) — 后台锈码检查器，类似于货物表
* [clippy](https://crates.io/crates/clippy) — 锈迹斑斑[！[构建徽章](https://api.travis-ci.com/rust-lang/rust-clippy.svg?branch=master)](https://travis-ci.org/rust-lang/rust-clippy)
* [clog-tool/clog-cli](https://github.com/clog-tool/clog-cli) — 从git元数据生成changelog（[常规changelog](https://blog.thoughtram.io/announcements/tools/2014/09/18/announcing-clog-a-conventional-changelog-generator-for-the-rest-of-us.html))[！[构建徽章](https://api.travis-ci.org/clog-tool/clog-cli.svg?branch=master)](https://travis-ci.org/clog-tool/clog-cli)
* [comtrya](https://github.com/comtrya/comtrya) — localhost/dotfiles的配置管理工具[！[build badge](https://github.com/comtrya/comtrya/actions/workflows/main.yaml/badge.svg)](https://github.com/comtrya/comtrya/actions)
* [create-rust-app](https://github.com/Wulf/create-rust-app) — 通过运行一个命令来设置一个现代的rust+react web应用程序。[！[板条箱](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/create-rust-app)
* [dan-t/rusty-tags](https://github.com/dan-t/rusty-tags) — 为货运项目及其所有依赖项创建ctag/etag[！[build badge](https://api.travis-ci.org/dan-t/rusty-tags.svg?branch=master)](https://travis-ci.org/dan-t/rusty-tags)
* [datanymizer/datanymizer](https://github.com/datanymizer/datanymizer) - 强大的数据库匿名器，具有灵活的规则[！[build badge](https://github.com/datanymizer/datanymizer/workflows/CI/badge.svg?branch=main)](https://github.com/datanymizer/datanymizer/actions?query=workflow%3ACI+分支%3main）
* [delta](https://crates.io/crates/git-delta) — git和diff输出的语法突出显示[！[build badge](https://github.com/dandavison/delta/workflows/Continuous%20Integration/badge.svg)](https://github.com/dandavison/delta//actions)
* [dotenv-linter](https://github.com/dotenv-linter/dotenv-linter) — 过梁为`。env`files[！[build badge](https://github.com/dotenv-linter/dotenv-linter/workflows/CI/badge.svg?branch=master)](https://github.com/dotenv-linter/dotenv-linter/actions?query=workflow%3ACI+分支%3主控）
* [fw](https://github.com/brocode/fw) — 工作区生产力助推器[！[Rust](https://github.com/brocode/fw/actions/workflows/rust.yml/badge.svg)](https://github.com/brocode/fw/actions/workflows/rust.yml)
* [geiger](https://github.com/rust-secure-code/cargo-geiger) — 一个列出与Rust板条箱中不安全Rust代码的使用及其所有依赖项相关的统计信息的程序[！[Build Status](https://dev.azure.com/cargo-geiger/cargo-geiger/_apis/build/status/rust-secure-code.cargo-geiger?branchName=master)](https://dev.azure.com/cargo-geiger/cargo-geiger/_build/latest?definitionId=1&branchName=master)
* [git-cliff](https://github.com/orhun/git-cliff) — 一个高度可定制的变更日志生成器，遵循常规提交规范！[https://github.com/orhun/git-cliff/actions](https://img.shields.io/github/workflow/status/orhun/git-cliff/Continuous%20Integration/main?label=build)
* [git-journal](https://github.com/saschagrunert/git-journal/) — Git提交消息和变更日志生成框架[！[build badge](https://api.travis-ci.org/saschagrunert/git-journal.svg?branch=master)](https://travis-ci.org/saschagrunert/git-journal)
* [hot-lib-reloader](https://github.com/rksm/hot-lib-reloader-rs) — 热重新加载Rust代码[！[build badge](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml)
* [just](https://github.com/casey/just) — 用于项目特定任务的便捷命令运行程序[！[build badge](https://api.travis-ci.org/casey/just.svg?branch=master)](https://travis-ci.org/casey/just)
* [mask](https://github.com/jacobdeichert/mask) — 由简单的markdown文件[！[build badge]定义的CLI任务运行程序(https://github.com/jacobdeichert/mask/workflows/CI/badge.svg?branch=master)](https://github.com/jacobdeichert/mask/actions?query=workflow%3ACI)
* [Module Linker](https://github.com/fiatjaf/module-linker) — 在GitHub的“mod”、“use”和“extern crate”语句中添加“<a>”链接到引用的扩展。
* [ptags](https://github.com/dalance/ptags) — git存储库的并行通用ctags包装[！[Build Status](https://api.travis-ci.org/dalance/ptags.svg?branch=master)](https://travis-ci.org/dalance/ptags)
* [Racer](https://github.com/racer-rust/racer) — Rust[！[build badge]的代码完成(https://api.travis-ci.org/racer-rust/racer.svg?branch=master)](https://travis-ci.org/racer-rust/racer)
* [Rust Search Extension](https://github.com/huhu/rust-search-extension) — 一个方便的浏览器扩展，可以在地址栏（综合框）中搜索板条箱和文档。[！[生成状态](https://github.com/huhu/rust-search-extension/workflows/build/badge.svg?branch=master)](https://github.com/huhu/rust-search-extension/actions)
* [rust-lang/rustfix](https://github.com/rust-lang/rustfix)  -自动应用rustc提出的建议
* [Rustup](https://github.com/rust-lang/rustup) — Rust工具链安装程序[！[build badge](https://github.com/rust-lang/rustup/workflows/Linux%20（master）/bedge.svg？分支=主）](https://github.com/rust-lang/rustup/actions)
* [scriptisto](https://github.com/igor-petruk/scriptisto) 一个语言不可知的“shebang解释器”，使您能够用编译语言编写一个文件脚本。[！[生成状态](https://cloud.drone.io/api/badges/igor-petruk/scriptisto/status.svg)](https://cloud.drone.io/igor-petruk/scriptisto)

### Build system

* [Cargo](https://crates.io/) — Rust包管理器
  * [cargo-all-features](https://github.com/frewsxcv/cargo-all-features) - 一个可配置的子命令，用于简化所有功能组合的测试、构建和更多功能[！[CI](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml/badge.svg)](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml)
  * [cargo-benchcmp](https://crates.io/crates/cargo-benchcmp) — 用于比较Rust微基准测试的实用程序[！[build badge](https://api.travis-ci.org/BurntSushi/cargo-benchcmp.svg?branch=master)](https://travis-ci.org/BurntSushi/cargo-benchcmp)
  * [cargo-bitbake](https://crates.io/crates/cargo-bitbake) — 一个货物扩展，可以利用meta-rust[！[build badge]中的类生成BitBake配方(https://api.travis-ci.org/cardoe/cargo-bitbake.svg?branch=master)](https://travis-ci.org/cardoe/cargo-bitbake)
  * [cargo-cache](https://crates.io/crates/cargo-cache) — 检查/管理/清理您的货物缓存（`~/.cargo/`/`${cargo_HOME}`）、打印大小等[！[Build Status](https://github.com/matthiaskrgr/cargo-cache/workflows/ci/badge.svg?branch=master)](https://github.com/matthiaskrgr/cargo-cache/actions)
  * [cargo-check](https://crates.io/crates/cargo-check) — 一个围绕“cargo rustc---Zno trans”的包装，如果您只需要正确性检查[！[build badge](https://api.travis-ci.org/rsolomo/cargo-check.svg?branch=master)](https://travis-ci.org/rsolomo/cargo-check)
  * [cargo-count](https://crates.io/crates/cargo-count) — 列出货物项目的源代码计数和详细信息，包括不安全统计[！[build badge](https://api.travis-ci.org/kbknapp/cargo-count.svg?branch=master)](https://travis-ci.org/kbknapp/cargo-count)
  * [cargo-deb](https://crates.io/crates/cargo-deb) — 生成二进制Debian包[！[build badge](https://api.travis-ci.org/mmstick/cargo-deb.svg?branch=master)](https://travis-ci.org/mmstick/cargo-deb)
  * [cargo-deps](https://crates.io/crates/cargo-deps) — 构建Rust项目的依赖关系图[！[build badge](https://api.travis-ci.com/m-cat/cargo-deps.svg?branch=master)](https://travis-ci.org/m-cat/cargo-deps)
  * [cargo-do](https://crates.io/crates/cargo-do) — 连续运行多个货物命令[！[build badge](https://api.travis-ci.org/pwoolcoc/cargo-do.svg?branch=master)](https://travis-ci.org/pwoolcoc/cargo-do)
  * [cargo-ebuild](https://crates.io/crates/cargo-ebuild) — 货物扩展，可以使用树内eclass[！[build badge]生成ebuild(https://api.travis-ci.org/cardoe/cargo-ebuild.svg?branch=master)](https://travis-ci.org/cardoe/cargo-ebuild)
  * [cargo-edit](https://crates.io/crates/cargo-edit) — 允许您通过读/写货物来添加和列出依赖项。命令行中的toml文件[！[build badge](https://api.travis-ci.org/killercup/cargo-edit.svg?branch=master)](https://travis-ci.org/killercup/cargo-edit)
  * [cargo-generate](https://github.com/cargo-generate/cargo-generate) 利用预先存在的git存储库作为模板，生成一个rust项目。
  * [cargo-graph](https://crates.io/crates/cargo-graph) — 更新了“cargo dot”的分叉，并添加了其他功能。未维护，请参见“货物部门”[！[build badge](https://api.travis-ci.org/kbknapp/cargo-graph.svg?branch=master)](https://travis-ci.org/kbknapp/cargo-graph)
  * [cargo-info](https://crates.io/crates/cargo-info) — 询问板条箱。io从命令行[！[build badge]获取板条箱详细信息(https://api.travis-ci.org/imp/cargo-info.svg?branch=master)](https://travis-ci.org/imp/cargo-info)
  * [cargo-license](https://crates.io/crates/cargo-license) — 用于快速查看所有依赖项的许可证的cargo子命令。[！[构建徽章](https://api.travis-ci.org/onur/cargo-license.svg?branch=master)](https://travis-ci.org/onur/cargo-license)
  * [cargo-make](https://crates.io/crates/cargo-make) — Rust任务运行器和构建工具。[！[构建徽章](https://github.com/sagiegurari/cargo-make/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/cargo-make/actions)
  * [cargo-modules](https://crates.io/crates/cargo-modules) — 一个货物插件，用于显示板条箱模块的树状概览。[！[构建徽章](https://api.travis-ci.org/regexident/cargo-modules.svg?branch=master)](https://travis-ci.org/regexident/cargo-modules)
  * [cargo-multi](https://crates.io/crates/cargo-multi) — 在多个板条箱上运行指定的货物命令[！[build badge](https://api.travis-ci.org/imp/cargo-multi.svg?branch=master)](https://travis-ci.org/imp/cargo-multi)
  * [cargo-outdated](https://crates.io/crates/cargo-outdated) — 当更新版本的Rust依赖项可用或过期时显示[！[build badge](https://api.travis-ci.org/kbknapp/cargo-outdated.svg?branch=master)](https://travis-ci.org/kbknapp/cargo-outdated)
  * [cargo-release](https://crates.io/crates/cargo-release) — 用于发布git管理的货物项目、构建、标记、发布、文档和推送的工具[！[Rust](https://github.com/crate-ci/cargo-release/actions/workflows/ci.yml/badge.svg)](https://github.com/crate-ci/cargo-release/actions/workflows/rust.yml)
  * [cargo-script](https://crates.io/crates/cargo-script) — 让人们快速轻松地运行Rust“脚本”，可以利用Cargo的包生态系统[！[build badge](https://api.travis-ci.org/DanielKeep/cargo-script.svg?branch=master)](https://travis-ci.org/DanielKeep/cargo-script)
  * [cargo-update](https://crates.io/crates/cargo-update) — cargo子命令，用于检查并将更新应用于已安装的可执行文件[！[build badge](https://api.travis-ci.org/nabijaczleweli/cargo-update.svg?branch=master)](https://travis-ci.org/nabijaczleweli/cargo-update)
  * [cargo-watch](https://crates.io/crates/cargo-watch) — 源代码更改时货物编译项目的实用程序[！[build badge](https://api.travis-ci.org/passcod/cargo-watch.svg?branch=master)](https://travis-ci.org/passcod/cargo-watch)
  * [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand) — 在源代码中展开宏
* CMake
  * [Devolutions/CMakeRust](https://github.com/Devolutions/CMakeRust) — 用于将Rust库集成到CMake项目中
  * [SiegeLord/RustCMake](https://github.com/SiegeLord/RustCMake) — 一个示例项目，显示了使用Rust[！[build badge]的CMake(https://api.travis-ci.org/SiegeLord/RustCMake.svg?branch=master)](https://travis-ci.org/SiegeLord/RustCMake)
* [Fleet](https://github.com/dimensionhq/fleet) [[舰队rs](https://crates.io/crates/fleet-rs)]-Rust的快速构建工具。
* Github actions
  * [icepuma/rust-action](https://github.com/icepuma/rust-action) — rust github操作
  * [peaceiris/actions-mdbook](https://github.com/peaceiris/actions-mdbook) — mdBook的GitHub操作

### Debugging

* GDB
  * [gdbgui](https://github.com/cs01/gdbgui) — 基于浏览器的前端，用于gdb调试C、C++、Rust和go。[！[构建徽章](https://api.travis-ci.org/cs01/gdbgui.svg?branch=master)](https://travis-ci.org/cs01/gdbgui)
* LLDB
  * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) — [Visual Studio代码]的LLDB扩展(https://code.visualstudio.com/).

### Deployment

* Docker
  * [emk/rust-musl-builder](https://github.com/emk/rust-musl-builder) — 使用musl-libc和musl-gcc编译静态Rust二进制文件的Docker映像，以及有用的C库的静态版本
  * [kpcyrd/mini-docker-rust](https://github.com/kpcyrd/mini-docker-rust) — 非常小的rust docker图像的示例项目[！[build badge](https://api.travis-ci.org/kpcyrd/mini-docker-rust.svg?branch=master)](https://travis-ci.org/kpcyrd/mini-docker-rust)
  * [liuchong/docker-rustup](https://github.com/liuchong/docker-rustup) — 多版本（使用musl工具）Rust Docker映像
  * [LukeMathWalker/cargo-chef](https://github.com/LukeMathWalker/cargo-chef) - 用于在Docker构建之间缓存编译远程依赖项的工具和预构建映像。
  * [messense/rust-musl-cross](https://github.com/messense/rust-musl-cross) — 使用musl cross[！[build badge]编译静态Rust二进制文件的Docker映像(https://api.travis-ci.org/messense/rust-musl-cross.svg?branch=master)](https://travis-ci.org/messense/rust-musl-cross)
  * [rust-lang-nursery/docker-rust](https://github.com/rust-lang/docker-rust) — Rust Docker官方图片
* Github Pages
  * [wasm-template-rust](https://github.com/sn99/wasm-template-rust) — 一个用于Rust的wasm模板，可以在不部署npm的情况下发布到gh页面
* Heroku
  * [emk/heroku-buildpack-rust](https://github.com/emk/heroku-buildpack-rust) — Heroku上Rust应用程序的内置包

### Embedded

[Rust Embedded](https://rust-embedded.org/) focuses on improving the end-to-end experience of using Rust in resource-constrained environments and non-traditional platforms. See [awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust) for a curated, and more extended list of embedded Rust resources.

* Arduino
  * [avr-rust/ruduino](https://github.com/avr-rust/ruduino) Arduino Uno的可重复使用组件。
* Cross compiling
  * [japaric/rust-cross](https://github.com/japaric/rust-cross) — 关于交叉编译Rust程序的所有信息[！[build badge](https://api.travis-ci.org/japaric/rust-cross.svg?branch=master)](https://travis-ci.org/japaric/rust-cross)
  * [japaric/xargo](https://github.com/japaric/xargo) — 轻松交叉编译Rust程序，定制ARM Cortex-M等裸机目标[！[build badge](https://api.travis-ci.org/japaric/xargo.svg?branch=master)](https://travis-ci.org/japaric/xargo)
* Espressif
  * [esp-rs](https://github.com/esp-rs) 许多社区项目支持在Espressif Systems生产的各种SoC和模块上使用Rust编程语言。
* nRF
  * [nrf-rs/nrf-hal](https://github.com/nrf-rs/nrf-hal) — nRF系列设备的Rust HAL
[![build badge](https://api.travis-ci.org/nrf-rs/nrf-hal.svg?branch=master)](https://travis-ci.org/nrf-rs/nrf-hal)

### FFI

See also [Foreign Function Interface](https://doc.rust-lang.org/book/first-edition/ffi.html),  [The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/) (a collection of examples of using code written in Rust from other languages) and [FFI examples written in Rust](https://github.com/alexcrichton/rust-ffi-examples).

* C
  * [rlhunt/cbindgen](https://github.com/eqrion/cbindgen) — 从Rust源文件生成C头文件。用于Gecko for WebRender[！[build badge](https://api.travis-ci.org/eqrion/cbindgen.svg?branch=master)](https://travis-ci.org/eqrion/cbindgen)
  * [Sean1708/rusty-cheddar](https://github.com/Sean1708/rusty-cheddar) — 从Rust源文件生成C头文件[！[build badge](https://api.travis-ci.org/Sean1708/rusty-cheddar.svg?branch=master)](https://travis-ci.org/Sean1708/rusty-cheddar)
* C++
  * [dtolnay/cxx](https://github.com/dtolnay/cxx) — Rust和C++之间的安全互操作[！[build badge](https://img.shields.io/badge/github-dtolnay/cxx-8da0cb?style=for-徽章&labelColor=555555&logo=github）](https://github.com/dtolnay/cxx)
  * [rust-cpp](https://crates.io/crates/cpp) - 直接在Rust中嵌入C++代码。[！[生成状态](https://api.travis-ci.org/mystor/rust-cpp.svg?branch=master)](https://travis-ci.org/mystor/rust-cpp)[！[生成状态](https://ci.appveyor.com/api/projects/status/uu76vmcrwnjqra0u/branch/master?svg=true)](https://ci.appveyor.com/project/mystor/rust-cpp/branch/master)
  * [rust-lang/rust-bindgen](https://github.com/rust-lang/rust-bindgen) — Rust绑定生成器
* Erlang
  * [rusterlium/rustler](https://github.com/rusterlium/rustler) — 用于创建Erlang NIF函数的安全Rust桥[！[build badge](https://api.travis-ci.org/rusterlium/rustler.svg?branch=master)](https://travis-ci.org/rusterlium/rustler)
* Haskell
  * [mgattozzi/curryrs](https://github.com/mgattozzi/curryrs) — 弥合Haskell和Rust之间的差距
* Java
  * [bennettanderson/rjni](https://github.com/benanders/rjni) — 使用Rust中的Java
  * [drrb/java-rust-example](https://github.com/drrb/java-rust-example) — 使用Java中的Rust[！[build badge](https://api.travis-ci.org/drrb/java-rust-example.svg?branch=master)](https://travis-ci.org/drrb/java-rust-example)
  * [j4rs](https://crates.io/crates/j4rs) — 使用Rust[！[build badge]中的Java(https://api.travis-ci.org/astonbitecode/j4rs.svg?branch=master)](https://travis-ci.org/astonbitecode/j4rs)
  * [jni](https://crates.io/crates/jni) — 使用Java中的Rust[！[build badge](https://api.travis-ci.org/jni-rs/jni-rs.svg?branch=master)](https://travis-ci.org/jni-rs/jni-rs)
  * [jni-sys](https://crates.io/crates/jni-sys) — 与jni对应的Rust定义。h[！[构建徽章](https://api.travis-ci.org/sfackler/rust-jni-sys.svg?branch=master)](https://travis-ci.org/sfackler/rust-jni-sys)
  * [rucaja](https://crates.io/crates/rucaja) — 使用Rust[！[build badge]中的Java(https://api.travis-ci.org/kud1ing/rucaja.svg?branch=master)](https://travis-ci.org/kud1ing/rucaja)
* Lua
  * [jcmoyer/rust-lua53](https://github.com/jcmoyer/rust-lua53) — Rust[！[build badge]的Lua 5.3绑定(https://api.travis-ci.org/jcmoyer/rust-lua53.svg?branch=master)](https://travis-ci.org/jcmoyer/rust-lua53)
  * [lilyball/rust-lua](https://github.com/lilyball/rust-lua) — Lua 5.1的安全Rust绑定[！[build badge](https://api.travis-ci.org/lilyball/rust-lua.svg?branch=master)](https://travis-ci.org/lilyball/rust-lua)
  * [tickbh/td_rlua](https://github.com/tickbh/td_rlua) [[td_rua](https://crates.io/crates/td_rlua)]-Rust[！[build badge]的零成本高级lua 5.3包装(https://api.travis-ci.org/tickbh/td_rlua.svg?branch=master)](https://travis-ci.org/tickbh/td_rlua)
  * [tomaka/hlua](https://github.com/tomaka/hlua) — Rust库与Lua[！[build badge]接口(https://api.travis-ci.org/tomaka/hlua.svg?branch=master)](https://travis-ci.org/tomaka/hlua)
* mruby
  * [anima-engine/mrusty](https://github.com/anima-engine/mrusty) — Rust[！[build badge]的mruby安全绑定(https://api.travis-ci.org/anima-engine/mrusty.svg?branch=master)](https://travis-ci.org/anima-engine/mrusty)
* Node.js
  * [infinyon/node-bindgen](https://github.com/infinyon/node-bindgen) - 使用Rust生成nodejs模块的简单方法
  * [neon-bindings/neon](https://github.com/neon-bindings/neon) — 用于编写安全快速的本机节点的Rust绑定。js模块[！[build badge](https://api.travis-ci.org/neon-bindings/neon.svg?branch=master)](https://travis-ci.org/neon-bindings/neon)
* Objective-C
  * [SSheldon/rust-objc](https://github.com/SSheldon/rust-objc) — Rust的Objective-C运行时绑定和包装
* Python
  * [dgrunwald/rust-cpython](https://github.com/dgrunwald/rust-cpython) — Python绑定[！[build badge](https://api.travis-ci.org/dgrunwald/rust-cpython.svg?branch=master)](https://travis-ci.org/dgrunwald/rust-cpython)
  * [getsentry/milksnake](https://github.com/getsentry/milksnake) — python setuptools的扩展，它允许您以最可移植的方式在python轮子中分发动态链接库。
  * [PyO3/PyO3](https://github.com/PyO3/PyO3) — Python解释器的Rust绑定[！[build badge](https://api.travis-ci.org/PyO3/pyo3.svg?branch=master)](https://travis-ci.org/PyO3/pyo3)
* Ruby
  * [d-unseductable/ruru](https://github.com/d-unseductable/ruru) — 用Rust[！[build badge]编写的原生Ruby扩展(https://api.travis-ci.org/d-unseductable/ruru.svg?branch=master)](https://travis-ci.org/d-unseductable/ruru)
  * [danielpclark/rutie](https://github.com/danielpclark/rutie) — 用Rust编写的本机Ruby扩展，反之亦然[！[Build Status](https://api.travis-ci.org/danielpclark/rutie.svg?branch=master)](https://travis-ci.org/danielpclark/rutie)
  * [tildeio/helix](https://github.com/tildeio/helix) — 用Rust[！[build badge]编写Ruby类(https://api.travis-ci.org/tildeio/helix.svg?branch=master)](https://travis-ci.org/tildeio/helix)
* Web Assembly
  * [rhysd/wain](https://github.com/rhysd/wain) - wain:WebAssembly INnterpeter在Safe Rust中从头开始，零依赖[！[build badge](https://github.com/rhysd/wain/workflows/CI/badge.svg?branch=master&event=push)](https://github.com/rhysd/wain/actions?query=workflow%3ACI+分支%3主控+事件%3推送）
  * [rustwasm/wasm-bindgen](https://github.com/rustwasm/wasm-bindgen) — 一个促进wasm模块和JS之间高层交互的项目。[！[构建徽章](https://api.travis-ci.com/rustwasm/wasm-bindgen.svg?branch=master)](https://travis-ci.org/rustwasm/wasm-bindgen)
  * [rustwasm/wasm-pack](https://github.com/rustwasm/wasm-pack) — ：package:：sparkes：打包wasm并发布到npm！[！[构建徽章](https://api.travis-ci.com/rustwasm/wasm-pack.svg?branch=master)](https://travis-ci.org/rustwasm/wasm-pack)

### Formatters

* [dprint](https://github.com/dprint/dprint) — 一个可插拔且可配置的代码格式化平台[！[build badge](https://github.com/dprint/dprint/workflows/CI/badge.svg)](https://github.com/dprint/dprint/actions?query=workflow%3ACI)
* [Prettier Rust](https://github.com/jinxdash/prettier-plugin-rust) — 一个固执己见的Rust代码格式化程序，可以自动修复错误的语法（〔Prettier〕(https://prettier.io/)社区插件）
* [rustfmt](https://github.com/rust-lang/rustfmt) — Rust团队维护的Rust代码格式化程序，包含在cargo[！[build badge]中(https://api.travis-ci.com/rust-lang/rustfmt.svg?branch=master)](https://app.travis-ci.com/github/rust-lang/rustfmt)

### IDEs

See also [Are we (I)DE yet?](https://areweideyet.com/) and [Rust Tools](https://www.rust-lang.org/tools).

  * [Atom](https://atom.io/)
    * [rust-lang/atom-ide-rust](https://github.com/rust-lang/atom-ide-rust) — Rust IDE对Atom的支持，由Rust语言服务器（RLS）提供支持[！[Build Status](https://api.travis-ci.com/rust-lang/atom-ide-rust.svg?branch=master)](https://app.travis-ci.com/grust-lang/atom-ide-rust)
  * [Eclipse](https://www.eclipse.org/)
    * [Eclipse Corrosion](https://github.com/eclipse/corrosion)
  * [Emacs](https://www.gnu.org/software/emacs/)
    * [emacs-racer](https://github.com/racer-rust/emacs-racer) — 自动完成（另请参见[公司](https://company-mode.github.io)和[自动完成](https://github.com/auto-complete/auto-complete))
    * [flycheck-rust](https://github.com/flycheck/flycheck-rust) — [Flycheck]防锈支撑(https://github.com/flycheck/flycheck)
    * [rust-mode](https://github.com/rust-lang/rust-mode) — 锈蚀主要模式
    * [rustic](https://github.com/brotzeit/rustic) - Emacs的Rust开发环境[！[build badge](https://github.com/brotzeit/rustic/workflows/CI/badge.svg)](https://github.com/brotzeit/rustic/actions?query=workflow%3ACI)
  * [gitpod.io](https://gitpod.io) — 基于Rust Language Server的完全Rust支持的在线IDE
  * [gnome-builder](https://wiki.gnome.org/Apps/Builder) 自版本3.22.2以来，对锈蚀和货物的本机支持
  * [IntelliJ](https://www.jetbrains.com/idea/)
    * [intellij-rust/intellij-rust](https://github.com/intellij-rust/intellij-rust) — [！[构建徽章](https://api.travis-ci.org/intellij-rust/intellij-rust.svg?branch=master)](https://travis-ci.org/intellij-rust/intellij-rust)
  * [Kakoune](http://kakoune.org/)
    * [kak-lsp/kak-lsp](https://github.com/kak-lsp/kak-lsp/) — [LSP](https://microsoft.github.io/language-server-protocol/)客户。在Rust中实现并支持开箱即用的rls。
  * [Ride](https://github.com/madeso/ride) — [！[构建徽章](https://api.travis-ci.org/madeso/ride.svg?branch=master)](https://travis-ci.org/madeso/ride)
  * [Sublime Text](https://www.sublimetext.com/)
    * [rust-lang/rust-enhanced](https://github.com/rust-lang/rust-enhanced) — 官方Rust包
  * [Vim](https://vim.sourceforge.io/) — 无处不在的文本编辑器
    * [autozimu/LanguageClient-neovim](https://github.com/autozimu/LanguageClient-neovim) — [LSP](https://microsoft.github.io/language-server-protocol/)客户。在Rust中实现并支持开箱即用的rls。
    * [crates.nvim](https://github.com/Saecki/crates.nvim) - 帮助管理板条箱的插件。io依赖项。
    * [rust.vim](https://github.com/rust-lang/rust.vim) — 提供文件检测、语法突出显示、格式化、Syntastic集成等。
    * [vim-racer](https://github.com/racer-rust/vim-racer) — 允许vim使用[Racer](https://github.com/racer-rust/racer)用于Rust代码完成和导航。
  * Visual Studio
    * [dgriffen/rls-vs2017](https://github.com/ZoeyR/rls-vs2017) — Visual Studio 2017预览版的Rust支持[！[build badge](https://ci.appveyor.com/api/projects/status/d2lxlincwninhsng?svg=true)](https://ci.appveyor.com/project/dgriffen/rls-vs2017)
    * [PistonDevelopers/VisualRust](https://github.com/PistonDevelopers/VisualRust) — Rust[！[Build status]的Visual Studio扩展(https://ci.appveyor.com/api/projects/status/5nw5no10jj0y4p3f?svg=true)](https://ci.appveyor.com/project/vosen/visualrust)
  * [Visual Studio Code](https://code.visualstudio.com/)
    * [Better TOML](https://marketplace.visualstudio.com/items?itemName=bungcip.better-toml) - vscode中的TOML支持
    * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) — LLDB扩展
    * [crates](https://github.com/serayuzgur/crates) — 板条箱是板条箱的扩展。io依赖项。[！[构建徽章](https://img.shields.io/vscode-marketplace/v/serayuzgur.crates.svg)](https://github.com/serayuzgur/crates)[！[构建徽章](https://api.travis-ci.org/serayuzgur/crates.svg?branch=master)](https://travis-ci.org/serayuzgur/crates)
    * [Prettier - Code formatter (Rust)](https://marketplace.visualstudio.com/items?itemName=jinxdash.prettier-rust) — 自动修复错误语法的Opinionated Rust代码格式化程序（〔Prettier〕(https://prettier.io/)社区插件）
    * [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer) — RLS的另一种Trust语言服务器
    * [rust-lang/rls-vscode](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust) — Visual Studio代码的Rust支持（同时支持RLS和Rust分析器）

### Profiling

* [bheisler/criterion.rs](https://github.com/bheisler/criterion.rs) — Rust的统计驱动基准库[！[Build Status](https://api.travis-ci.org/bheisler/criterion.rs.svg?branch=master)](https://travis-ci.org/bheisler/criterion.rs)
* [Bytehound](https://github.com/koute/bytehound) — Linux内存分析器
* [ellisonch/rust-stopwatch](https://github.com/ellisonch/rust-stopwatch) — 秒表库[！[构建徽章](https://api.travis-ci.org/ellisonch/rust-stopwatch.svg?branch=master)](https://travis-ci.org/ellisonch/rust-stopwatch)
* FlameGraphs
  * [llogiq/flame](https://github.com/llogiq/flame) — [！[构建徽章](https://api.travis-ci.org/llogiq/flame.svg?branch=master)](https://travis-ci.org/llogiq/flame)
  * [mrhooray/torch](https://github.com/mrhooray/torch) — 基于DWARF调试信息生成FlameGraphs
* [sharkdp/hyperfine](https://github.com/sharkdp/hyperfine) — 命令行基准测试工具[！[版本信息](https://img.shields.io/crates/v/hyperfine.svg)](https://crates.io/crates/hyperfine)[！[生成状态](https://api.travis-ci.org/sharkdp/hyperfine.svg?branch=master)](https://travis-ci.org/sharkdp/hyperfine)

### Services

* [deps.rs](https://github.com/deps-rs/deps.rs) — 检测过时或不安全的依赖项
* [docs.rs](https://docs.rs) — 板条箱的自动文档生成

### Static analysis

[[assert](https://crates.io/keywords/assert), [static](https://crates.io/keywords/static)]

* [facebookexperimental/MIRAI](https://github.com/facebookexperimental/mirai) — 在Rust的中级中间表示（MIR）上运行的抽象解释器[！[Continuous Integration](https://github.com/facebookexperimental/MIRAI/actions/workflows/rust.yml/badge.svg)](https://github.com/facebookexperimental/MIRAI/actions/workflows/rust.yml)
* [static_assertions](https://crates.io/crates/static_assertions) — 编译时断言以确保满足不变量[！[Build Status](https://api.travis-ci.org/nvzqz/static-assertions-rs.svg?branch=master)](https://travis-ci.org/nvzqz/static-assertions-rs/)

### Testing

[[test](https://crates.io/keywords/test), [testing](https://crates.io/keywords/testing)]

* Code Coverage
  * [tarpaulin](https://crates.io/crates/cargo-tarpaulin) — 为Rust[！[build badge]设计的代码覆盖工具(https://api.travis-ci.org/repositories/xd009642/tarpaulin.svg?branch=master)](https://travis-ci.org/xd009642/tarpaulin)
* Continuous Integration
  * [trust](https://github.com/japaric/trust) — 一个Travis CI和AppVeyor模板，用于在5种架构上测试Rust机箱，并发布Linux、macOS和Windows的二进制版本
* Frameworks and Runners
  * [AlKass/polish](https://github.com/AlKass/polish) — 小型测试/测试驱动框架[！[构建状态](https://api.travis-ci.org/AlKass/polish.svg?branch=master)](https://travis-ci.org/AlKass/polish)[！[板条箱包状态](https://img.shields.io/crates/v/polish.svg)](https://crates.io/crates/polish)
  * [cargo-dinghy](https://crates.io/crates/cargo-dinghy/) - 一个货物扩展，以简化在智能手机和其他小型处理器设备上运行库测试和测试台。
  * [cucumber](https://crates.io/crates/cucumber) [![Latest Version](https://img.shields.io/crates/v/cucumber.svg)](https://crates.io/crates/cucumber) — Rust的Cucumber测试框架的实现。完全本地，没有外部测试运行程序或依赖项。[！[生成状态](https://github.com/cucumber-rs/cucumber/workflows/CI/badge.svg?branch=master)](https://github.com/cucumber-rs/cucumber)
  * [demonstrate](https://crates.io/crates/demonstrate) — 声明性测试框架[！[生成状态](https://github.com/aubaugh/demonstrate/workflows/Continuous%20Integration/badge.svg?branch=master)](https://github.com/aubaugh/demonstrate)
  * [rstest](https://crates.io/crates/rstest) — Rust[！[Build Status]的基于夹具的测试框架(https://github.com/la10736/rstest/workflows/Test/badge.svg?branch=master)](https://github.com/la10736/rstest/actions)
  * [speculate](https://crates.io/crates/speculate) — 受RSpec启发的Rust最小测试框架
* Mocking and Test Data
  * [asomers/mockall](https://github.com/asomers/mockall) [[模拟](https://crates.io/crates/mockall)]-一个强大的Rust模拟对象库。[！[Cirrus构建状态](https://api.cirrus-ci.com/github/asomers/mockall.svg)](https://cirrus-ci.com/github/asomers/mockall)
  * [fake-rs](https://github.com/cksac/fake-rs) —  生成假数据的库[！[build badge](https://api.travis-ci.org/repositories/cksac/fake-rs.svg?branch=master)](https://travis-ci.org/cksac/fake-rs)
  * [goldenfile](https://github.com/calder/rust-goldenfile) [[黄金文件](https://crates.io/crates/goldenfile)]-为goldenfile测试提供简单API的库。[！[构建徽章](https://api.travis-ci.org/calder/rust-goldenfile.svg?branch=master)](https://travis-ci.org/calder/rust-goldenfile)
  * [httpmock](https://github.com/alexliesenfeld/httpmock) — HTTP模拟[！[build badge](https://dev.azure.com/alexliesenfeld/httpmock/_apis/build/status/alexliesenfeld.httpmock?branchName=master)](https://dev.azure.com/alexliesenfeld/httpmock/_build/latest?definitionId=2&branchName=master)
  * [mockiato](https://crates.io/crates/mockiato) — Rust 2018的严格但友好的模拟库[！[build badge](https://api.travis-ci.com/mockiato/mockiato.svg?branch=master)](https://app.travis-ci.com/github/mockiato/mockiato)
  * [mockito](https://crates.io/crates/mockito) — HTTP模拟[！[build badge](https://api.travis-ci.org/lipanski/mockito.svg?branch=master)](https://travis-ci.org/lipanski/mockito)
  * [nrxus/faux](https://github.com/nrxus/faux/) [![Latest Version](https://img.shields.io/crates/v/faux.svg)](https://crates.io/crates/faux) — 一个从结构中创建模拟的库！[构建](https://github.com/nrxus/faux/workflows/test/badge.svg?branch=master)
* Mutation Testing
  * [cargo-mutants](https://github.com/sourcefrog/cargo-mutants) [[货物变种](https://crates.io/crates/cargo-mutants)]-通过注入突变发现未充分测试的代码，无需更改源代码。[！[构建徽章](https://github.com/sourcefrog/cargo-mutants/actions/workflows/tests.yml/badge.svg?branch=main&event=push)](https://github.com/sourcefrog/cargo-mutants/actions/workflows/tests.yml?query=branch%3Amain)
  * [mutagen](https://github.com/llogiq/mutagen) [[诱变剂](https://crates.io/crates/mutagen)]-源级突变测试框架（仅限夜间）[！[build badge](https://api.travis-ci.org/llogiq/mutagen.svg?branch=master)](https://travis-ci.org/llogiq/mutagen)
* Property Testing and Fuzzing
  * [proptest](https://crates.io/crates/proptest) — 受[假设]启发的属性测试框架(https://hypothesis.works/)Python框架[！[build badge](https://api.travis-ci.org/altsysrq/proptest.svg?branch=master)](https://travis-ci.org/altsysrq/proptest)
  * [quickcheck](https://crates.io/crates/quickcheck) — [QuickCheck]的Rust实现(https://wiki.haskell.org/Introduction_to_QuickCheck1)[！[构建徽章](https://api.travis-ci.org/BurntSushi/quickcheck.svg?branch=master)](https://travis-ci.org/BurntSushi/quickcheck)
  * [rust-fuzz/afl.rs](https://github.com/rust-fuzz/afl.rs) — Rust fuzzer，使用[AFL](https://lcamtuf.coredump.cx/afl/)[！[构建徽章](https://api.travis-ci.org/rust-fuzz/afl.rs.svg?branch=master)](https://travis-ci.org/rust-fuzz/afl.rs)

### Transpiling

* [BayesWitnesses/m2cgen](https://github.com/BayesWitnesses/m2cgen) — 一个CLI工具，用于将经过训练的经典机器学习模型转换为零依赖的原生Rust代码。[！[GitHub操作状态](https://github.com/BayesWitnesses/m2cgen/workflows/GitHub%20Actions/badge.svg?branch=master)](https://github.com/BayesWitnesses/m2cgen/actions)
* [immunant/c2rust](https://github.com/immunant/c2rust) — C到Rust转换器和交叉检查器构建在Clang/LLVM之上。[！[生成状态](https://api.travis-ci.org/immunant/c2rust.svg?branch=master)](https://travis-ci.org/immunant/c2rust)
* [jameysharp/corrode](https://github.com/jameysharp/corrode) — 用Haskell编写的C到Rust转换器。

## Libraries

* [perf-monitor-rs](https://github.com/larksuite/perf-monitor-rs) — 一个工具包，旨在作为应用程序监控其性能的基础。[！[板条箱.io](https://img.shields.io/crates/v/perf_monitor.svg)](https://crates.io/crates/perf_monitor)
* [Phate6660/nixinfo](https://github.com/Phate6660/nixinfo) [[板条箱](https://crates.io/crates/nixinfo)]-用于收集系统信息（如cpu、发行版、环境、内核等）的库板条箱。

### Artificial Intelligence

#### Genetic algorithms

* [innoave/genevo](https://github.com/innoave/genevo) — 以可定制和可扩展的方式执行遗传算法（GA）模拟。
* [m-decoster/RsGenetic](https://github.com/m-decoster/RsGenetic) — Rust中的遗传算法库。处于维护模式。
* [Martin1887/oxigen](https://github.com/Martin1887/oxigen) — 快速、并行、可扩展和适应性强的遗传算法库。使用此库的一个示例仅在几秒钟内解决了N=255的N Queens问题，并且使用了不到1MB的RAM。
* [pkalivas/radiate](https://github.com/pkalivas/radiate) — 一个可定制的并行遗传编程引擎，能够为有监督、无监督和强化学习问题制定解决方案。随附NEAT和Evtree的完整且可定制的实现。[！[生成状态](https://api.travis-ci.com/pkalivas/radiate.svg?branch=master)](https://app.travis-ci.com/github/pkalivas/radiate)![板条箱.io](https://img.shields.io/crates/v/radiate)
* [willi-kappler/darwin-rs](https://github.com/willi-kappler/darwin-rs) — Rust的进化算法[！[Build Status](https://api.travis-ci.org/willi-kappler/darwin-rs.svg?branch=master)](https://travis-ci.org/willi-kappler/darwin-rs)

#### Machine learning

See [[Machine learning](https://crates.io/keywords/machine-learning)]

See also [About Rust’s Machine Learning Community](https://medium.com/@autumn_eng/about-rust-s-machine-learning-community-4cda5ec8a790#.hvkp56j3f) and [Are we learning yet?](https://www.arewelearningyet.com).

* [autumnai/leaf](https://github.com/autumnai/leaf) — 开放机器智能框架。[！[生成状态](https://api.travis-ci.org/autumnai/leaf.svg?branch=master)](https://travis-ci.org/autumnai/leaf). 放弃的项目。最新的叉子是[矛/果汁]（https://github.com/spearow/juice).
* [huggingface/tokenizers](https://github.com/huggingface/tokenizers) - Hugging Face面向现代NLP管道的标记化器，使用Rust（原始实现）编写，带有Python绑定。[！[生成状态](https://github.com/huggingface/tokenizers/workflows/Rust/badge.svg?branch=master)](https://github.com/huggingface/tokenizers/actions)
* [LaurentMazare/tch-rs](https://github.com/LaurentMazare/tch-rs) — PyTorch的Rust语言绑定。[！[生成状态](https://api.travis-ci.org/LaurentMazare/tch-rs.svg?branch=master)](https://travis-ci.org/LaurentMazare/tch-rs)
* [maciejkula/rustlearn](https://github.com/maciejkula/rustlearn) — Rust的机器学习板条箱。[！[圆圈CI](https://circleci.com/gh/maciejkula/rustlearn.svg?style=svg)](https://app.circleci.com/pipelines/github/maciejkula/rustlearn)
* [rust-ml/linfa](https://github.com/rust-ml/linfa) — 机器学习框架。
* [smartcorelib/smartcore](https://github.com/smartcorelib/smartcore) — Rust中的机器学习库[！[构建状态](https://img.shields.io/circleci/build/github/smartcorelib/smartcore)](https://smartcorelib.org/)
* [tensorflow/rust](https://github.com/tensorflow/rust) — TensorFlow的Rust语言绑定。[！[生成状态](https://api.travis-ci.org/tensorflow/rust.svg?branch=master)](https://travis-ci.org/tensorflow/rust)

### Astronomy

[[astronomy](https://crates.io/keywords/astronomy)]

* [fitsio](https://crates.io/crates/fitsio) — 适合界面库包装cfitsio[！[build badge](https://api.travis-ci.org/mindriot101/rust-fitsio.svg?branch=master)](https://travis-ci.org/mindriot101/rust-fitsio)
* [flosse/rust-sun](https://github.com/flosse/rust-sun) [[太阳](https://crates.io/crates/sun)]-JS库suncalc[！[build badge]的锈端口(https://api.travis-ci.org/flosse/rust-sun.svg?branch=master)](https://travis-ci.org/flosse/rust-sun)
* [saurvs/astro-rust](https://github.com/saurvs/astro-rust) — Rust的天文学[！[建造徽章](https://api.travis-ci.org/saurvs/astro-rust.svg?branch=master)](https://travis-ci.org/saurvs/astro-rust)

### Asynchronous

* [async-std](https://async.rs/) [[async-std]](https://crates.io/crates/async-std) - Rust标准库的异步版本[！[CI](https://github.com/async-rs/async-std/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/async-rs/async-std/actions/workflows/ci.yml)
* [dpc/mioco](https://github.com/dpc/mioco) — 可扩展、基于协同程序的异步IO处理库[！[build badge](https://api.travis-ci.org/dpc/mioco.svg?branch=master)](https://travis-ci.org/dpc/mioco)
* [mio](https://github.com/tokio-rs/mio) — MIO是Rust的一个轻量级IO库，其重点是尽可能减少操作系统抽象的开销[！[build badge](https://api.travis-ci.org/tokio-rs/mio.svg?branch=master)](https://travis-ci.org/tokio-rs/mio)
* [rust-lang/futures-rs](https://github.com/rust-lang/futures-rs) — Rust的零成本期货[！[构建徽章](https://api.travis-ci.com/rust-lang/futures-rs.svg?branch=master)](https://travis-ci.org/rust-lang/futures-rs)
* [TeaEntityLab/fpRust](https://github.com/TeaEntityLab/fpRust) — Monad/MonadIO、Handler、Coroutine/doNotation、Rust[！[build badge]的函数编程特性(https://api.travis-ci.org/TeaEntityLab/fpRust.svg?branch=master)](https://travis-ci.org/TeaEntityLab/fpRust)
* [Xudong-Huang/may](https://github.com/Xudong-Huang/may) — rust stackful协同程序库[！[build badge](https://api.travis-ci.org/Xudong-Huang/may.svg?branch=master)](https://travis-ci.org/Xudong-Huang/may)
* [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) — 一个带有工作窃取调度器的协同程序I/O库[！[build badge](https://api.travis-ci.org/zonyitoo/coio-rs.svg?branch=master)](https://travis-ci.org/zonyitoo/coio-rs)

### Audio and Music

[[audio](https://crates.io/keywords/audio)]

* [hound](https://crates.io/crates/hound) — WAV编码和解码库[！[build badge](https://api.travis-ci.org/ruuda/hound.svg?branch=master)](https://travis-ci.org/ruuda/hound)
* [insomnimus/nodi](https://github.com/insomnimus/nodi) [[节点](https://crates.io/crates/nodi)]-一个用于播放和提取MIDI文件的库。[！[构建徽章](https://github.com/insomnimus/nodi/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/insomnimus/nodi/actions)
* [jhasse/ears](https://github.com/jhasse/ears) — 在OpenAL和libsndfile[！[build badge]之上，一个简单的库可以播放声音和音乐(https://api.travis-ci.org/jhasse/ears.svg?branch=master)](https://travis-ci.org/jhasse/ears)
* [musitdev/portmidi-rs](https://github.com/musitdev/portmidi-rs) — [PortMidi](https://portmedia.sourceforge.net/portmidi/)绑定[！[build badge](https://api.travis-ci.org/musitdev/portmidi-rs.svg?branch=master)](https://travis-ci.org/musitdev/portmidi-rs)
* [ozankasikci/rust-music-theory](https://github.com/ozankasikci/rust-music-theory) — Rust音乐理论库[！[构建状态](https://api.travis-ci.com/ozankasikci/rust-music-theory.svg?branch=master)](https://travis-ci.org/ozankasikci/rust-music-theory)
* [pdeljanov/Symphonia](https://github.com/pdeljanov/Symphonia) — 一个纯Rust音频解码和媒体解复用库，支持AAC、FLAC、MP3、MP4、OGG、Vorbis和WAV。
* [RustAudio](https://github.com/RustAudio)
  * [RustAudio/cpal](https://github.com/RustAudio/cpal) - 纯Rust中的低级跨平台音频I/O库。[！[操作状态](https://github.com/RustAudio/cpal/workflows/cpal/badge.svg?branch=master)](https://github.com/RustAudio/cpal/actions)
  * [RustAudio/rodio](https://github.com/RustAudio/rodio) — Rust音频播放库[！[Build Status](https://api.travis-ci.org/RustAudio/rodio.svg?branch=master)](https://travis-ci.org/RustAudio/rodio)
  * [RustAudio/rust-portaudio](https://github.com/RustAudio/rust-portaudio) — PortAudio绑定[！[build badge](https://api.travis-ci.org/RustAudio/rust-portaudio.svg?branch=master)](https://travis-ci.org/RustAudio/rust-portaudio)
* [Serial-ATA/lofty-rs](https://github.com/Serial-ATA/lofty-rs) [[崇高](https://crates.io/crates/lofty)]-用于读取和编辑各种音频格式元数据的库[！[build badge](https://github.com/Serial-ATA/lofty-rs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Serial-ATA/lofty-rs/actions)

### Authentication

* [constantoine/totp-rs](https://github.com/constantoine/totp-rs) [[总计](https://crates.io/crates/totp-rs)]-2fa库，用于生成和验证基于TOTP的令牌！[生成状态](https://github.com/constantoine/totp-rs/workflows/Rust/badge.svg)
* [Keats/jsonwebtoken](https://github.com/Keats/jsonwebtoken) — [JSON Web令牌](https://en.wikipedia.org/wiki/JSON_Web_Token)库处于rust[！[生成状态](https://api.travis-ci.org/Keats/jsonwebtoken.svg?branch=master)](https://travis-ci.org/Keats/jsonwebtoken)
* [oauth2](https://github.com/ramosbugs/oauth2-rs) — 可扩展的强类型Rust OAuth2客户端库[！[Build Status](https://api.travis-ci.org/ramosbugs/oauth2-rs.svg?branch=main)](https://travis-ci.org/ramosbugs/oauth2-rs)
* [oxide-auth](https://github.com/HeroicKatora/oxide-auth) — OAuth2服务器库，用于与actix或其他前端结合使用，具有一组可配置和可插拔的后端[！[Build Status](https://api.cirrus-ci.com/github/HeroicKatora/oxide-auth.svg?branch=master)](https://cirrus-ci.com/github/HeroicKatora/oxide-auth)
* [sgrust01/jwtvault](https://github.com/sgrust01/jwtvault) — 用于管理和编排JWT工作流的异步库[！[Build Status](https://api.travis-ci.org/sgrust01/jwtvault.svg?branch=master)](https://travis-ci.org/sgrust01/jwtvault)
* [yup-oauth2](https://github.com/dermesser/yup-oauth2) — 提供设备、已安装和服务帐户流的oauth2客户端实现[！[Build Status](https://api.travis-ci.org/dermesser/yup-oauth2.svg?branch=master)](https://travis-ci.org/dermesser/yup-oauth2)

### Automotive

* [marcelbuesing/can-dbc](https://github.com/marcelbuesing/can-dbc) [[可以dbc](https://crates.io/crates/can-dbc)]-DBC格式的解析器[！[build badge](https://api.travis-ci.org/marcelbuesing/can-dbc.svg?branch=dev)](https://travis-ci.org/marcelbuesing/can-dbc)
* [marcelbuesing/tokio-socketcan-bcm](https://github.com/marcelbuesing/tokio-socketcan-bcm) [[东京socketcan bcm](https://crates.io/crates/tokio-socketcan-bcm)]-Linux SocketCAN BCM对tokio的支持[！[build badge](https://api.travis-ci.org/marcelbuesing/tokio-socketcan-bcm.svg?branch=master)](https://travis-ci.org/marcelbuesing/tokio-socketcan-bcm)
* [mbr/socketcan](https://github.com/socketcan-rs/socketcan-rs) [[插座罐](https://crates.io/crates/socketcan)]-Linux SocketCAN库
* [oefd/tokio-socketcan](https://github.com/oefd/tokio-socketcan) [[东京插座罐]](https://crates.io/crates/tokio-socketcan)]-基于SocketCAN机箱的Linux SocketCAN对tokio的支持
* [Sensirion/lin-bus](https://github.com/Sensirion/lin-bus-rs) [[lin总线](https://crates.io/crates/lin-bus)]-LIN总线驱动器特性和协议实现[！[构建徽章](https://circleci.com/gh/Sensirion/lin-bus-rs.svg?style=svg)](https://app.circleci.com/pipelines/github/Sensirion/lin-bus-rs)

### Bioinformatics

* [Rust-Bio](https://github.com/rust-bio) — Rust中的生物信息学库。

### Caching

* [aisk/rust-memcache](https://github.com/aisk/rust-memcache) — Memcached客户端库[！[build badge](https://api.travis-ci.org/aisk/rust-memcache.svg?branch=master)](https://travis-ci.org/aisk/rust-memcache)
* [al8n/stretto](https://github.com/al8n/stretto) - 高性能线程安全内存绑定Rust缓存[！[build badge](https://github.com/al8n/stretto/actions/workflows/ci.yml/badge.svg)](https://github.com/al8n/stretto/actions/workflows/ci.yml)
* [jaemk/cached](https://github.com/jaemk/cached) — 简单的功能缓存/记忆
* [mozilla/sccache](https://github.com/mozilla/sccache/) - 共享编译缓存，非常适合Rust编译[！[build badge](https://api.travis-ci.org/mozilla/sccache.svg?branch=master)](https://travis-ci.org/mozilla/sccache)

### Cloud

* AWS [[aws](https://crates.io/keywords/aws)]
  * [awslabs/aws-lambda-rust-runtime](https://github.com/awslabs/aws-lambda-rust-runtime) [[lambda_runtime](https://crates.io/crates/lambda_runtime)]-AWS Lambda的Rust运行时[！[build badge](https://github.com/awslabs/aws-lambda-rust-runtime/workflows/Rust/badge.svg)](https://github.com/awslabs/aws-lambda-rust-runtime/actions)
  * [awslabs/aws-sdk-rust](https://github.com/awslabs/aws-sdk-rust) - 用于Rust的新AWS SDK
  * [rusoto/rusoto](https://github.com/rusoto/rusoto) — [！[构建徽章](https://api.travis-ci.org/rusoto/rusoto.svg?branch=master)](https://travis-ci.org/rusoto/rusoto)
* Load Balancer
  * [Convey](https://github.com/bparli/convey) - 具有动态配置加载的第4层负载平衡器。
* Multi Cloud
  * [Qovery/engine](https://github.com/Qovery/engine) - 抽象层库，只需几分钟即可轻松在云提供商上部署应用程序

### Command-line

* Argument parsing
  * [clap-rs](https://github.com/clap-rs/clap) [[鼓掌](https://crates.io/crates/clap)]-一个易于使用、功能齐全的命令行参数解析器[！[build badge](https://api.travis-ci.org/clap-rs/clap.svg?branch=master)](https://travis-ci.org/clap-rs/clap)
  * [cliparser](https://crates.io/crates/cliparser) — 简单的命令行分析器。[！[构建徽章](https://github.com/sagiegurari/cliparser/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/cliparser/actions)
  * [docopt/docopt.rs](https://github.com/docopt/docopt.rs) [[文档选项](https://crates.io/crates/docopt)]-[DocOpt]的Rust实现(http://docopt.org)[！[构建徽章](https://api.travis-ci.org/docopt/docopt.rs.svg?branch=master)](https://travis-ci.org/docopt/docopt.rs)
  * [google/argh](https://github.com/google/argh) [参数](https://crates.io/crates/argh)]-针对代码大小[！[build badge]优化的基于Derive的自变量分析器(https://github.com/google/argh/workflows/Argh/badge.svg?branch=master)](https://github.com/google/argh/actions)
  * [killercup/quicli](https://github.com/killercup/quicli) [[奎克利](https://crates.io/crates/quicli)]-在Rust[！[build badge]中快速构建酷炫的CLI应用程序(https://api.travis-ci.org/killercup/quicli.svg?branch=master)](https://travis-ci.org/killercup/quicli)
  * [ksk001100/seahorse](https://github.com/ksk001100/seahorse) [[海马](https://crates.io/crates/seahorse)]-用Rust[！[Build status]编写的最小CLI框架(https://github.com/ksk001100/seahorse/workflows/CI/badge.svg?branch=master)](https://github.com/ksk001100/seahorse/actions)
  * [TeXitoi/structopt](https://github.com/TeXitoi/structopt) [[结构选项](https://crates.io/crates/structopt)]-通过定义结构[！[build badge]解析命令行参数(https://api.travis-ci.org/TeXitoi/structopt.svg?branch=master)](https://travis-ci.org/TeXitoi/structopt)
* Data visualization
  * [nukesor/comfy-table](https://github.com/nukesor/comfy-table) [[舒适的桌子](https://crates.io/crates/comfy-table)]-为您的cli工具提供漂亮的动态表格。[！[生成状态](https://github.com/Nukesor/comfy-table/workflows/Tests/badge.svg?branch=master)](https://github.com/nukesor/comfy-table/actions)
  * [zhiburt/tabled](https://github.com/zhiburt/tabled) [[表格](https://crates.io/crates/tabled)]-一个易于使用的库，用于Rust结构和枚举的漂亮打印表。[！[生成状态](https://github.com/zhiburt/tabled/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/tabled/actions)
* Human-centered design
  * [rust-cli/human-panic](https://github.com/rust-cli/human-panic) [[人类恐慌](https://crates.io/crates/human-panic)]-人类的恐慌信息[！[build badge](https://api.travis-ci.org/rust-cli/human-panic.svg?branch=master)](https://travis-ci.org/rust-cli/human-panic)
* Line editor
  * [kkawakam/rustyline](https://github.com/kkawakam/rustyline) [[锈线](https://crates.io/crates/rustyline)]-Rust[！[build badge]中的readline实现(https://api.travis-ci.org/kkawakam/rustyline.svg?branch=master)](https://travis-ci.org/kkawakam/rustyline)
  * [MovingtoMars/liner](https://github.com/MovingtoMars/liner) [[衬垫](https://crates.io/crates/liner)]-提供类似于readline的功能的库[！[build badge](https://api.travis-ci.org/MovingtoMars/liner.svg?branch=master)](https://travis-ci.org/MovingtoMars/liner)
  * [murarth/linefeed](https://github.com/murarth/linefeed) [[换行](https://crates.io/crates/linefeed)]-可配置、可扩展、交互式线路阅读器[！[build badge](https://api.travis-ci.org/murarth/linefeed.svg?branch=master)](https://travis-ci.org/murarth/linefeed)
  * [srijs/rust-copperline](https://github.com/srijs/rust-copperline) [[铜](https://crates.io/crates/copperline)]-纯Rust命令行编辑库
* Other
  * [mgrachev/update-informer](https://github.com/mgrachev/update-informer) [[更新举报人](https://crates.io/crates/update-informer)]-更新CLI应用程序的informer。它在板条箱上检查新版本。io和GitHub[！[构建徽章](https://github.com/mgrachev/update-informer/workflows/CI/badge.svg)](https://github.com/mgrachev/update-informer/actions)
* Pipeline
  * [hniksic/rust-subprocess](https://github.com/hniksic/rust-subprocess) [[子流程](https://crates.io/crates/subprocess)]-与外部管道相互作用的设施[！[build badge](https://api.travis-ci.org/hniksic/rust-subprocess.svg?branch=master)](https://travis-ci.org/hniksic/rust-subprocess)
  * [imp/pager-rs](https://gitlab.com/imp/pager-rs) [[寻呼机](https://crates.io/crates/pager)]-通过外部寻呼机传送输出
  * [oconnor663/duct.rs](https://github.com/oconnor663/duct.rs) [[管道](https://crates.io/crates/duct)]-子流程管道和IO重定向的生成器[！[build badge](https://api.travis-ci.org/oconnor663/duct.rs.svg?branch=master)](https://travis-ci.org/oconnor663/duct.rs)
  * [rust-cli/rexpect](https://github.com/rust-cli/rexpect) [[预期](https://crates.io/crates/rexpect)]-自动化交互式应用程序，如ssh、ftp、passwd等[！[CI](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml/badge.svg)](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml)
  * [zhiburt/expectrl](https://github.com/zhiburt/expectrl) [[期待](https://crates.io/crates/expectrl)]-用于控制伪终端中交互程序的库[！[build badge](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml)
* Progress
  * [a8m/pb](https://github.com/a8m/pb) [[电话](https://crates.io/crates/pbr)]-Rust的控制台进度条
  * [console-rs/indicatif](https://github.com/console-rs/indicatif) [[指标](https://crates.io/crates/indicatif)]-向用户指示进度
  * [etienne-napoleone/spinach](https://github.com/etienne-napoleone/spinach) [[菠菜](https://crates.io/crates/spinach)]-防锈实用旋转器。[！[CI](https://github.com/etienne-napoleone/spinach/actions/workflows/ci.yml/badge.svg)](https://github.com/etienne-napoleone/spinach/actions/workflows/ci.yml)
  * [FGRibreau/spinners](https://github.com/FGRibreau/spinners) [[微调器](https://crates.io/crates/spinners)]-60多个优雅的终端旋转器
* Prompt
  * [hashmismatch/terminal_cli.rs](https://github.com/hashmismatch/terminal_cli.rs) [[终端](https://crates.io/crates/terminal_cli)]-构建交互式命令提示符[！[build badge](https://api.travis-ci.org/hashmismatch/terminal_cli.rs.svg?branch=master)](https://travis-ci.org/hashmismatch/terminal_cli.rs)
  * [starship/starship](https://starship.rs/) [[星舰](https://crates.io/crates/starship)]-任何shell的最小、快速、可定制的提示[！[Build status](https://github.com/starship/starship/workflows/Main%20workflow/badge.svg?branch=master)](https://github.com/starship/starship/actions)
  * [ynqa/promkit](https://github.com/ynqa/promkit) [[提示](https://crates.io/crates/promkit)]-用于构建交互式命令行工具的工具包[！[Build status](https://github.com/ynqa/promkit/workflows/promkit/badge.svg?branch=master)](https://github.com/ynqa/promkit/actions)
* Style
  * [LukasKalbertodt/bunt](https://github.com/LukasKalbertodt/bunt) [[短发](https://crates.io/crates/bunt)]-使用宏的跨平台终端颜色和样式[！[Build status](https://github.com/LukasKalbertodt/bunt/actions/workflows/ci.yml/badge.svg)](https://github.com/LukasKalbertodt/bunt/actions?query=workflow%3ACI+分支%3主控）
  * [LukasKalbertodt/term-painter](https://github.com/LukasKalbertodt/term-painter) [[术语画家](https://crates.io/crates/term-painter)]-跨平台风格的终端输出[！[build badge](https://api.travis-ci.org/LukasKalbertodt/term-painter.svg?branch=master)](https://travis-ci.org/LukasKalbertodt/term-painter)
  * [mackwic/colored](https://github.com/mackwic/colored) [[彩色](https://crates.io/crates/colored)]-着色终端如此简单，您已经知道如何操作了！
  * [ogham/rust-ansi-term](https://github.com/ogham/rust-ansi-term) [[答案](https://crates.io/crates/ansi_term)]-控制ANSI终端的颜色和格式[！[build badge](https://api.travis-ci.org/ogham/rust-ansi-term.svg?branch=master)](https://travis-ci.org/ogham/rust-ansi-term)
  * [SergioBenitez/yansi](https://github.com/SergioBenitez/yansi) [[延思](https://crates.io/crates/yansi)]-一个非常简单的ANSI终端彩绘库
* TUI
  * BearLibTerminal
    * [cfyzium/bearlibterminal](https://github.com/nabijaczleweli/BearLibTerminal.rs) [[熊库终端](https://crates.io/crates/bear-lib-terminal)]-[BearLibTerminal](https://github.com/tommyettinger/BearLibTerminal)绑定[！[build badge](https://api.travis-ci.org/nabijaczleweli/BearLibTerminal.rs.svg?branch=master)](https://travis-ci.org/nabijaczleweli/BearLibTerminal.rs)
  * [fdehau/tui-rs](https://github.com/fdehau/tui-rs) [[推](https://crates.io/crates/tui)]-TUI图书馆的灵感来源于[祝福的控件](https://github.com/yaronn/blessed-contrib)和[termui](https://github.com/gizak/termui)[！[构建徽章](https://api.travis-ci.org/fdehau/tui-rs.svg?branch=master)](https://travis-ci.org/fdehau/tui-rs)
  * [gyscos/Cursive](https://github.com/gyscos/Cursive) [[草书](https://crates.io/crates/cursive)]-构建丰富的TUI应用程序[！[build badge](https://api.travis-ci.org/gyscos/Cursive.svg?branch=master)](https://travis-ci.org/gyscos/Cursive)
  * [ivanceras/titik](https://github.com/ivanceras/titik) - 跨平台TUI小部件库，目标是提供交互式小部件[！[Build Status](https://api.travis-ci.com/ivanceras/titik.svg?branch=master)](https://app.travis-ci.com/github/ivanceras/titik)
  * ncurses
    * [ihalila/pancurses](https://github.com/ihalila/pancurses) [[煎饼](https://crates.io/crates/pancurses)]-curses库，支持linux和windows[！[build badge](https://api.travis-ci.org/ihalila/pancurses.svg?branch=master)](https://travis-ci.org/ihalila/pancurses)
    * [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs) [[课程](https://crates.io/crates/ncurses)]-[课程](https://www.gnu.org/software/ncurses/)绑定[！[build badge](https://api.travis-ci.org/jeaye/ncurses-rs.svg?branch=master)](https://travis-ci.org/jeaye/ncurses-rs)
  * [ogham/rust-term-grid](https://github.com/ogham/rust-term-grid) [[术语网格](https://crates.io/crates/term_grid)]-用于将事物放入网格的Rust库[！[build badge](https://api.travis-ci.org/ogham/rust-term-grid.svg?branch=master)](https://travis-ci.org/ogham/rust-term-grid)
  * [redox-os/termion](https://github.com/redox-os/termion) [[期限](https://crates.io/crates/termion)]-用于控制终端的无绑定库/TTY[！[build badge](https://api.travis-ci.org/redox-os/termion.svg?branch=master)](https://travis-ci.org/redox-os/termion)
  * Termbox
    * [gchp/rustbox](https://github.com/gchp/rustbox) [[锈盒](https://crates.io/crates/rustbox)]-绑定到[Termbox](https://github.com/nsf/termbox)[！[构建徽章](https://api.travis-ci.org/gchp/rustbox.svg?branch=master)](https://travis-ci.org/gchp/rustbox)
  * [TimonPost/crossterm](https://github.com/crossterm-rs/crossterm) [[交叉术语](https://crates.io/crates/crossterm)]-跨平台终端库

### Compression

* [Brotli](https://opensource.googleblog.com/2015/09/introducing-brotli-new-compression.html)
  * [dropbox/rust-brotli](https://github.com/dropbox/rust-brotli) — Rust中的Brotli解压缩程序，可选地避免stdlib
  * [ende76/brotli-rs](https://github.com/ende76/brotli-rs) — Brotli压缩的实现
* bzip2
  * [alexcrichton/bzip2-rs](https://github.com/alexcrichton/bzip2-rs) — [libbz2](https://www.sourceware.org/bzip2/)绑定[！[build badge](https://api.travis-ci.com/alexcrichton/bzip2-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/bzip2-rs)
* gzip
  * [zopfli](https://github.com/zopfli-rs/zopfli) [[zopfli](https://crates.io/crates/zopfli)]-实现Zopfli压缩算法以实现更高质量的deflate或zlib压缩
* gzp
  * [sstadick/gzp](https://github.com/sstadick/gzp/) - deflate格式和snapy的多线程编码和解码
* miniz
  * [rust-lang/flate2-rs](https://github.com/rust-lang/flate2-rs) — [迷你](https://code.google.com/archive/p/miniz)绑定[！[build badge](https://github.com/rust-lang/flate2-rs/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/flate2-rs/actions)
* snappy
  * [JeffBelgum/rust-snappy](https://github.com/JeffBelgum/rust-snappy) — [敏捷](https://github.com/google/snappy)绑定[！[build badge](https://api.travis-ci.org/JeffBelgum/rust-snappy.svg?branch=master)](https://travis-ci.org/JeffBelgum/rust-snappy)
* tar
  * [alexcrichton/tar-rs](https://github.com/alexcrichton/tar-rs) — 用Rust[！[build badge]读取/写入tar存档(https://api.travis-ci.com/alexcrichton/tar-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/tar-rs)
* zip
  * [zip-rs/zip](https://github.com/zip-rs/zip) — 读取和写入ZIP档案[！[Build Status](https://api.travis-ci.org/mvdnes/zip-rs.svg?branch=master)](https://travis-ci.org/mvdnes/zip-rs)

### Computation

* [argmin-rs/argmin](https://github.com/argmin-rs/argmin) [[参数最小值](https://crates.io/crates/argmin)]-纯Rust优化库[！[build badge](https://api.travis-ci.org/argmin-rs/argmin.svg?branch=master)](https://travis-ci.org/argmin-rs/argmin)
* [BLAS](https://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms) [[布拉斯](https://crates.io/keywords/blas)]
  * [mikkyang/rust-blas](https://github.com/mikkyang/rust-blas) — BLAS绑定
* [calebwin/emu](https://github.com/calebwin/emu) — 基于Rust宏的GPGPU数值计算语言
* [dimforge/nalgebra](https://github.com/dimforge/nalgebra) — 低维线性代数库[！[build badge](https://api.travis-ci.org/dimforge/nalgebra.svg?branch=dev)](https://travis-ci.org/dimforge/nalgebra)
* [GSL](http://www.gnu.org/software/gsl/)
  * [GuillaumeGomez/rust-GSL](https://github.com/GuillaumeGomez/rust-GSL) — GSL绑定[！[build badge](https://api.travis-ci.org/GuillaumeGomez/rust-GSL.svg?branch=master)](https://travis-ci.org/GuillaumeGomez/rust-GSL)
* [LAPACK](https://en.wikipedia.org/wiki/LAPACK)
  * [stainless-steel/lapack](https://github.com/blas-lapack-rs/lapack) — LAPACK绑定[！[build badge](https://api.travis-ci.org/blas-lapack-rs/lapack.svg?branch=master)](https://travis-ci.org/blas-lapack-rs/lapack)
* Parallel
  * [arrayfire/arrayfire-rust](https://github.com/arrayfire/arrayfire-rust) — [Arrayfire](https://github.com/arrayfire)绑定
  * [autumnai/collenchyma](https://github.com/autumnai/collenchyma) — 一个可扩展、可插拔、后端不可知的框架，用于CUDA、OpenCL和通用主机CPU上的并行、高性能计算。[！[构建徽章](https://api.travis-ci.org/autumnai/collenchyma.svg?branch=master)](https://travis-ci.org/autumnai/collenchyma)
  * [luqmana/rust-opencl](https://github.com/luqmana/rust-opencl) — [OpenCL](https://www.khronos.org/opencl/)绑定
* Scirust
  * [indigits/scirust](https://github.com/indigits/scirust) — Rust中的科学计算库[！[Build Status](https://api.travis-ci.org/indigits/scirust.svg?branch=master)](https://travis-ci.org/indigits/scirust)
* Statrs
  * [statrs-dev/statrs](https://github.com/statrs-dev/statrs) — Rust[！[Build Status]中的稳健统计计算库(https://api.travis-ci.org/boxtown/statrs.svg?branch=master)](https://travis-ci.org/boxtown/statrs)

### Concurrency

* [crossbeam-rs/crossbeam](https://github.com/crossbeam-rs/crossbeam) –支持Rust[！[build badge]中的并行性和低级别并发(https://api.travis-ci.org/crossbeam-rs/crossbeam.svg?branch=master)](https://travis-ci.org/crossbeam-rs/crossbeam)
* [orium/archery](https://github.com/orium/archery) [[射箭](https://crates.io/crates/archery)]-从`Rc`/`Arc`指针类型抽象的库。[！[构建徽章](https://api.travis-ci.org/orium/archery.svg?branch=master)](https://travis-ci.org/orium/archery)
* [Rayon](https://github.com/rayon-rs/rayon) –Rust[！[build badge]的数据并行库(https://api.travis-ci.org/rayon-rs/rayon.svg?branch=master)](https://travis-ci.org/rayon-rs/rayon)
* [rustcc/coroutine-rs](https://github.com/rustcc/coroutine-rs) –Rust中的Coroutine库[！[构建徽章](https://api.travis-ci.org/rustcc/coroutine-rs.svg?branch=master)](https://travis-ci.org/rustcc/coroutine-rs)
* [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) –Coroutine I/O for Rust[！[构建徽章](https://api.travis-ci.org/zonyitoo/coio-rs.svg?branch=master)](https://travis-ci.org/zonyitoo/coio-rs)

### Configuration

* [andoriyu/uclicious](https://github.com/andoriyu/uclicious) [[核素](https://crates.io/crates/uclicious)]-[libUCL](https://github.com/vstakhov/libucl)基于功能丰富的配置库。[！[CircleCI](https://circleci.com/gh/vstakhov/libucl.svg?style=svg)](https://app.circleci.com/pipelines/github/vstakhov/libucl)
* [Kixunil/configure_me](https://github.com/Kixunil/configure_me) [[配置名称](https://crates.io/crates/configure_me)]-用于轻松处理应用程序配置的库
* [mehcode/config-rs](https://github.com/mehcode/config-rs) [[配置](https://crates.io/crates/config)]-Rust应用程序的分层配置系统（对12因素应用程序的强大支持）。[！[构建徽章](https://api.travis-ci.org/mehcode/config-rs.svg?branch=master)](https://travis-ci.org/mehcode/config-rs)

### Cryptography

[[crypto](https://crates.io/keywords/crypto), [cryptography](https://crates.io/keywords/cryptography)]

* [briansmith/ring](https://github.com/briansmith/ring) — 使用Rust和BoringSSL的加密原语进行安全、快速、小型加密。[！[构建徽章](https://api.travis-ci.org/briansmith/ring.svg?branch=master)](https://travis-ci.org/briansmith/ring)
* [briansmith/webpki](https://github.com/briansmith/webpki) — Rust中的Web PKI TLS X.509证书验证。[！[构建徽章](https://api.travis-ci.org/briansmith/webpki.svg?branch=master)](https://travis-ci.org/briansmith/webpki)
* [conradkleinespel/rooster](https://github.com/conradkleinespel/rooster) [[公鸡](https://crates.io/crates/rooster)]-终端中使用的简单密码管理器
* [cossacklabs/themis](https://github.com/cossacklabs/themis) [[主题](https://crates.io/crates/themis)]-用于解决典型数据安全任务的高级密码库，最适合多平台应用程序。[！[构建徽章](https://circleci.com/gh/cossacklabs/themis/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/cossacklabs/themis)
* [DaGenix/rust-crypto](https://github.com/DaGenix/rust-crypto) — Rust[！[build badge]中的加密算法(https://api.travis-ci.org/DaGenix/rust-crypto.svg?branch=master)](https://travis-ci.org/DaGenix/rust-crypto)
* [dalek-cryptography/curve25519-dalek](https://github.com/dalek-cryptography/curve25519-dalek) — Curve25519操作的纯Rust实现
* [dalek-cryptography/ed25519-dalek](https://github.com/dalek-cryptography/ed25519-dalek) — Ed25519数字签名的纯Rust实现
* [dalek-cryptography/x25519-dalek](https://github.com/dalek-cryptography/x25519-dalek) — X25519密钥交换的纯Rust实现
* [debris/tiny-keccak](https://github.com/debris/tiny-keccak) — Keccak系列的纯Rust实现（SHA3）
* [exonum/exonum](https://github.com/exonum/exonum) [[外显子](https://crates.io/crates/exonum)]-区块链项目的可扩展框架[！[build badge](https://api.travis-ci.com/exonum/exonum.svg?branch=master)](https://travis-ci.org/exonum/exonum)
* [gakonst/ark-circom](https://github.com/gakonst/ark-circom) - Arkworks绑定到Circom的R1CS，用于Rust中的Groth16 Proof和Witness生成。
* [klutzy/suruga](https://github.com/klutzy/suruga) — [TLS 1.2]的Rust实现(https://datatracker.ietf.org/doc/html/rfc5246)
* [kornelski/rust-security-framework](https://github.com/kornelski/rust-security-framework) — 安全框架绑定（OSX本机）
* [libOctavo/octavo](https://github.com/libOctavo/octavo) — Rust[！[build badge]中的模块化哈希和加密库(https://api.travis-ci.org/libOctavo/octavo.svg?branch=master)](https://travis-ci.org/libOctavo/octavo)
* [novifinancial/opaque-ke](https://github.com/novifinancial/opaque-ke) — 最近[OPAQUE]的纯Rust实现(https://datatracker.ietf.org/doc/draft-krawczyk-cfrg-opaque/)密码认证密钥交换。[！[构建徽章](https://github.com/novifinancial/opaque-ke/workflows/Rust%20CI/badge.svg?branch=master)](https://github.com/novifinancial/opaque-ke)
* [orion-rs/orion](https://github.com/orion-rs/orion) — 该库旨在提供简单易用的加密。”“可用”意味着暴露易于使用且难以误用的高级API。[！[测试](https://github.com/orion-rs/orion/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/orion-rs/orion/actions/workflows/test.yml)
* [racum/rust-djangohashers](https://github.com/racum/rust-djangohashers) [[djangohashers](https://crates.io/crates/djangohashers)]-Django项目中使用的密码原语的Rust端口。它不需要Django，只需要根据其样式对密码进行哈希和验证。[！[构建徽章](https://api.travis-ci.org/Racum/rust-djangohashers.svg?branch=master)](https://travis-ci.org/Racum/rust-djangohashers)
* [RustCrypto/hashes](https://github.com/RustCrypto/hashes) — 用纯Rust[！[build badge]编写的加密哈希函数集合(https://api.travis-ci.org/RustCrypto/hashes.svg?branch=master)](https://travis-ci.org/RustCrypto/hashes)
* [rustls/rustls](https://github.com/rustls/rustls) — TLS的Rust实现
* [sfackler/rust-native-tls](https://github.com/sfackler/rust-native-tls) — 本机TLS库的绑定
* [sfackler/rust-openssl](https://github.com/sfackler/rust-openssl) — [开放SSL](https://www.openssl.org/)绑定[！[build badge](https://api.travis-ci.org/sfackler/rust-openssl.svg?branch=master)](https://travis-ci.org/sfackler/rust-openssl)
* [sodiumoxide/sodiumoxide](https://github.com/sodiumoxide/sodiumoxide) — [利钠盐](https://github.com/jedisct1/libsodium)绑定[！[build badge](https://api.travis-ci.org/sodiumoxide/sodiumoxide.svg?branch=master)](https://travis-ci.org/sodiumoxide/sodiumoxide)
* [vityafx/randomorg](https://github.com/vityafx/randomorg) - 随机的。org客户端库。[！[板条箱徽章](https://img.shields.io/crates/v/randomorg.svg)](https://crates.io/crates/randomorg)
* [w3f/schnorrkel](https://github.com/w3f/schnorrkel) - Schnorr VRF和Ristretto组的签名

### Data processing

* [amv-dev/yata](https://github.com/amv-dev/yata) — 高性能技术分析库[！[构建状态](https://img.shields.io/github/workflow/status/amv-dev/yata/Rust?branch=master)](https://github.com/amv-dev/yata/actions?query=workflow%3ARust)
* [bluss/ndarray](https://github.com/rust-ndarray/ndarray) — 具有阵列视图、多维切片和高效操作的N维阵列
* [kernelmachine/utah](https://github.com/kernelmachine/utah) — Rust中的数据框架结构和操作
* [pola-rs/polars](https://github.com/pola-rs/polars) - 快速功能完整的DataFrame库！[构建和测试](https://github.com/pola-rs/polars/workflows/Build%20and%20test/badge.svg?branch=master)
* [weld-project/weld](https://github.com/weld-project/weld) — 数据分析应用程序的高性能运行时

### Data streaming

* [infinyon/fluvio](https://github.com/infinyon/fluvio) - 可编程数据流平台[！[CI](https://github.com/infinyon/fluvio/workflows/CI/badge.svg?branch=stable)](https://github.com/infinyon/fluvio/actions)

### Data structures

* [becheran/grid](https://github.com/becheran/grid) [[网格](https://crates.io/crates/grid)]-提供一个易于使用且快速的二维数据结构，用于防锈。[！[生成状态](https://github.com/becheran/grid/actions/workflows/rust.yml/badge.svg)](https://github.com/becheran/grid/actions)
* [billyevans/tst](https://github.com/billyevans/tst) [[tst](https://crates.io/crates/tst)]-三元搜索树集合[！[构建徽章](https://api.travis-ci.org/billyevans/tst.svg?branch=master)](https://travis-ci.org/billyevans/tst)
* [contain-rs](https://github.com/contain-rs) — Rust的std:：集合的扩展
* [danielpclark/array_tool](https://github.com/danielpclark/array_tool) — Rust的数组助手。在向量上提供的数组中使用的一些最常用的方法。用于处理大多数用例的多形态实现。[！[构建徽章](https://api.travis-ci.org/danielpclark/array_tool.svg?branch=master)](https://travis-ci.org/danielpclark/array_tool)
* [fizyk20/generic-array](https://github.com/fizyk20/generic-array) –允许按typenums[！[build badge]大小排列数组的黑客(https://api.travis-ci.org/fizyk20/generic-array.svg?branch=master)](https://travis-ci.org/fizyk20/generic-array)
* [garro95/priority-queue](https://github.com/garro95/priority-queue)[[priority-queue](https://crates.io/crates/priority-queue)] — A priority queue that implements priority changes. [![build badge](https://api.travis-ci.org/garro95/priority-queue.svg?branch=master)](https://travis-ci.org/garro95/priority-queue)
* [mrhooray/kdtree-rs](https://github.com/mrhooray/kdtree-rs) — Rust中的K维树用于快速地理空间索引和最近邻查找
* [orium/rpds](https://github.com/orium/rpds) [[转/分](https://crates.io/crates/rpds)]-Rust中的持久数据结构。[！[构建徽章](https://github.com/orium/rpds/workflows/CI/badge.svg)](https://github.com/orium/rpds/actions?query=workflow%3ACI)
* [RoaringBitmap/roaring-rs](https://github.com/RoaringBitmap/roaring-rs) –锈迹斑斑的位图
* [rust-itertools/itertools](https://github.com/rust-itertools/itertools) — [！[构建徽章](https://api.travis-ci.org/rust-itertools/itertools.svg?branch=master)](https://travis-ci.org/rust-itertools/itertools)
* [tnballo/scapegoat](https://github.com/tnballo/scapegoat) [[替罪羊](https://crates.io/crates/scapegoat)]-“BTreeSet”和“BTreeMap”的安全、易出错、仅堆栈选项。[！[GitHub操作](https://github.com/tnballo/scapegoat/workflows/test/badge.svg?branch=master)](https://github.com/tnballo/scapegoat/actions)
* [xfix/enum-map](https://github.com/xfix/enum-map) [[枚举映射](https://crates.io/crates/enum-map)]-使用数组存储值的枚举的优化映射实现。[！[构建徽章](https://api.travis-ci.org/xfix/enum-map.svg?branch=master)](https://travis-ci.org/xfix/enum-map)
* [yamafaktory/hypergraph](https://github.com/yamafaktory/hypergraph) [[超图](https://crates.io/crates/hypergraph)]-Hypergraph是生成有向超图的数据结构库。[！[ci](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml)

### Data visualization

* [djduque/pgfplots](https://github.com/djduque/pgfplots) [[pgfplots](https://crates.io/crates/pgfplots)]-生成出版物质量数据的Rust库。[！[构建](https://github.com/DJDuque/pgfplots/actions/workflows/rust.yml/badge.svg)](https://github.com/DJDuque/pgfplots/actions/workflows/rust.yml)
* [igiagkiozis/plotly](https://github.com/igiagkiozis/plotly) — 为Rust策划。
* [milliams/plotlib](https://github.com/milliams/plotlib) — [！[构建徽章](https://api.travis-ci.org/milliams/plotlib.svg?branch=master)](https://travis-ci.org/milliams/plotlib)
* [plotters](https://github.com/plotters-rs/plotters) — [！[构建徽章](https://github.com/plotters-rs/plotters/workflows/CI/badge.svg)](https://github.com/plotters-rs/plotters/actions)
* [saresend/gust](https://github.com/saresend/Gust) — [！[构建徽章](https://api.travis-ci.org/saresend/Gust.svg?branch=master)](https://travis-ci.org/saresend/Gust)

### Database

[[database](https://crates.io/keywords/database)]

* NoSQL [[nosql](https://crates.io/keywords/nosql)]

  * [ArangoDB](https://www.arangodb.com)
    * [Aragog](https://gitlab.com/qonfucius/aragog) [[阿拉戈格](https://crates.io/crates/aragog)]-轻量级ArangoDB对象文档、关系和图形映射器[！[pipeline status](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
    * [Arangors](https://github.com/fMeow/arangors) [[阿兰戈斯](https://crates.io/crates/arangors)]-Rust的ArangoDB驱动程序
  * [Cassandra](https://cassandra.apache.org/_/index.html) [[卡桑德拉](https://crates.io/keywords/cassandra)，[cql](https://crates.io/keywords/cql)]
    * [AlexPikalov/cdrs](https://github.com/AlexPikalov/cdrs) [[光盘](https://crates.io/crates/cdrs)]-使用Rust[！[build badge]编写的本机客户端(https://api.travis-ci.org/AlexPikalov/cdrs.svg?branch=master)](https://travis-ci.org/AlexPikalov/cdrs)
    * [krojew/cdrs-tokio](https://github.com/krojew/cdrs-tokio) [[cdrs东京](https://crates.io/crates/cdrs-tokio)]-生产就绪的异步Apache Cassandra驱动程序，用纯Rust[！[build badge]编写(https://github.com/krojew/cdrs-tokio/actions/workflows/rust.yml/badge.svg)](https://github.com/krojew/cdrs-tokio/actions)
    * [Metaswitch/cassandra-rs](https://github.com/Metaswitch/cassandra-rs) —  绑定到DataTax C/C++客户端[！[build badge](https://api.travis-ci.org/Metaswitch/cassandra-rs.svg?branch=master)](https://travis-ci.org/Metaswitch/cassandra-rs)
  * CouchDB [[couchdb](https://crates.io/keywords/couchdb)]
    * [chill-rs/chill](https://github.com/chill-rs/chill) [[沙发床](https://crates.io/crates/chill)]-CouchDB REST API的Rust客户端[！[build badge](https://api.travis-ci.org/chill-rs/chill.svg?branch=master)](https://travis-ci.org/chill-rs/chill)
  * [DynamoDB](https://aws.amazon.com/dynamodb/) [[发电机模块](https://crates.io/keywords/dynamodb)]
    * [softprops/dynomite](https://github.com/softprops/dynomite) - 一个用于与`rusoto_dynamodb`[！[build badge]进行强类型和方便交互的库(https://github.com/softprops/dynomite/workflows/Main/badge.svg?branch=master)](https://github.com/softprops/dynomite/actions)
  * Elasticsearch [[elasticsearch](https://crates.io/keywords/elasticsearch)]
    * [benashford/rs-es](https://github.com/benashford/rs-es) [秒](https://crates.io/crates/rs-es)]-[Elastic]的Rust客户端(https://www.elastic.co/)REST API[！[构建标记](https://api.travis-ci.org/benashford/rs-es.svg?branch=master)](https://travis-ci.org/benashford/rs-es)
    * [elastic-rs/elastic](https://github.com/elastic-rs/elastic) [[弹性](https://crates.io/crates/elastic)]-elastic是一个高效的模块化API客户端，用于使用Rust[！[build badge]编写的Elasticsearch(https://ci.appveyor.com/api/projects/status/csa78tcumdpnbur2?svg=true)](https://ci.appveyor.com/project/KodrAus/elastic)
  * etcd
    * [jimmycuadra/rust-etcd](https://github.com/jimmycuadra/rust-etcd) [[etcd](https://crates.io/crates/etcd)]-用于CoreOS etcd的客户端库。[！[构建徽章](https://api.travis-ci.org/jimmycuadra/rust-etcd.svg?branch=master)](https://travis-ci.org/jimmycuadra/rust-etcd)
    * [lodrem/etcd-rs](https://github.com/lodrem/etcd-rs) — 用于rust[！[CI]的异步etcd客户端(https://github.com/lodrem/etcd-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/lodrem/etcd-rs/actions/workflows/ci.yml)
  * ForestDB
    * [vhbit/sherwood](https://github.com/vhbit/sherwood) — [森林数据库](https://github.com/couchbase/forestdb)绑定[！[build badge](https://api.travis-ci.org/vhbit/sherwood.svg?branch=master)](https://travis-ci.org/vhbit/sherwood)
  * [InfluxDB](https://www.influxdata.com/)
    * [driftluo/InfluxDBClient-rs](https://github.com/driftluo/InfluxDBClient-rs) — 同步接口[！[build badge](https://api.travis-ci.org/driftluo/InfluxDBClient-rs.svg?branch=master)](https://travis-ci.org/driftluo/InfluxDBClient-rs)
  * LevelDB
    * [skade/leveldb](https://github.com/skade/leveldb) — [级别数据库](https://github.com/google/leveldb)绑定[！[build badge](https://api.travis-ci.org/skade/leveldb.svg?branch=master)](https://travis-ci.org/skade/leveldb)
  * LMDB [[lmdb](https://crates.io/keywords/lmdb)]
    * [vhbit/lmdb-rs](https://github.com/vhbit/lmdb-rs) [[lmdb-rs](https://crates.io/crates/lmdb-rs)]-[LMDB](https://www.symas.com/symas-embedded-database-lmdb)绑定[！[build badge](https://api.travis-ci.org/vhbit/lmdb-rs.svg?branch=master)](https://travis-ci.org/vhbit/lmdb-rs)
  * MongoDB [[mongodb](https://crates.io/keywords/mongodb)]
    * [mongodb/mongo-rust-driver](https://github.com/mongodb/mongo-rust-driver) [[蒙古](https://crates.io/crates/mongodb)]-[MongoDB](https://www.mongodb.com/)绑定
  * [PickleDB](https://pythonhosted.org/pickleDB/)
    * [seladb/pickledb-rs](https://github.com/seladb/pickledb-rs) — 一个轻量级、简单的键值存储，深受Python PickleDB的启发。[！[构建徽章](https://api.travis-ci.org/seladb/pickledb-rs.svg?branch=master)](https://travis-ci.org/seladb/pickledb-rs)
  * Redis [[redis](https://crates.io/keywords/redis)]
    * [aembke/fred](https://github.com/aembke/fred.rs) [[弗雷德](https://crates.io/crates/fred)]-高级异步[Redis](https://redis.io/)Tokio的Rust客户端。[！[CircleCI](https://circleci.com/gh/aembke/fred.rs/tree/main.svg?style=svg)]([https://circleci.com/gh/aembke/fred.rs/tree/main](https://app.circleci.com/pipelines/github/aembke/fred.rs?branch=main))
    * [redis-rs](https://github.com/redis-rs/redis-rs) — [Redis](https://redis.io/)Rust[！[Rust]中的库(https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml)
  * [RocksDB](https://rocksdb.org/)
    * [rust-rocksdb/rust-rocksdb](https://github.com/rust-rocksdb/rust-rocksdb) — RocksDB绑定[！[RocksDBCI](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml)
  * [SurrealDB](https://surrealdb.com/)
    * [surrealdb/surrealdb](https://github.com/surrealdb/surrealdb) — SurrealDB嵌入式文档图形数据库
  * [UnQLite](https://unqlite.org/)
    * [zitsen/unqlite.rs](https://github.com/zitsen/unqlite.rs) — UnQLite绑定[！[build badge](https://api.travis-ci.org/zitsen/unqlite.rs.svg?branch=master)](https://travis-ci.org/zitsen/unqlite.rs)
  * [ZooKeeper](https://zookeeper.apache.org/)
    * [bonifaido/rust-zookeeper](https://github.com/bonifaido/rust-zookeeper) [[动物园管理员](https://crates.io/crates/zookeeper)]-Apache ZooKeeper的客户端库。[！[构建徽章](https://api.travis-ci.org/bonifaido/rust-zookeeper.svg?branch=master)](https://travis-ci.org/bonifaido/rust-zookeeper)
    * [krojew/rust-zookeeper](https://github.com/krojew/rust-zookeeper) [[动物园管理员异步](https://crates.io/crates/zookeeper-async)]-Async Zookeeper客户端100%使用Rust编写，基于tokio！[生成状态](https://github.com/krojew/rust-zookeeper/actions/workflows/rust.yml/badge.svg)
* OGM [[ogm](https://crates.io/keywords/ogm)]
    * [Aragog](https://gitlab.com/qonfucius/aragog) [[阿拉戈格](https://crates.io/crates/aragog)]-轻量级ArangoDB对象文档、关系和图形映射器[！[pipeline status](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
* ORM [[orm](https://crates.io/keywords/orm)]
  * [Brendonovich/prisma-client-rust](https://github.com/Brendonovich/prisma-client-rust) — 一个自动生成的查询生成器，使用Prisma生态系统提供简单且完全类型安全的数据库访问。[！[测试状态](https://img.shields.io/github/workflow/status/Brendonovich/prisma-client-rust/CI?label=tests&style=flat-正方形）](https://github.com/Brendonovich/prisma-client-rust/actions)
  * [diesel-rs/diesel](https://github.com/diesel-rs/diesel) — Rust[！[Build Status]的ORM和查询生成器(https://api.travis-ci.org/diesel-rs/diesel.svg?branch=master)](https://travis-ci.org/diesel-rs/diesel)
  * [ivanceras/rustorm](https://github.com/ivanceras/rustorm) — Rust的ORM[！[Build Status](https://api.travis-ci.org/ivanceras/rustorm.svg?branch=master)](https://travis-ci.org/ivanceras/rustorm)
  * [rbatis/rbatis](https://github.com/rbatis/rbatis) — Rust ORM框架高性能（基于JSON）[！[构建状态](https://api.travis-ci.org/zhuxiujia/rbatis.svg?branch=master)](https://travis-ci.org/zhuxiujia/rbatis)
  * [SeaQL/sea-orm](https://github.com/SeaQL/sea-orm) — 🐚 Rust[！[Build Status]的异步动态ORM(https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml)
* [sfackler/r2d2](https://github.com/sfackler/r2d2) — 通用连接池[！[build badge](https://api.travis-ci.org/sfackler/r2d2.svg?branch=master)](https://travis-ci.org/sfackler/r2d2)
* SQL [[sql](https://crates.io/keywords/sql)]
  * Generic
    * [launchbadge/sqlx](https://github.com/launchbadge/sqlx) - 异步PostgreSQL/MSQL/SQLite连接池，具有强大的类型支持[！[build badge](https://img.shields.io/github/workflow/status/launchbadge/sqlx/Rust/master?style=flat-正方形）](https://github.com/launchbadge/sqlx)
    * [SeaQL/sea-query](https://github.com/SeaQL/sea-query) - 🔱 用于MySQL、Postgres和SQLite的动态SQL查询生成器[！[build status](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml)
    * [SeaQL/sea-schema](https://github.com/SeaQL/sea-schema) - 🌿 SQL架构管理套件[！[生成状态](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml)
  * Microsoft SQL
    * [prisma/tiberius](https://github.com/prisma/tiberius) — [！[货物测试](https://github.com/prisma/tiberius/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/prisma/tiberius/actions/workflows/test.yml)
  * MySql [[mysql](https://crates.io/keywords/mysql)]
    * [AgilData/mysql-proxy-rs](https://github.com/AgilData/mysql-proxy-rs) — MySQL代理[！[CircleCI](https://circleci.com/gh/AgilData/mysql-proxy-rs/tree/master.svg?style=svg)](https://app.circleci.com/pipelines/github/AgilData/mysql-proxy-rs?branch=master)
    * [blackbeam/mysql_async](https://github.com/blackbeam/mysql_async) [[mysql_async](https://crates.io/crates/mysql_async)]-基于Tokio的异步Rust Mysql驱动程序。[！[CircleCI](https://circleci.com/gh/blackbeam/mysql_async/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/blackbeam/mysql_async?branch=master)
    * [blackbeam/rust-mysql-simple](https://github.com/blackbeam/rust-mysql-simple) [[mysql](https://crates.io/crates/mysql)]-本机MySql客户端[！[build badge](https://api.travis-ci.org/blackbeam/rust-mysql-simple.svg?branch=master)](https://travis-ci.org/blackbeam/rust-mysql-simple)
  * PostgreSql [[postgres](https://crates.io/keywords/postgres), [postgresql](https://crates.io/keywords/postgresql)]
    * [sfackler/rust-postgres](https://github.com/sfackler/rust-postgres) [[帖子](https://crates.io/crates/postgres)]-本机[PostgreSQL](https://www.postgresql.org/)客户端[！[构建徽章](https://api.travis-ci.org/sfackler/rust-postgres.svg?branch=master)](https://travis-ci.org/sfackler/rust-postgres)
  * Sqlite [[sqlite](https://crates.io/keywords/sqlite)]
    * [rusqlite](https://github.com/rusqlite/rusqlite) — [方形3](https://www.sqlite.org/index.html)绑定[！[build badge](https://api.travis-ci.org/rusqlite/rusqlite.svg?branch=master)](https://travis-ci.org/rusqlite/rusqlite)

### Date and time

[[date](https://crates.io/keywords/date), [time](https://crates.io/keywords/time)]

* [chronotope/chrono](https://github.com/chronotope/chrono) — [！[构建徽章](https://api.travis-ci.org/chronotope/chrono.svg?branch=master)](https://travis-ci.org/chronotope/chrono)
* [Mnwa/ms](https://github.com/Mnwa/ms) [[ms转换器](https://crates.io/crates/ms-converter)]-这是一个将类人时间转换为毫秒的库[！[build badge](https://github.com/Mnwa/ms/workflows/build/badge.svg?branch=master)](https://github.com/Mnwa/ms/actions?query=workflow%3Abuild)
* [time-rs/time](https://github.com/time-rs/time) — [！[构建徽章](https://github.com/time-rs/time/workflows/Build/badge.svg)](https://github.com/time-rs/time/actions)

### Distributed systems

* Antimony
  * [antimonyproject/antimony](https://github.com/antimonyproject/antimony) [[锑](https://crates.io/crates/antimony)]-流处理/分布式计算平台[！[build badge](https://api.travis-ci.org/antimonyproject/antimony.svg?branch=master)](https://travis-ci.org/antimonyproject/antimony)
* Apache Kafka
  * [fede1024/rust-rdkafka](https://github.com/fede1024/rust-rdkafka) [[卡夫卡](https://crates.io/crates/rdkafka)]-[librdkafka](https://github.com/edenhill/librdkafka)绑定[！[build badge](https://api.travis-ci.org/fede1024/rust-rdkafka.svg?branch=master)](https://travis-ci.org/fede1024/rust-rdkafka)
  * [gklijs/schema_registry_converter](https://github.com/gklijs/schema_registry_converter) [[schema_registry_converter](https://crates.io/crates/schema_registry_converter)]-与[confluent schema registry]集成(https://www.confluent.io/product/confluent-platform/data-compatibility/)[！[构建徽章](https://api.travis-ci.org/gklijs/schema_registry_converter.svg?branch=master)](https://travis-ci.org/gklijs/schema_registry_converter)
  * [kafka-rust/kafka-rust](https://github.com/kafka-rust/kafka-rust) — [！[构建徽章](https://api.travis-ci.org/kafka-rust/kafka-rust.svg?branch=master)](https://travis-ci.org/kafka-rust/kafka-rust)
* Beanstalkd
  * [schickling/rust-beanstalkd](https://github.com/schickling/rust-beanstalkd) — [Beanstalkd](https://github.com/beanstalkd/beanstalkd)绑定[！[build badge](https://api.travis-ci.org/schickling/rust-beanstalkd.svg?branch=master)](https://travis-ci.org/schickling/rust-beanstalkd)
* HDFS
  * [hyunsik/hdfs-rs](https://github.com/hyunsik/hdfs-rs) [[hdfs](https://crates.io/crates/hdfs)]-libhdfs绑定

### Domain driven design

  * [serverlesstechnology/cqrs](https://github.com/serverlesstechnology/cqrs) [问题](https://crates.io/crates/cqrs-es)]-CQRS和事件源的框架，带有[用户指南](https://doc.rust-cqrs.org/)

### Email

[[email](https://crates.io/keywords/email), [imap](https://crates.io/keywords/imap), [smtp](https://crates.io/keywords/smtp)]

* [gsquire/sendgrid-rs](https://github.com/gsquire/sendgrid-rs) — SendGrid API的非官方Rust库[！[build badge](https://api.travis-ci.org/gsquire/sendgrid-rs.svg?branch=master)](https://travis-ci.org/gsquire/sendgrid-rs)
* [jdrouet/catapulte](https://github.com/jdrouet/catapulte) [![build badge](https://api.travis-ci.com/jdrouet/catapulte.svg?branch=main)](https://travis-ci.org/jdrouet/catapulte) - 使用[MRML]发送电子邮件的微服务(https://github.com/jdrouet/mrml)模板。
* [jdrouet/jolimail](https://github.com/jdrouet/jolimail) [![pipeline status](https://gitlab.com/jeremie.drouet/jolimail/badges/main/pipeline.svg)](https://gitlab.com/jeremie.drouet/jolimail/-/commits/main) - 要构建的web应用程序[MRML](https://github.com/jdrouet/mrml)模板。
* [jdrouet/mrml](https://github.com/jdrouet/mrml) [![build badge](https://api.travis-ci.com/jdrouet/mrml.svg?branch=master)](https://travis-ci.org/jdrouet/mrml) - 一个库，可以在任何邮件客户端上生成漂亮的电子邮件模板。
* [lettre/lettre](https://github.com/lettre/lettre) — Rust[！[CI]的SMTP库(https://github.com/lettre/lettre/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/lettre/lettre/actions/workflows/test.yml)
* [staktrace/mailparse](https://github.com/staktrace/mailparse) [[邮件解析](https://crates.io/crates/mailparse)]-用于解析真实世界电子邮件文件的库[！[build badge](https://api.travis-ci.org/staktrace/mailparse.svg?branch=master)](https://travis-ci.org/staktrace/mailparse)
* [stalwartlabs/mail-parser](https://github.com/stalwartlabs/mail-parser) [[邮件分析器](https://crates.io/crates/mail-parser)]-具有完整MIME支持的快速、健壮的电子邮件解析库[！[build badge](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml)
* [stalwartlabs/mail-send](https://github.com/stalwartlabs/mail-send) [[邮件发送](https://crates.io/crates/mail-send)]-支持DKIM的电子邮件生成器和SMTP客户端库[！[build badge](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml)

### Encoding

[[encoding](https://crates.io/keywords/encoding)]

* ASN.1
  * [alex/rust-asn1](https://github.com/alex/rust-asn1) — 锈ASN。1（DER）序列化程序[！[构建标记](https://api.travis-ci.org/alex/rust-asn1.svg?branch=master)](https://travis-ci.org/alex/rust-asn1)
* Binary
  * [bincode-org/bincode](https://github.com/bincode-org/bincode) — Rust[！[CI]中的二进制编码器/解码器(https://github.com/bincode-org/bincode/actions/workflows/rust.yml/badge.svg?branch=trunk)](https://github.com/bincode-org/bincode/actions/workflows/rust.yml)
  * [m4b/goblin](https://github.com/m4b/goblin) [[妖精](https://crates.io/crates/goblin)]-跨平台、零拷贝和支持endian的二进制解析[！[build badge](https://api.travis-ci.org/m4b/goblin.svg?branch=master)](https://travis-ci.org/m4b/goblin)
* BSON
  * [mongodb/bson-rust](https://github.com/mongodb/bson-rust) — Rust中对BSON的编码和解码支持
* Byte swapping
  * [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder) — 支持大端、小端和原生字节顺序[！[build badge](https://api.travis-ci.org/BurntSushi/byteorder.svg?branch=master)](https://travis-ci.org/BurntSushi/byteorder)
* Cap'n Proto
  * [capnproto/capnproto-rust](https://github.com/capnproto/capnproto-rust) — [！[构建徽章](https://api.travis-ci.org/capnproto/capnproto-rust.svg?branch=master)](https://travis-ci.org/capnproto/capnproto-rust)
* CBOR
  * [serde_cbor](https://crates.io/crates/serde_cbor) — CBOR对serde[！[build badge]的支持(https://api.travis-ci.org/pyfisch/cbor.svg?branch=master)](https://travis-ci.org/pyfisch/cbor)
* Character Encoding
  * [hsivonen/encoding_rs](https://github.com/hsivonen/encoding_rs) [[编码_rs](https://crates.io/crates/encoding_rs)]-Rust[！[build badge]中面向Gecko的编码标准实现(https://api.travis-ci.org/hsivonen/encoding_rs.svg?branch=master)](https://travis-ci.org/hsivonen/encoding_rs)
  * [lifthrasiir/rust-encoding](https://github.com/lifthrasiir/rust-encoding) — [！[构建徽章](https://api.travis-ci.org/lifthrasiir/rust-encoding.svg?branch=master)](https://travis-ci.org/lifthrasiir/rust-encoding)
* CRC
  * [mrhooray/crc-rs](https://github.com/mrhooray/crc-rs) — [！[构建徽章](https://api.travis-ci.org/mrhooray/crc-rs.svg?branch=master)](https://travis-ci.org/mrhooray/crc-rs)
* CSV
  * [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv) — 快速灵活的CSV读写器，支持Serde[！[build badge](https://api.travis-ci.org/BurntSushi/rust-csv.svg?branch=master)](https://travis-ci.org/BurntSushi/rust-csv)
* EDN
  * [naomijub/edn-rs](https://github.com/naomijub/edn-rs) [编辑](https://crates.io/crates/edn-rs)]-crate将EDN格式解析并发出为Rust类型。[！[生成状态]（https://api.travis-ci.org/naomijub/edn-rs.svg?branch=master)](https://travis-ci.org/naomijub/edn-rs)
* [FlatBuffers](https://google.github.io/flatbuffers/)
  * [frol/flatc-rust](https://github.com/frol/flatc-rust) — 用于Cargo构建脚本的FlatBuffers编译器（flatc）集成[！[build badge](https://api.travis-ci.org/frol/flatc-rust.svg?branch=master)](https://travis-ci.org/frol/flatc-rust)
* HAR
  * [mandrean/har-rs](https://github.com/mandrean/har-rs) [[哈尔](https://crates.io/crates/har)]-HTTP存档格式（HAR）序列化和反序列化库[！[Build Status](https://api.travis-ci.org/mandrean/har-rs.svg?branch=master)](https://travis-ci.org/mandrean/har-rs)
* HTML
  * [servo/html5ever](https://github.com/servo/html5ever) — 高性能浏览器级HTML5解析器[！[build badge](https://api.travis-ci.com/servo/html5ever.svg?branch=master)](https://travis-ci.org/servo/html5ever)
* JSON
  * [importcjj/rust-ajson](https://github.com/importcjj/rust-ajson) [[ajson]](https://crates.io/crates/ajson) —  快速获取JSON值[！[build badge](https://api.travis-ci.com/importcjj/rust-ajson.svg?branch=master)](https://app.travis-ci.com/github/importcjj/rust-ajson)
  * [maciejhirsz/json-rust](https://github.com/maciejhirsz/json-rust) [[简体](https://crates.io/crates/json)]-Rust[！[build badge]中的JSON实现(https://api.travis-ci.org/maciejhirsz/json-rust.svg?branch=master)](https://travis-ci.org/maciejhirsz/json-rust)
  * [pikkr/pikkr](https://github.com/pikkr/pikkr) [[皮克](https://crates.io/crates/pikkr)]-JSON解析器，直接获取值，而不在Rust中执行标记化
  * [serde-rs/json](https://github.com/serde-rs/json) [[序列号](https://crates.io/crates/serde_json)]-对[Serde]的JSON支持(https://github.com/serde-rs/serde)框架[！[构建徽章](https://api.travis-ci.org/serde-rs/json.svg?branch=master)](https://travis-ci.org/serde-rs/json)
  * [simd-lite/simd-json](https://github.com/simd-lite/simd-json) [[模拟json](https://crates.io/crates/simd-json)]-基于simdjson端口的高性能JSON解析器
* MsgPack
  * [3Hren/msgpack-rust](https://github.com/3Hren/msgpack-rust) — 纯Rust低/高级别MessagePack实现[！[build badge](https://api.travis-ci.org/3Hren/msgpack-rust.svg?branch=master)](https://travis-ci.org/3Hren/msgpack-rust)
* PEM
  * [jcreekmore/pem-rs](https://github.com/jcreekmore/pem-rs) [[佩姆](https://crates.io/crates/pem)]-基于Rust的解析和编码PEM编码数据的方法[！[build badge](https://api.travis-ci.org/jcreekmore/pem-rs.svg?branch=master)](https://travis-ci.org/jcreekmore/pem-rs)
* ProtocolBuffers
  * [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf) — [！[构建徽章](https://api.travis-ci.org/stepancheg/rust-protobuf.svg?branch=master)](https://travis-ci.org/stepancheg/rust-protobuf)
  * [tokio-rs/prost](https://github.com/tokio-rs/prost) — [！[持续集成](https://github.com/tokio-rs/prost/workflows/continuous%20integration/badge.svg?branch=master)](https://github.com/tokio-rs/prost/actions)
* RON (Rusty Object Notation)
  * [https://github.com/ron-rs/ron](https://github.com/ron-rs/ron) — [！[构建徽章](https://api.travis-ci.org/ron-rs/ron.svg?branch=master)](https://travis-ci.org/https://github.com/ron-秒/秒）
* Serde
  * [vityafx/serde-aux](https://github.com/vityafx/serde-aux/) - 用于serde库的其他工具。[！[CI](https://github.com/vityafx/serde-aux/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/serde-aux/actions/workflows/ci.yml)[！[板条箱徽章](https://img.shields.io/crates/v/serde-aux.svg)](https://crates.io/crates/serde-aux)
* TOML
  * [toml-rs/toml](https://github.com/toml-rs/toml) — [！[CI](https://github.com/toml-rs/toml/actions/workflows/ci.yml/badge.svg)](https://github.com/toml-rs/toml/actions/workflows/ci.yml)
* XML
  * [Florob/RustyXML](https://github.com/Florob/RustyXML) — 用Rust[！[build badge]编写的XML解析器(https://api.travis-ci.org/Florob/RustyXML.svg?branch=master)](https://travis-ci.org/Florob/RustyXML)
  * [media-io/yaserde](https://github.com/media-io/yaserde) — 另一个专门用于XML的序列化器/反序列化器[！[build badge](https://api.travis-ci.org/media-io/yaserde.svg?branch=master)](https://travis-ci.org/media-io/yaserde)
  * [netvl/xml-rs](https://github.com/netvl/xml-rs) — 流式XML库[！[build badge](https://api.travis-ci.org/netvl/xml-rs.svg?branch=master)](https://travis-ci.org/netvl/xml-rs)
  * [shepmaster/sxd-document](https://github.com/shepmaster/sxd-document) — Rust[！[build badge]中的XML库(https://api.travis-ci.org/shepmaster/sxd-document.svg?branch=master)](https://travis-ci.org/shepmaster/sxd-document)
  * [shepmaster/sxd-xpath](https://github.com/shepmaster/sxd-xpath) — Rust[！[build badge]中的XPath库(https://api.travis-ci.org/shepmaster/sxd-xpath.svg?branch=master)](https://travis-ci.org/shepmaster/sxd-xpath)
  * [tafia/quick-xml](https://github.com/tafia/quick-xml) — 高性能XML拉式读取器/写入器[！[build badge](https://api.travis-ci.org/tafia/quick-xml.svg?branch=master)](https://travis-ci.org/tafia/quick-xml)
* YAML
  * [chyh1990/yaml-rust](https://github.com/chyh1990/yaml-rust) — Rust缺少YAML 1.2实现。[！[构建徽章](https://api.travis-ci.org/chyh1990/yaml-rust.svg?branch=master)](https://travis-ci.org/chyh1990/yaml-rust)
  * [dtolnay/serde-yaml](https://github.com/dtolnay/serde-yaml) [[serde\_yaml](https://crates.io/crates/serde_yaml)]-对[Serde]的YAML支持(https://github.com/serde-rs/serde)框架[！[构建](https://img.shields.io/github/workflow/status/dtolnay/serde-yaml/CI/master)](https://github.com/dtolnay/serde-yaml/actions?query=branch%3Amaster)
  * [vitiral/stfu8](https://github.com/vitiral/stfu8) [[stfu8](https://crates.io/crates/stfu8)]-以UTF-8[！[build badge]排序文本格式(https://api.travis-ci.org/vitiral/stfu8.svg?branch=master)](https://travis-ci.org/vitiral/stfu8)

### Filesystem

[[filesystem](https://crates.io/keywords/filesystem)]
* Operations
  * [pop-os/dbus-udisks2](https://github.com/pop-os/dbus-udisks2) [[数据库-磁盘2](https://crates.io/crates/dbus-udisks2)]-UDisks2 DBus API
  * [pop-os/sys-mount](https://github.com/pop-os/sys-mount) [[系统安装](https://crates.io/crates/sys-mount)]-“mount”/“umount2”系统调用的高级抽象。
  * [vitiral/path_abs](https://github.com/vitiral/path_abs) [[路径_abs](https://crates.io/crates/path_abs)]-绝对可序列化路径类型和关联方法。[！[构建徽章](https://api.travis-ci.org/vitiral/path_abs.svg?branch=master)](https://travis-ci.org/webdesus/fs_extr://travis-ci.org/vitiral/path_abs）
  * [webdesus/fs_extra](https://github.com/webdesus/fs_extra) — 扩展机会标准库std:：fs和std::io[！[build badge](https://api.travis-ci.org/webdesus/fs_extra.svg?branch=master)](https://travis-ci.org/webdesus/fs_extra)
* Temporary Files
  * [Stebalien/tempfile](https://github.com/Stebalien/tempfile) — 临时文件库[！[build badge](https://api.travis-ci.org/Stebalien/tempfile.svg?branch=master)](https://travis-ci.org/Stebalien/tempfile)
  * [Stebalien/xattr](https://github.com/Stebalien/xattr) [[xattr](https://crates.io/crates/xattr)]-列出并操作unix扩展文件属性[！[build badge](https://api.travis-ci.org/Stebalien/xattr.svg?branch=master)](https://travis-ci.org/Stebalien/xattr)
  * [zboxfs/zbox](https://github.com/zboxfs/zbox) [[邮箱](https://crates.io/crates/zbox)]-零细节、注重隐私的嵌入式文件系统。[！[构建徽章](https://api.travis-ci.org/zboxfs/zbox.svg?branch=master)](https://travis-ci.org/zboxfs/zbox)

### Functional Programming

[[functional programming](https://crates.io/keywords/fp)]
* Prelude
  * [JasonShin/fp-core.rs](https://github.com/JasonShin/fp-core.rs) — Rust中的函数编程库
  * [myrrlyn/tap](https://github.com/myrrlyn/tap) - 后缀位置管道行为

### Game development

See also [Are we game yet?](https://arewegameyet.rs)
* Allegro
  * [SiegeLord/RustAllegro](https://github.com/SiegeLord/RustAllegro) — [快板5](https://liballeg.org/)绑定[！[build badge](https://api.travis-ci.org/SiegeLord/RustAllegro.svg?branch=master)](https://travis-ci.org/SiegeLord/RustAllegro)
* [Awesome Quads](https://github.com/ozkriff/awesome-quads) — 指向miniquad/macroquad相关代码和资源的链接列表
* [Awesome wgpu](https://github.com/rofrol/awesome-wgpu) — wgpu代码和资源的整理列表
* bracket-lib (previously RLTK)
  * [bracket-lib](https://github.com/amethyst/bracket-lib) [[括号lib](https://crates.io/crates/bracket-lib)]-为Rust实现的Roguelike工具包（RLTK）。[！[锈](https://github.com/amethyst/bracket-lib/actions/workflows/rust.yml/badge.svg)](https://github.com/amethyst/bracket-lib/actions/workflows/rust.yml)
* Challonge
  * [vityafx/challonge-rs](https://github.com/vityafx/challonge-rs) [[查隆格](https://crates.io/crates/challonge)]-Challonge REST API的客户端库。帮助组织锦标赛。[！[CI](https://github.com/vityafx/challonge-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/challonge-rs/actions/workflows/ci.yml)
* Corange
  * [lucidscape/corange-rs](https://github.com/lucidscape/corange-rs) — [Corange](https://github.com/orangeduck/Corange)绑定
* Entity-Component Systems (ECS)
  * [amethyst/specs](https://github.com/amethyst/specs) — 规范并行ECS[！[build badge](https://api.travis-ci.org/amethyst/specs.svg?branch=master)](https://travis-ci.org/amethyst/specs)
  * [legion](https://github.com/amethyst/legion) — 一个功能丰富的高性能ECS库，具有最小的样板[！[build badge](https://github.com/amethyst/legion/workflows/CI/badge.svg?branch=master)](https://github.com/amethyst/legion/actions)
* Game Engines
  * [Bevy](https://github.com/bevyengine/bevy) 是一个在Rust中构建的刷新简单的数据驱动游戏引擎。-[！[板条箱.io](https://img.shields.io/crates/v/bevy.svg)](https://crates.io/crates/bevy)
[![Crates.io](https://img.shields.io/crates/d/bevy.svg)](https://crates.io/crates/bevy)
  * [Fyrox](https://fyrox.rs/) — Rust游戏引擎3D[！[Crates.io](https://img.shields.io/crates/v/fyrox.svg)](https://crates.io/crates/fyrox)[！[许可证](https://img.shields.io/crates/l/fyrox.svg)](https://github.com/FyroxEngine/Fyrox/blob/master/LICENSE.md)[！[板条箱.io](https://img.shields.io/crates/d/fyrox.svg)](https://crates.io/crates/fyrox)
  * [ggez](https://github.com/ggez/ggez) — 一个轻量级游戏框架，用于以最小的摩擦制作2D游戏-[！[Crates.io](https://img.shields.io/crates/v/ggez.svg)](https://crates.io/crates/ggez)[！[许可证](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ggez/ggez/blob/master/LICENSE)[！[板条箱.io](https://img.shields.io/crates/d/ggez.svg)](https://crates.io/crates/ggez)
  * [Kiss3d](http://kiss3d.org) — 用Rust[！[Crates.io]编写的保持简单、愚蠢的3d图形引擎(https://img.shields.io/crates/d/kiss3d.svg)](https://crates.io/crates/kiss3d)
  * [oxidator](https://github.com/Ruddle/oxidator) — 用Rust和WebGPU编写的实时战略游戏/引擎
  * [Piston](https://www.piston.rs/) — [！[板条箱.io](https://img.shields.io/crates/v/piston.svg?style=flat-正方形）](https://crates.io/crates/piston)[！[板条箱.io](https://img.shields.io/crates/l/piston.svg)](https://github.com/PistonDevelopers/piston/blob/master/LICENSE)[！[板条箱.io](https://img.shields.io/crates/d/piston.svg)](https://crates.io/crates/piston)
  * [Unrust](https://github.com/unrust/unrust) — unrust-一个纯粹的基于rust的（webgl 2.0/原生）游戏引擎
* [Godot](https://godotengine.org/)
  * [godot-rust/godot-rust](https://github.com/godot-rust/godot-rust) [[gdnative](https://crates.io/crates/gdnative)]-Godot游戏引擎的Rust绑定[！[CI](https://github.com/godot-rust/godot-rust/actions/workflows/full-ci.yml/badge.svg)](https://github.com/godot-rust/godot-rust/actions/workflows/full-ci.yml)
* [Raylib](https://www.raylib.com/)
  * [deltaphc/raylib-rs](https://github.com/deltaphc/raylib-rs) [[射线库](https://crates.io/crates/raylib)]-raylib的Rust绑定
* [SDL](http://www.libsdl.org/) [[sdl](https://crates.io/keywords/sdl)]
  * [brson/rust-sdl](https://github.com/brson/rust-sdl) — SDL1绑定[！[build badge](https://api.travis-ci.org/brson/rust-sdl.svg?branch=master)](https://travis-ci.org/brson/rust-sdl)
  * [Rust-SDL2/rust-sdl2](https://github.com/Rust-SDL2/rust-sdl2) — SDL2绑定[！[build badge](https://api.travis-ci.org/Rust-SDL2/rust-sdl2.svg?branch=master)](https://travis-ci.org/Rust-SDL2/rust-sdl2)
* SFML
  * [jeremyletang/rust-sfml](https://github.com/jeremyletang/rust-sfml) — [SFML](https://www.sfml-dev.org/)绑定
* Tcod-rs
  * [tomassedovic/tcod-rs](https://github.com/tomassedovic/tcod-rs) — Rust的Libtcod绑定。
  * Warning: Not maintained anymore
* Toornament-rs
  * [vityafx/toornament-rs](https://github.com/vityafx/toornament-rs) - 装饰。com API绑定。[！[CI](https://github.com/vityafx/toornament-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/toornament-rs/actions/workflows/ci.yml)[！[板条箱徽章](https://img.shields.io/crates/v/toornament.svg)](https://crates.io/crates/toornament)
* Victorem
  * [VictoremWinbringer/Victorem](https://github.com/VictoremWinbringer/Victorem) [[维克多姆](https://crates.io/crates/Victorem)]-简单的UDP游戏服务器和UDP客户端框架，用于创建简单的2D和3D在线游戏原型[！[build badge](https://api.travis-ci.org/VictoremWinbringer/Victorem.svg?branch=master)](https://travis-ci.org/VictoremWinbringer/Victorem)

### Geospatial

[[geo](https://crates.io/keywords/geo), [gis](https://crates.io/keywords/gis)]

* [DaveKram/coord_transforms](https://github.com/DaveKram/coord_transforms) [[坐标变换](https://crates.io/crates/coord_transforms)]-坐标变换（二维、三维和地理空间）[！[build badge](https://api.travis-ci.org/DaveKram/coord_transforms.svg?branch=master)](https://travis-ci.org/DaveKram/coord_transforms)
* [Georust](https://github.com/georust) — 用Rust编写的地理空间工具和库
* [rust-reverse-geocoder](https://github.com/gx0r/rrgeo) — Rust中的快速离线反向地理编码器，灵感来自[thampiman/reverse geocoder](https://github.com/thampiman/reverse-geocoder)
* [vlopes11/geomorph](https://github.com/vlopes11/geomorph) [[地貌](https://crates.io/crates/geomorph)]-UTM、LatLon和MGRS坐标之间的转换[！[build badge](https://api.travis-ci.org/vlopes11/geomorph.svg?branch=master)](https://travis-ci.org/vlopes11/geomorph)

### Graphics

[[graphics](https://crates.io/keywords/graphics)]

* Font
  * [RazrFalcon/rustybuzz](https://github.com/RazrFalcon/rustybuzz) - Rust[！[build badge]的增量harfbuzz端口(https://api.travis-ci.org/RazrFalcon/rustybuzz.svg?branch=master)](https://travis-ci.org/RazrFalcon/rustybuzz)
  * [redox-os/rusttype](https://github.com/redox-os/rusttype) — 像FreeType[！[build badge]这样的库的纯Rust替代品(https://api.travis-ci.org/redox-os/rusttype.svg?branch=master)](https://travis-ci.org/redox-os/rusttype)
* [gfx-rs/gfx](https://github.com/gfx-rs/gfx) — Rust的高性能无绑定图形API。[！[构建徽章](https://api.travis-ci.org/gfx-rs/gfx.svg?branch=master)](https://travis-ci.org/gfx-rs/gfx)
* [gfx-rs/wgpu](https://github.com/gfx-rs/wgpu) - 基于gfx hal的本地WebGPU实现。[！[构建徽章](https://github.com/gfx-rs/wgpu/workflows/CI/badge.svg?branch=master)](https://github.com/gfx-rs/wgpu/actions)
* OpenGL [[opengl](https://crates.io/keywords/opengl)]
  * [brendanzab/gl-rs](https://github.com/brendanzab/gl-rs) — [！[构建徽章](https://api.travis-ci.org/brendanzab/gl-rs.svg?branch=master)](https://travis-ci.org/brendanzab/gl-rs)
  * [glium/glium](https://github.com/glium/glium) — Rust语言的安全OpenGL包装。[！[构建徽章](https://api.travis-ci.org/glium/glium.svg?branch=master)](https://travis-ci.org/glium/glium)
  * [glutin](https://crates.io/crates/glutin) — [GLFW]的防锈替代品(https://www.glfw.org/)[！[构建徽章](https://api.travis-ci.org/rust-windowing/glutin.svg?branch=master)](https://travis-ci.org/rust-windowing/glutin)
  * [Kiss3d](http://kiss3d.org) — 绘制简单的几何图形，并用一行文字进行游戏[！[build badge](https://api.travis-ci.org/sebcrozet/kiss3d.svg?branch=master)](https://api.travis-ci.org/repositories/sebcrozet/kiss3d)
  * [PistonDevelopers/glfw-rs](https://github.com/PistonDevelopers/glfw-rs) — [！[构建徽章](https://api.travis-ci.org/PistonDevelopers/glfw-rs.svg?branch=master)](https://travis-ci.org/PistonDevelopers/glfw-rs)
* PDF
  * [fschutt/printpdf](https://github.com/fschutt/printpdf) — PDF写作库[！[build badge](https://api.travis-ci.org/fschutt/printpdf.svg?branch=master)](https://travis-ci.org/fschutt/printpdf)
  * [J-F-Liu/lopdf](https://github.com/J-F-Liu/lopdf) — PDF文档操作[！[build badge](https://api.travis-ci.org/J-F-Liu/lopdf.svg?branch=master)](https://travis-ci.org/J-F-Liu/lopdf)
  * [kaj/rust-pdf](https://github.com/kaj/rust-pdf) — [！[构建徽章](https://api.travis-ci.org/kaj/rust-pdf.svg?branch=master)](https://travis-ci.org/kaj/rust-pdf)
  * [WASM-PDF](https://github.com/jussiniinikoski/wasm-pdf) –使用JavaScript和WASM（WebAssembly）生成PDF文件[！[build badge](https://api.travis-ci.org/jussiniinikoski/wasm-pdf.svg?branch=master)](https://travis-ci.org/jussiniinikoski/wasm-pdf)
* [Vulkan](https://www.vulkan.org/) [[乌尔坎](https://crates.io/keywords/vulkan)]
  * [erupt](https://gitlab.com/Friz64/erupt) [[爆发](https://crates.io/crates/erupt)]-[！[构建徽章](https://gitlab.com/Friz64/erupt/badges/main/pipeline.svg)](https://gitlab.com/Friz64/erupt/-/pipelines)
  * [vulkano](https://github.com/vulkano-rs/vulkano) [[乌尔卡诺](https://crates.io/crates/vulkano)]-[！[构建徽章](https://api.travis-ci.org/vulkano-rs/vulkano.svg?branch=master)](https://travis-ci.org/vulkano-rs/vulkano)

### GUI

[[gui](https://crates.io/keywords/gui)]

* [autopilot-rs/autopilot-rs](https://github.com/autopilot-rs/autopilot-rs) — Rust的一个简单的跨平台GUI自动化库。
* Cocoa
  * [servo/core-foundation-rs](https://github.com/servo/core-foundation-rs) — [！[构建徽章](https://api.travis-ci.com/servo/core-foundation-rs.svg?branch=master)](https://travis-ci.org/servo/core-foundation-rs)
* [DioxusLabs/dioxus](https://github.com/dioxuslabs/dioxus) - 一个可移植的、高性能的、符合人体工程学的框架，用于在Rust中构建跨平台用户界面！[锈ci](https://github.com/dioxuslabs/dioxus/actions/workflows/main.yml/badge.svg)
* [Druid](https://github.com/linebender/druid) [[德鲁伊](https://crates.io/crates/druid)]-[德鲁伊](https://linebender.org/druid/)，一个数据优先的原生UI设计工具包。[！[构建徽章](https://github.com/linebender/druid/workflows/.github/workflows/ci.yml/badge.svg)](https://github.com/linebender/druid/actions)
* [emilk/egui](https://github.com/emilk/egui) - Rust的简单、快速、高度可移植的即时模式GUI库。egui在web上运行，本机运行，并在您最喜欢的游戏引擎中运行。[！[生成状态](https://github.com/emilk/egui/workflows/CI/badge.svg)](https://github.com/emilk/egui/actions?workflow=CI)
* [emoon/rust_minifb](https://github.com/emoon/rust_minifb) — minifb是一个具有可选位图渲染的跨平台窗口设置。它还配有简单的鼠标和键盘输入。主要为原型设计
* [FLTK](https://www.fltk.org/)
  * [fltk-rs](https://github.com/fltk-rs/fltk-rs) — FLTK Rust绑定[！[Build](https://github.com/fltk-rs/fltk-rs/workflows/Build/badge.svg?branch=master)](https://github.com/fltk-rs/fltk-rs/actions)
* [Flutter](https://flutter.dev/)
  * [flutter-rs](https://github.com/flutter-rs/flutter-rs) — 在dart&rust中构建flutter桌面应用程序。
* [fschutt/azul](https://github.com/fschutt/azul) — 一个免费的、功能性的、面向IMGUI的GUI框架，用于快速开发用Rust编写的桌面应用程序，由Mozilla WebRender渲染引擎支持。[！[构建徽章](https://api.travis-ci.org/fschutt/azul.svg?branch=master)](https://travis-ci.org/fschutt/azul)
* [GTK+](https://www.gtk.org/) [[gtk](https://crates.io/keywords/gtk)]
  * [gtk-rs/gtk3-rs](https://github.com/gtk-rs/gtk3-rs) - GTK3生锈绑定！【CI】(https://github.com/gtk-rs/gtk3-rs/workflows/CI/badge.svg)
  * [relm](https://github.com/antoyo/relm) — 异步、基于GTK+的GUI库，灵感来自Elm[！[build badge](https://api.travis-ci.org/antoyo/relm.svg?branch=master)](https://travis-ci.org/antoyo/relm)
* [iced-rs/iced](https://github.com/iced-rs/iced) [[冰](https://crates.io/crates/iced)]-Rust的跨平台GUI库侧重于简单性和类型安全性。灵感来自Elm。
* [ImGui](https://github.com/ocornut/imgui)
  * [imgui-rs](https://github.com/imgui-rs/imgui-rs) — ImGui[！[Build Status]的Rust绑定(https://github.com/imgui-rs/imgui-rs/workflows/ci/badge.svg?branch=master)](https://github.com/imgui-rs/imgui-rs/actions)
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/)
  * [Kiss-ui](https://github.com/KISS-UI/kiss-ui) — 基于IUP[！[Build Status]构建的简单UI框架(https://api.travis-ci.org/cybergeek94/kiss-ui.svg?branch=master)](https://travis-ci.org/cybergeek94/kiss-ui)
* [ivanceras/sauron-native](https://github.com/ivanceras/sauron-native) - 真正的本地和跨平台GUI库。一个统一的代码可以作为本地GUI、Html Web和TUI运行。[！[生成状态](https://api.travis-ci.com/ivanceras/sauron-native.svg?branch=master)](https://app.travis-ci.com/github/ivanceras/sauron-native)
* [libui](https://github.com/andlabs/libui)
  * [rust-native-ui/libui-rs](https://github.com/rust-native-ui/libui-rs) — libui绑定[！[build badge](https://api.travis-ci.org/rust-native-ui/libui-rs.svg?branch=master)](https://travis-ci.org/rust-native-ui/libui-rs).
* [Nuklear](https://github.com/Immediate-Mode-UI/Nuklear)
  * [nuklear-rust](https://github.com/snuk182/nuklear-rust) — Nuklear的Rust绑定
* [OrbTk](https://github.com/redox-os/orbtk) — Orbital Widget Toolkit是一个使用SDL2[！[Build and test]的多平台（G）UI工具包(https://github.com/redox-os/orbtk/workflows/build/badge.svg?branch=develop)](https://github.com/redox-os/orbtk/actions)
* [PistonDevelopers/conrod](https://github.com/PistonDevelopers/conrod/) — 一个简单易用的即时模式2D GUI库，完全用Rust[！[build badge]编写(https://api.travis-ci.org/PistonDevelopers/conrod.svg?branch=master)](https://travis-ci.org/PistonDevelopers/conrod)
* [Qt](https://doc.qt.io)
  * [cyndis/qmlrs](https://github.com/cyndis/qmlrs) — QtQuick绑定[！[build badge](https://api.travis-ci.org/cyndis/qmlrs.svg?branch=master)](https://travis-ci.org/cyndis/qmlrs)
  * [rust-qt](https://github.com/rust-qt)
  * [woboq/qmetaobject-rs](https://github.com/woboq/qmetaobject-rs) — 通过在编译时构建QMetaObject来集成Qml和Rust。[！[构建徽章](https://api.travis-ci.org/woboq/qmetaobject-rs.svg?branch=master)](https://travis-ci.org/woboq/qmetaobject-rs)
* [rise-ui](https://github.com/rise-ui/rise) — 简单的基于组件的跨平台GUI工具包，用于开发美观且用户友好的界面。
* [saurvs/nfd-rs](https://github.com/saurvs/nfd-rs) — [本机文件对话框](https://github.com/mlabbe/nativefiledialog)绑定
* [Sciter](https://sciter.com/)
  * [sciter-sdk/rust-sciter](https://github.com/sciter-sdk/rust-sciter) — Sciter绑定[！[build badge](https://ci.appveyor.com/api/projects/status/github/sciter-sdk/rust-sciter?svg=true)](https://ci.appveyor.com/project/sciter-sdk/rust-sciter)
* [slint-ui/slint](https://github.com/slint-ui/slint) [[斜视](https://crates.io/crates/slint)]-[细长](https://slint-ui.com)是一个工具包，可以有效地为嵌入式设备和桌面应用程序开发流畅的图形用户界面。[！[生成状态](https://github.com/slint-ui/slint/workflows/CI/badge.svg?branch=master)](https://github.com/slint-ui/slint/actions?query=workflow%3ACI)
* [tauri-apps/tauri](https://github.com/tauri-apps/tauri) — 使用web前端构建更小、更快、更安全的桌面应用程序，由[WRY]提供支持(https://github.com/tauri-apps/wry). [！[测试库](https://img.shields.io/github/workflow/status/tauri-apps/tauri/test%20library?label=test%20library)](https://github.com/tauri-apps/tauri/actions?query=workflow%3A%22test+库%22）
* [tauri-apps/wry](https://github.com/tauri-apps/wry) - Webview渲染库Y。

### Image processing

* [abonander/img_hash](https://github.com/abonander/img_hash) — 感知图像散列和比较以获得相等性和相似性。[！[生成状态](https://api.travis-ci.org/abonander/img_hash.svg?branch=master)](https://travis-ci.org/abonander/img_hash)
* [image-rs/image](https://github.com/image-rs/image) — 基本成像处理功能和转换图像格式的方法[！[build badge](https://api.travis-ci.org/image-rs/image.svg?branch=master)](https://travis-ci.org/image-rs/image)
* [image-rs/imageproc](https://github.com/image-rs/imageproc) — 基于“图像”库的图像处理库。[！[生成状态](https://api.travis-ci.org/image-rs/imageproc.svg?branch=master)](https://travis-ci.org/image-rs/imageproc)
* [rust-cv/cv](https://github.com/rust-cv/cv) — Rust CV是一个在Rust中实现计算机视觉算法、抽象和系统的项目#尽可能支持[no_std]！[构建徽章](https://github.com/rust-cv/cv/workflows/tests/badge.svg)
* [teovoinea/steganography](https://github.com/teovoinea/steganography) [[隐写术](https://crates.io/crates/steganography)]-一个简单的隐写库[！[build badge](https://api.travis-ci.org/teovoinea/steganography.svg?branch=master)](https://travis-ci.org/teovoinea/steganography)
* [twistedfall/opencv-rust](https://github.com/twistedfall/opencv-rust) — OpenCV[！[build badge]的Rust绑定(https://api.travis-ci.org/twistedfall/opencv-rust.svg?branch=cv2)](https://travis-ci.org/twistedfall/opencv-rust)

### Language specification

* [shnewto/bnf](https://github.com/shnewto/bnf) — 用于解析Backus–Naur形式的上下文无关语法的库。[！[构建徽章](https://api.travis-ci.org/shnewto/bnf.svg?branch=master)](https://travis-ci.org/shnewto/bnf)

### Logging

[[log](https://crates.io/keywords/log)]

* [estk/log4rs](https://github.com/estk/log4rs) — 高度可配置的日志框架，以Java的Logback和log4j库[！[CircleCI]为模型(https://circleci.com/gh/estk/log4rs.svg?style=shield)](https://app.circleci.com/pipelines/github/estk/log4rs)
* [jesusprubio/leg](https://github.com/jesusprubio/leg) — 优雅印花，适合懒惰的开发人员。用最小的努力让你的CLI变得更好。[！[生成状态](https://github.com/jesusprubio/leg/workflows/CI/badge.svg)](https://github.com/jesusprubio/leg/actions/workflows/ci.yml)
* [rbatis/fast_log](https://github.com/rbatis/fast_log) — Rust异步日志高性能异步日志[！[Build Status](https://api.travis-ci.com/rbatis/fast_log.svg?branch=master)](https://travis-ci.org/rbatis/fast_log)
* [rust-lang/log](https://github.com/rust-lang/log) — Rust[！[Build Status]的日志记录实现(https://api.travis-ci.org/rust-lang/log.svg?branch=master)](https://travis-ci.org/rust-lang/log)
* [seanmonstar/pretty-env-logger](https://github.com/seanmonstar/pretty-env-logger) — 一个漂亮、易于使用的Rust记录器。[！[生成状态](https://api.travis-ci.org/seanmonstar/pretty-env-logger.svg?branch=master)](https://travis-ci.org/seanmonstar/pretty-env-logger)
* [slog-rs/slog](https://github.com/slog-rs/slog) — Rust[！[Build Status]的结构化、可组合日志记录(https://api.travis-ci.org/slog-rs/slog.svg?branch=master)](https://travis-ci.org/slog-rs/slog)
* [tokio-rs/tracing](https://github.com/tokio-rs/tracing) — 用于异步感知结构化日志、错误处理、度量等的应用程序级跟踪框架[！[Build Status](https://github.com/tokio-rs/tracing/workflows/CI/badge.svg?branch=master)](https://github.com/tokio-rs/tracing/actions?query=workflow%3ACI)

### Macro

* cute
  * [mattgathu/cute](https://github.com/mattgathu/cute) — Rust中用于Python式列表理解的宏。[！[生成状态](https://api.travis-ci.org/mattgathu/cute.svg?branch=master)](https://travis-ci.org/tensorflow/rust)
* [Linq-in-Rust](https://github.com/StardustDL/Linq-in-Rust) - C#-LINQ类表达式的宏和方法。[！[CI](https://github.com/StardustDL/Linq-in-Rust/workflows/CI/badge.svg?branch=master)](https://github.com/StardustDL/Linq-in-Rust/actions?query=workflow%3ACI)

### Markup language

* CommonMark
  * [raphlinus/pulldown-cmark](https://github.com/raphlinus/pulldown-cmark) — [通用标记](https://commonmark.org/)Rust中的解析器

### Mobile

* Android / iOS
  * [ivanschuetz/rust_android_ios](https://github.com/ivanschuetz/rust_android_ios) — 分别使用Rust swig和cbindgen为Android和iOS使用共享Rust lib的示例。
* Generic
  * [Geal/rust_on_mobile](https://github.com/Geal/rust_on_mobile)
* iOS
  * [TimNN/cargo-lipo](https://github.com/TimNN/cargo-lipo) — cargo lipo子命令，它自动创建一个通用库，用于iOS应用程序。[！[构建徽章](https://api.travis-ci.org/TimNN/cargo-lipo.svg?branch=master)](https://travis-ci.org/TimNN/cargo-lipo)

### Network programming

* Bluetooth
  * [bluez/bluer](https://github.com/bluez/bluer) [[更蓝](https://crates.io/crates/bluer)]-Rust的官方BlueZ绑定。[！[构建徽章](https://github.com/bluez/bluer/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/bluez/bluer/actions/workflows/rust.yml)
* CoAP
  * [Covertness/coap-rs](https://github.com/Covertness/coap-rs) — A[受限应用协议（CoAP）](https://datatracker.ietf.org/doc/html/rfc7252)Rust的库。[！[构建徽章](https://api.travis-ci.org/Covertness/coap-rs.svg?branch=master)](https://travis-ci.org/Covertness/coap-rs)
* Docker
  * [fussybeaver/bollard](https://github.com/fussybeaver/bollard) — Rust中的Docker守护程序API
* FTP
  * [mattnenterprise/rust-ftp](https://github.com/mattnenterprise/rust-ftp) — 一个[FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol)Rust[！[build badge]客户端(https://api.travis-ci.org/mattnenterprise/rust-ftp.svg?branch=master)](https://travis-ci.org/mattnenterprise/rust-ftp)
* gRPC
  * [tikv/grpc-rs](https://github.com/tikv/grpc-rs) — Rust的gRPC库基于C核心库和未来[！[Build Status](https://api.travis-ci.org/tikv/grpc-rs.svg?branch=master)](https://travis-ci.org/tikv/grpc-rs)
* HTTP
  * [Hurl](https://github.com/Orange-OpenSource/hurl) — 使用纯文本和libcurl[！[CI]运行和测试HTTP请求(https://github.com/Orange-OpenSource/hurl/workflows/CI/badge.svg)](https://github.com/Orange-OpenSource/hurl/actions)
* IPNetwork
  * [achanda/ipnetwork](https://github.com/achanda/ipnetwork) — 一个在纯Rust中使用IP网络的库[！[build badge](https://api.travis-ci.org/achanda/ipnetwork.svg?branch=master)](https://travis-ci.org/achanda/ipnetwork)
  * [candrew/netsim](https://github.com/canndrew/netsim) — 用于网络模拟和测试的Rust库[！[build badge](https://api.travis-ci.org/canndrew/netsim.svg?branch=master)](https://travis-ci.org/canndrew/netsim)
  * [jesusprubio/online](https://github.com/jesusprubio/online) — 图书馆检查您的互联网连接[！[CI](https://github.com/jesusprubio/online/actions/workflows/ci.yml/badge.svg)](https://github.com/jesusprubio/online/actions/workflows/ci.yml)
* Low level
  * [actix/actix](https://github.com/actix/actix) — Rust[！[build badge]的演员库(https://api.travis-ci.org/actix/actix.svg?branch=master)](https://travis-ci.org/actix/actix)
  * [dylanmckay/protocol](https://github.com/dylanmckay/protocol) — 自定义TCP/UDP协议定义
  * [libpnet/libpnet](https://github.com/libpnet/libpnet) — 跨平台、低级别网络[！[build badge](https://api.travis-ci.org/libpnet/libpnet.svg?branch=master)](https://travis-ci.org/libpnet/libpnet)
  * [smoltcp-rs/smoltcp](https://github.com/smoltcp-rs/smoltcp) — 一个独立的、事件驱动的TCP/IP堆栈，专为裸机、实时系统设计[！[build badge](https://api.travis-ci.org/smoltcp-rs/smoltcp.svg?branch=master)](https://travis-ci.org/smoltcp-rs/smoltcp)
  * [tokio-rs/tokio](https://github.com/tokio-rs/tokio) — 一个网络应用程序框架，用于客户端和服务器的快速开发和高度可扩展的生产部署。
* message-io
  * [lemunozm/message-io](https://github.com/lemunozm/message-io) — 事件驱动消息库，轻松快速地构建网络应用程序。支持TCP、UDP和WebSockets。[！[构建徽章](https://img.shields.io/github/workflow/status/lemunozm/message-io/message-io%20ci)](https://github.com/lemunozm/message-io/actions?query=workflow%3A%22message-io+ci%22）
* MQTT
  * [bytebeamio/rumqtt](https://github.com/bytebeamio/rumqtt) - 供开发人员构建与[MQTT协议]通信的应用程序的库(https://mqtt.org)通过TCP和WebSockets，使用或不使用TLS。[！[构建和测试](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml/badge.svg)](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml)
* NanoMsg
  * [thehydroimpulse/nanomsg.rs](https://github.com/thehydroimpulse/nanomsg.rs) — [纳米](https://nanomsg.org/)绑定[！[build badge](https://api.travis-ci.org/thehydroimpulse/nanomsg.rs.svg?branch=master)](https://travis-ci.org/thehydroimpulse/nanomsg.rs)
* NATS
  * [nats-io/nats.rs](https://github.com/nats-io/nats.rs) — NATS的Rust客户端，云原生消息系统。[！[生成状态](https://github.com/nats-io/nats.rs/workflows/Rust/badge.svg?branch=master)](https://github.com/nats-io/nats.rs/actions)
* Nng
  * [neachdainn/nng-rs](https://gitlab.com/neachdainn/nng-rs) [[编号](https://crates.io/crates/nng)]-[Nng（毫微秒v2）](https://nng.nanomsg.org/index.html)绑定[！[build badge](https://gitlab.com/neachdainn/nng-rs/badges/master/pipeline.svg)](https://gitlab.com/neachdainn/nng-rs/-/pipelines)
* NNTP
  * [mattnenterprise/rust-nntp](https://github.com/mattnenterprise/rust-nntp) [[nntp](https://crates.io/crates/nntp)]-一个[NNTP](https://en.wikipedia.org/wiki/Network_News_Transfer_Protocol)Rust[！[build badge]客户端(https://api.travis-ci.org/mattnenterprise/rust-nntp.svg?branch=master)](https://travis-ci.org/mattnenterprise/rust-nntp)
* P2P
  * [libp2p/rust-libp2p](https://github.com/libp2p/rust-libp2p) — libp2p网络堆栈的Rust实现。[！[圆圈CI](https://circleci.com/gh/libp2p/rust-libp2p.svg?style=svg)](https://app.circleci.com/pipelines/github/libp2p/rust-libp2p)
* POP3
  * [mattnenterprise/rust-pop3](https://github.com/mattnenterprise/rust-pop3) [[pop3](https://crates.io/crates/pop3)]-A[POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol)Rust[！[build badge]客户端(https://api.travis-ci.org/mattnenterprise/rust-pop3.svg?branch=master)](https://travis-ci.org/mattnenterprise/rust-pop3)
* QUIC
  * [cloudflare/quiche](https://github.com/cloudflare/quiche) — QUIC传输协议和HTTP/3的cloudflare实现！[构建](https://img.shields.io/github/workflow/status/cloudflare/quiche/Stable)
  * [mozilla/neqo](https://github.com/mozilla/neqo) — 用Rust编写的QUIC的实现
  * [quinn-rs/quinn](https://github.com/quinn-rs/quinn) — Rust[！[build badge]中基于未来的QUIC实现(https://dev.azure.com/dochtman/Projects/_apis/build/status/Quinn?branchName=master)](https://dev.azure.com/dochtman/Projects/_build)
* Raknet
  * [b23r0/rust-raknet](https://github.com/b23r0/rust-raknet) — Rust[！[Build Status]实现RakNet协议(https://img.shields.io/github/workflow/status/b23r0/rust-raknet/Rust)](https://github.com/b23r0/rust-raknet/actions/workflows/rust.yml)
* RPC
  * [ENQT-GmbH/remoc](https://github.com/ENQT-GmbH/remoc) [[远程](https://crates.io/crates/remoc)]-Remoc提供类似于Tokio的频道（广播、mpsc、oneshot、观看），并通过任何远程传输进行特征呼叫。[！[构建徽章](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml)
  * [smallnest/rpcx-rs](https://github.com/smallnest/rpcx-rs) — Rust的RPC库，用于以简单易行的方式开发微服务。[！[构建徽章](https://api.travis-ci.org/smallnest/rpcx-rs.svg?branch=master)](https://travis-ci.org/smallnest/rpcx-rs)
* Socket.io
  * [1c3t3a/rust-socketio](https://github.com/1c3t3a/rust-socketio) [[信任源](https://crates.io/crates/rust_socketio)]-[socket.io]的实现(https://socket.io)客户端使用Rust编写。[！[构建徽章](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml/badge.svg)](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml)
* SSH
  * [alexcrichton/ssh2-rs](https://github.com/alexcrichton/ssh2-rs) — [库ssh2](https://www.libssh2.org/)绑定[！[build badge](https://api.travis-ci.com/alexcrichton/ssh2-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/ssh2-rs)
  * [Thrussh](https://pijul.org/thrussh) [[画眉](https://crates.io/crates/thrussh)]-一个用Rust从头编写的SSH库，由[libsodina]支持(https://doc.libsodium.org/)
* Stomp
  * [zslayton/stomp-rs](https://github.com/zslayton/stomp-rs) — A[跺脚1.2](http://stomp.github.io/stomp-specification-1.2.html)Rust[！[build badge]中的客户端实现(https://api.travis-ci.org/zslayton/stomp-rs.svg?branch=master)](https://travis-ci.org/zslayton/stomp-rs)
* ZeroMQ
  * [erickt/rust-zmq](https://github.com/erickt/rust-zmq) — [零MQ](https://zeromq.org/)绑定[！[build badge](https://api.travis-ci.org/erickt/rust-zmq.svg?branch=master)](https://travis-ci.org/erickt/rust-zmq)

### Parsing

  * [Folyd/robotstxt](https://github.com/Folyd/robotstxt) - 谷歌机器人的原生Rust端口。txt解析器和匹配器C++库
  * [freestrings/jsonpath](https://github.com/freestrings/jsonpath) — [JsonPath](https://goessner.net/articles/JsonPath/)用Rust编写的引擎。Webassembly和Javascript也支持[！[Build Status](https://api.travis-ci.org/freestrings/jsonpath.svg?branch=master)](https://travis-ci.org/freestrings/jsonpath)
  * [Geal/nom](https://github.com/Geal/nom) — 解析器组合库[！[build badge](https://api.travis-ci.org/Geal/nom.svg?branch=master)](https://travis-ci.org/Geal/nom)
  * [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg) — 解析表达式语法（PEG）分析器生成器
  * [lalrpop/lalrpop](https://github.com/lalrpop/lalrpop) — Rust[！[Build status]的LR（1）解析器生成器(https://api.travis-ci.org/lalrpop/lalrpop.svg?branch=master)](https://travis-ci.org/lalrpop/lalrpop)
  * [m4rw3r/chomp](https://github.com/m4rw3r/chomp) –快速一元式解析器组合符[！[build badge](https://api.travis-ci.org/m4rw3r/chomp.svg?branch=master)](https://travis-ci.org/m4rw3r/chomp)
  * [Marwes/combine](https://github.com/Marwes/combine) — 解析器组合库[！[build badge](https://api.travis-ci.org/Marwes/combine.svg?branch=master)](https://travis-ci.org/Marwes/combine)
  * [nrc/zero](https://github.com/nrc/zero) [[零](https://crates.io/crates/zero/)]-二进制数据的零分配解析
  * [pest-parser/pest](https://github.com/pest-parser/pest) — 优雅的分析器[！[Build Status](https://api.travis-ci.org/pest-parser/pest.svg?branch=master)](https://travis-ci.org/pest-parser/pest)
  * [ptal/oak](https://github.com/ptal/oak) — 类型化PEG解析器生成器（编译器插件）
  * [replicadse/wavefront_rs](https://github.com/replicadse/wavefront_rs) — Wavefront OBJ格式的解析器。[！[板条箱.io](https://img.shields.io/crates/v/wavefront_rs.svg)](https://crates.io/crates/wavefront_rs)[！[板条箱.io](https://img.shields.io/crates/d/wavefront_rs?label=crates.io%20downloads)](https://crates.io/crates/wavefront_rs)[！[构建徽章](https://github.com/replicadse/wavefront_rs/workflows/pipeline/badge.svg?branch=master)](https://github.com/replicadse/wavefront_rs/actions)
  * [s-panferov/queryst](https://github.com/s-panferov/queryst) — 受[gs]启发的Rust查询字符串解析库(https://github.com/ljharb/qs#readme)
  * [softdevteam/grmtools](https://github.com/softdevteam/grmtools/) - 具有更好纠错能力的LR解析器

### Peripherals

* Serial Port
  * [Susurrus/serialport-rs](https://gitlab.com/susurrus/serialport-rs) [[串行端口](https://crates.io/crates/serialport)]-提供对串行端口访问的跨平台库

### Platform specific

* Cross-platform
  * [svartalf/rust-battery](https://crates.io/crates/battery) — 关于笔记本电池的跨平台信息[！[build badge](https://api.travis-ci.org/svartalf/rust-battery.svg?branch=master)](https://travis-ci.org/svartalf/rust-battery)
  * [vityafx/thread-priority](https://github.com/vityafx/thread-priority/) - 简单的跨平台线程优先级管理。[！[CI](https://github.com/vityafx/thread-priority/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/thread-priority/actions/workflows/ci.yml)[！[板条箱徽章](https://img.shields.io/crates/v/thread-priority.svg)](https://crates.io/crates/thread-priority)
* FreeBSD
  * [fubarnetes/libjail-rs](https://github.com/fubarnetes/libjail-rs/) [[监狱](https://crates.io/crates/jail)]-FreeBSD监狱库的Rust实现
* Linux
  * [arvancloud/nginx-rs](https://github.com/arvancloud/nginx-rs) — [Nginx](https://www.nginx.com)绑定[！[build badge](https://api.travis-ci.org/arvancloud/nginx-rs.svg?branch=master)](https://travis-ci.org/arvancloud/nginx-rs)
  * [hannobraun/inotify-rs](https://github.com/hannobraun/inotify-rs) — [初始化](https://en.wikipedia.org/wiki/Inotify)绑定[！[Rust](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml)
  * [pop-os/distinst](https://github.com/pop-os/distinst/) — Linux分发安装程序
  * [yaa110/rust-iptables](https://github.com/yaa110/rust-iptables) [[iptables](https://crates.io/crates/iptables)]-[iptables](https://www.netfilter.org/projects/iptables/index.html)绑定[！[build badge](https://api.travis-ci.org/yaa110/rust-iptables.svg?branch=master)](https://travis-ci.org/yaa110/rust-iptables)
* Unix-like
  * [nix-rust/nix](https://github.com/nix-rust/nix) — 类Unix API绑定[！[Cirrus Build Status](https://api.cirrus-ci.com/github/nix-rust/nix.svg)](https://cirrus-ci.com/github/nix-rust/nix)
  * [rustix](https://github.com/bytecodealliance/rustix) — POSIX/Unix/Linux/Winsock2系统调用的安全Rust绑定[！[Actions Status](https://github.com/bytecodealliance/rustix/workflows/CI/badge.svg)](https://github.com/bytecodealliance/rustix/actions?query=workflow%3ACI)
  * [zargony/fuse-rs](https://github.com/zargony/fuse-rs) — [保险丝](https://github.com/libfuse/libfuse)绑定
* Windows
  * [retep998/winapi-rs](https://github.com/retep998/winapi-rs) — Windows API绑定[！[Rust](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml/badge.svg?branch=dev)](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml)

### Scripting

[[scripting](https://crates.io/keywords/scripting)]

* [duckscript](https://crates.io/crates/duckscript) — [简单、可扩展和可嵌入的脚本语言。](https://github.com/sagiegurari/duckscript)[！[构建徽章](https://github.com/sagiegurari/duckscript/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/duckscript/actions)
* [fleabitdev/gamelisp](https://github.com/fleabitdev/glsp) — 一种用于Rust游戏开发的LISP lisk脚本语言
* [gluon-lang/gluon](https://github.com/gluon-lang/gluon) —  一种小型的静态类型函数式编程语言
* [KusionStack/KCLVM](https://github.com/KusionStack/KCLVM) - 一种基于约束的记录和函数语言，主要用于配置和策略场景。
* [metacall/core](https://github.com/metacall/core) [[元球](https://crates.io/crates/metacall)]-跨平台Polyglot Runtime，支持NodeJS、JavaScript、TypeScript、Python、Ruby、C#、Wasm、Java、Cobol等。[！[构建徽章](https://gitlab.com/metacall/core/badges/master/pipeline.svg)](https://gitlab.com/metacall/core)
* [mun](https://github.com/mun-lang/mun) — 一种编译的静态类型脚本语言，具有一流的热重新加载支持[！[build badge](https://api.travis-ci.org/mun-lang/mun.svg?branch=master)](https://travis-ci.org/mun-lang/mun)
* [murarth/ketos](https://github.com/murarth/ketos) — 一种Lisp方言函数式编程语言，用作rust的脚本和扩展语言
* [PistonDevelopers/dyon](https://github.com/PistonDevelopers/dyon) — 一种生疏的动态类型脚本语言
* [rhaiscript/rhai](https://github.com/rhaiscript/rhai) — 一种小型且快速的嵌入式脚本语言，类似于JavaScript和Rust[！[build badge]的组合(https://github.com/rhaiscript/rhai/workflows/Build/badge.svg)](https://github.com/rhaiscript/rhai/actions)
* [rune-rs/rune](https://github.com/rune-rs/rune) — 一种可嵌入的Rust动态编程语言

### Simulation

[[simulation](https://crates.io/keywords/simulation)]

* [nyx-space](https://crates.io/crates/nyx-space) - 高保真、快速、可靠且经过验证的天体动力学工具包库，用于航天器任务设计和轨道确定[！[Build Status](https://gitlab.com/nyx-space/nyx/badges/master/pipeline.svg)](https://gitlab.com/nyx-space/nyx/-/pipelines)

### Task scheduling

* [delay-timer](https://github.com/BinChengZhao/delay-timer) — 延迟任务的时间管理器。与crontab类似，但异步任务是可能的。
[![Build](https://github.com/BinChengZhao/delay-timer/actions/workflows/rust.yml/badge.svg)](
https://github.com/BinChengZhao/delay-timer/actions)

### Template engine

* Handlebars
  * [botika/yarte](https://github.com/botika/yarte) — Yarte代表**Y**et**A**另一个**R**ust**T**模板**E**引擎，是最快的模板引擎。[！[生成状态](https://api.travis-ci.org/botika/yarte.svg?branch=master)](https://travis-ci.org/botika/yarte)
  * [sunng87/handlebars-rust](https://github.com/sunng87/handlebars-rust) — 具有继承、自定义助手支持的Handlebars模板引擎。[！[构建徽章](https://api.travis-ci.org/sunng87/handlebars-rust.svg?branch=master)](https://travis-ci.org/sunng87/handlebars-rust)
* HTML
  * [djc/askama](https://github.com/djc/askama) — 基于Jinja[！[build badge]的模板渲染引擎(https://api.travis-ci.org/djc/askama.svg?branch=master)](https://travis-ci.org/djc/askama)
  * [kaj/ructe](https://github.com/kaj/ructe) — Rust[！[build badge]的HTML模板系统(https://api.travis-ci.org/kaj/ructe.svg?branch=master)](https://travis-ci.org/kaj/ructe)
  * [Keats/tera](https://github.com/Keats/tera) — 基于Jinja2和Django模板语言的模板引擎。[！[操作状态](https://github.com/Keats/tera/workflows/ci/badge.svg?branch=master)](https://github.com/Keats/tera/actions)
  * [lambda-fairy/maud](https://github.com/lambda-fairy/maud) — 编译时HTML模板[！[build badge](https://api.travis-ci.org/lambda-fairy/maud.svg?branch=master)](https://travis-ci.org/lambda-fairy/maud)
  * [Stebalien/horrorshow-rs](https://github.com/Stebalien/horrorshow-rs) — 编译时HTML模板[！[build badge](https://api.travis-ci.org/Stebalien/horrorshow-rs.svg?branch=master)](https://travis-ci.org/Stebalien/horrorshow-rs)
* Mustache
  * [rustache/rustache](https://github.com/rustache/rustache) — [！[构建徽章](https://api.travis-ci.org/rustache/rustache.svg?branch=master)](https://travis-ci.org/rustache/rustache)

### Text processing

* [becheran/wildmatch](https://github.com/becheran/wildmatch) [[通配符](https://crates.io/crates/wildmatch)]-简单字符串匹配问号和星号通配符[！[Actions Status](https://github.com/becheran/wildmatch/workflows/Build/badge.svg?branch=master)](https://github.com/becheran/wildmatch/actions)
* [BurntSushi/suffix](https://github.com/BurntSushi/suffix) — 线性时间后缀数组构造（支持Unicode）[！[build badge](https://api.travis-ci.org/BurntSushi/suffix.svg?branch=master)](https://travis-ci.org/BurntSushi/suffix)
* [BurntSushi/tabwriter](https://github.com/BurntSushi/tabwriter) — 弹性制表位（即文本列对齐）[！[build badge](https://api.travis-ci.org/BurntSushi/tabwriter.svg?branch=master)](https://travis-ci.org/BurntSushi/tabwriter)
* [cpc](https://github.com/probablykasper/cpc) - 分析和计算数学字符串，支持单位和单位转换，从“1+2”到“1%（1光年/14！s到km/h）”。
* [Daniel-Liu-c0deb0t/triple_accel](https://github.com/Daniel-Liu-c0deb0t/triple_accel) [[三倍加速](https://crates.io/crates/triple_accel)]-使用SIMD加速的Rust编辑距离例程；支持快速Hamming、Levenshtein、受限Damerau-Levenshtein等距离计算和字符串搜索[！[build badge](https://github.com/Daniel-Liu-c0deb0t/triple_accel/workflows/Test/badge.svg?branch=master)](https://github.com/Daniel-Liu-c0deb0t/triple_accel/actions)
* [fancy-regex/fancy-regex](https://github.com/fancy-regex/fancy-regex) [[花式正则表达式](https://crates.io/crates/fancy-regex)]-正则表达式实现旨在支持一组相对丰富的功能，如环视和回溯。[！[板条箱](https://img.shields.io/crates/v/fancy-regex.svg)](https://crates.io/crates/fancy-regex)[！[构建徽章](https://github.com/fancy-regex/fancy-regex/workflows/ci/badge.svg)](https://github.com/fancy-regex/fancy-regex/actions/workflows/ci.yml)
* [greyblake/whatlang-rs](https://github.com/greyblake/whatlang-rs) — 基于三角图的自然语言检测库[！[build badge](https://api.travis-ci.org/greyblake/whatlang-rs.svg?branch=master)](https://travis-ci.org/greyblake/whatlang-rs)
* [Lucretiel/joinery](https://github.com/Lucretiel/joinery) [[细木工](https://crates.io/crates/joinery)]–通用字符串+可迭代连接[！[build badge](https://api.travis-ci.org/Lucretiel/joinery.svg?branch=master)](https://travis-ci.org/Lucretiel/joinery)
* [mgeisler/textwrap](https://github.com/mgeisler/textwrap) [[文本换行](https://crates.io/crates/textwrap)]-自动换行文本（支持连字符）[！[build badge](https://api.travis-ci.org/mgeisler/textwrap.svg?branch=master)](https://travis-ci.org/mgeisler/textwrap)
* [ps1dr3x/easy_reader](https://github.com/ps1dr3x/easy_reader) — 一个阅读器，允许在巨大文件行中向前、向后和随机导航，而不需要使用迭代器[！[build badge](https://api.travis-ci.org/ps1dr3x/easy_reader.svg?branch=master)](https://travis-ci.org/ps1dr3x/easy_reader)
* [pwoolcoc/ngrams](https://github.com/pwoolcoc/ngrams) [[ngrams](https://crates.io/crates/ngrams)]-构造[n-grams](https://en.wikipedia.org/wiki/N-gram)来自任意迭代器[！[build badge](https://api.travis-ci.org/pwoolcoc/ngrams.svg?branch=master)](https://travis-ci.org/pwoolcoc/ngrams)
* [rust-lang/regex](https://github.com/rust-lang/regex) — 正则表达式（RE2样式）[！[build badge](https://api.travis-ci.com/rust-lang/regex.svg?branch=master)](https://travis-ci.org/rust-lang/regex)
* [strsim-rs](https://crates.io/crates/strsim) — 字符串相似性度量[！[build badge](https://api.travis-ci.org/dguo/strsim-rs.svg?branch=master)](https://travis-ci.org/dguo/strsim-rs)
* [yaa110/rake-rs](https://github.com/yaa110/rake-rs) [[耙](https://crates.io/crates/rake)]-Rust的RAKE算法的多语言实现[！[build badge](https://api.travis-ci.org/yaa110/rake-rs.svg?branch=master)](https://travis-ci.org/yaa110/rake-rs)

### Text search

* [andylokandy/simsearch-rs](https://github.com/andylokandy/simsearch-rs) [[模拟搜索](https://crates.io/crates/simsearch)]-一个简单轻量级的模糊搜索引擎，在内存中工作，搜索相似的字符串
* [BurntSushi/fst](https://github.com/BurntSushi/fst) [[fst](https://crates.io/crates/fst)]-[！[构建徽章](https://api.travis-ci.org/BurntSushi/fst.svg?branch=master)](https://travis-ci.org/BurntSushi/fst)
* [CurrySoftware/perlin](https://github.com/CurrySoftware/perlin) [[珀林](https://crates.io/crates/perlin)]
* [meilisearch/MeiliSearch](https://github.com/meilisearch/MeiliSearch) — 超相关、即时且允许错别字的全文搜索API。[！[生成状态](https://github.com/meilisearch/MeiliSearch/workflows/Cargo%20test/badge.svg?branch=master)](https://github.com/meilisearch/MeiliSearch/actions)
* [tantivy](https://github.com/quickwit-oss/tantivy) [[坦蒂维](https://crates.io/crates/tantivy)]-用Rust编写的极速全文搜索引擎库。[！[生成状态](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml/badge.svg)](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml)

### Unsafe

* [zerocopy](https://crates.io/crates/zerocopy) — 用于将任意字节序列安全地重新解释为本机Rust类型的实用程序

### Virtualization

* [beneills/quantum](https://github.com/beneills/quantum) — 高级Rust量子计算机模拟器[！[构建徽章](https://api.travis-ci.org/beneills/quantum.svg?branch=master)](https://travis-ci.org/beneills/quantum)
* [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime) — WebAssembly的独立运行时[！[Build Status](https://github.com/bytecodealliance/wasmtime/workflows/CI/badge.svg)](https://github.com/bytecodealliance/wasmtime/actions?query=workflow%3ACI)
* [chromium/chromiumos/platform/crosvm](https://chromium.googlesource.com/chromiumos/platform/crosvm/) CrOSVM-使Chrome OS能够在快速、安全的虚拟化环境中运行Linux应用程序
* [oxidecomputer/propolis](https://github.com/oxidecomputer/propolis) - illumos bhyve内核模块的基于Rust的用户空间程序
* [saurvs/hypervisor-rs](https://github.com/saurvs/hypervisor-rs) — OS X上的硬件加速虚拟化
* [unicorn-rs/unicorn-rs](https://github.com/unicorn-rs/unicorn-rs) — unicorn CPU模拟器的Rust绑定[！[Build Status](https://api.travis-ci.org/ekse/unicorn-rs.svg?branch=master)](https://travis-ci.org/ekse/unicorn-rs)

### Web programming

See also [Are we web yet?](https://www.arewewebyet.org) and [Rust web framework comparison](https://github.com/flosse/rust-web-framework-comparison).

* Client-side / WASM
  * [cargo-web](https://crates.io/crates/cargo-web) — 客户端Web的Cargo子命令[！[Build Status](https://api.travis-ci.org/koute/cargo-web.svg?branch=master)](https://travis-ci.org/koute/cargo-web)
  * [sauron](https://github.com/ivanceras/sauron) - 客户端web框架，它与Elm架构紧密结合。[！[生成状态](https://api.travis-ci.org/ivanceras/sauron.svg?branch=master)](https://travis-ci.org/ivanceras/sauron)
  * [seed](https://seed-rs.org/) — 用于创建web应用程序的Rust框架
  * [stdweb](https://crates.io/crates/stdweb) — 客户端Web的标准库[！[Build Status](https://api.travis-ci.org/koute/stdweb.svg?branch=master)](https://travis-ci.org/koute/stdweb)
  * [yew](https://crates.io/crates/yew) — 用于制作客户端web应用程序的Rust框架
* HTTP Client
  * [alexcrichton/curl-rust](https://github.com/alexcrichton/curl-rust) — [libcurl](https://curl.se/libcurl/)绑定[！[build badge](https://api.travis-ci.com/alexcrichton/curl-rust.svg?branch=master)](https://travis-ci.org/alexcrichton/curl-rust)
  * [async-graphql](https://github.com/async-graphql/async-graphql) - 在Rust[！[Build Status]中实现的GraphQL服务器库(https://dev.azure.com/graphql-rust/GraphQL%20Rust/_apis/build/status/graphql-锈刺柏）](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_build/latest?definitionId=1)
  * [DoumanAsh/yukikaze](https://gitlab.com/Douman/yukikaze) [[有幸](https://crates.io/crates/yukikaze)]-美丽优雅的Yukikaze是一个基于hyper的小型HTTP客户端库。[！[构建徽章](https://gitlab.com/Douman/yukikaze/badges/master/pipeline.svg)](https://gitlab.com/Douman/yukikaze)
  * [graphql-client](https://github.com/graphql-rust/graphql-client) — 在Rust中键入正确的GraphQL请求和响应。[！[Github操作状态](https://github.com/graphql-rust/graphql-client/workflows/CI/badge.svg?branch=master)](https://github.com/graphql-rust/graphql-client/actions)
  * [hyperium/hyper](https://github.com/hyperium/hyper) — HTTP实现[！[CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
  * [seanmonstar/reqwest](https://github.com/seanmonstar/reqwest) — 一个符合人体工程学的Rust HTTP客户端。[！[构建徽章](https://api.travis-ci.org/seanmonstar/reqwest.svg?branch=master)](https://travis-ci.org/seanmonstar/reqwest)
* HTTP Server
  * [actix/actix-web](https://github.com/actix/actix-web) — Rust的轻量级异步web框架，支持websocket[！[build badge](https://api.travis-ci.org/actix/actix-web.svg?branch=master)](https://travis-ci.org/actix/actix-web)
  * [branca](https://crates.io/crates/branca) — Branca的纯Rust实现，用于认证和加密API令牌。[！[构建徽章](https://api.travis-ci.org/return/branca.svg?branch=master)](https://travis-ci.org/return/branca)
  * [carllerche/tower-web](https://github.com/carllerche/tower-web) [[塔腹板](https://crates.io/crates/tower-web)]-Rust[！[build badge]的快速、无模板的web框架(https://api.travis-ci.org/carllerche/tower-web.svg?branch=master)](https://travis-ci.org/carllerche/tower-web)
  * [danclive/sincere](https://github.com/danclive/sincere) — 一个基于超线程和多线程的Rust（稳定）微web框架。[！[构建徽章](https://api.travis-ci.org/danclive/sincere.svg?branch=master)](https://travis-ci.org/danclive/sincere)
  * [GildedHonour/frank_jwt](https://github.com/GildedHonour/frank_jwt) — Rust中的JSON Web令牌实现。[！[构建徽章](https://api.travis-ci.org/GildedHonour/frank_jwt.svg?branch=master)](https://travis-ci.org/GildedHonour/frank_jwt)
  * [Gotham](https://github.com/gotham-rs/gotham) — 一个灵活的web框架，不会牺牲安全性、安全性或速度。[！[构建徽章](https://api.travis-ci.org/gotham-rs/gotham.svg?branch=master)](https://travis-ci.org/gotham-rs/gotham)
  * [handlebars-rust](https://github.com/sunng87/handlebars-rust) — Iron web框架中间件。[！[构建徽章](https://api.travis-ci.org/sunng87/handlebars-iron.svg?branch=master)](https://travis-ci.org/sunng87/handlebars-iron)
  * [hyperium/hyper](https://github.com/hyperium/hyper) — HTTP实现[！[CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
  * [Iron](https://github.com/iron/iron) — 基于中间件的服务器框架[！[build badge](https://api.travis-ci.org/GildedHonour/frank_jwt.svg?branch=master)](https://travis-ci.org/GildedHonour/frank_jwt)
  * [Juniper](https://github.com/graphql-rust/juniper) — Rust[！[build badge]的GraphQL服务器库(https://api.travis-ci.org/graphql-rust/juniper.svg?branch=master)](https://travis-ci.org/graphql-rust/juniper)
  * [miketang84/sapper](https://github.com/miketang84/sapper) — 一个基于异步超的轻量级web框架，用Rust语言实现。
  * [Nickel](https://github.com/nickel-org/nickel.rs/) — 灵感来自[Express](http://expressjs.com/)[！[构建徽章](https://api.travis-ci.org/nickel-org/nickel.rs.svg?branch=master)](https://travis-ci.org/nickel-org/nickel.rs)
  * [Ogeon/rustful](https://github.com/Ogeon/rustful) — Rust[！[build badge]的RESTful web框架(https://api.travis-ci.org/Ogeon/rustful.svg?branch=master)](https://travis-ci.org/Ogeon/rustful)
  * [Rocket](https://github.com/SergioBenitez/Rocket) — Rocket是Rust（夜间）的web框架，重点关注易用性、可表达性和速度[！[build badge](https://api.travis-ci.org/SergioBenitez/Rocket.svg?branch=master)](https://travis-ci.org/SergioBenitez/Rocket)
  * [Rustless](https://github.com/rustless/rustless) — 受[Grape]启发的类似REST的API微框架(https://github.com/ruby-grape/grape)和[Hyper](https://github.com/hyperium/hyper)[！[构建徽章](https://api.travis-ci.org/rustless/rustless.svg?branch=master)](https://travis-ci.org/rustless/rustless)
  * [Salvo](https://github.com/salvo-rs/salvo) — 一个基于hyper和tokio的易于使用的web框架。[！[内部版本](https://github.com/salvo-rs/salvo/workflows/CI%20（Linux）/bedge.svg？分支=主&事件=推送）](https://github.com/salvo-rs/salvo/actions)
  * [Saphir](https://github.com/richerarc/saphir) — 一个具有低级控制的渐进式web框架，没有痛苦。
  * [seanmonstar/warp](https://github.com/seanmonstar/warp) — 一个超简单、可组合的web服务器框架，用于提高速度。[！[板条箱](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/warp)
  * [tiny-http](https://github.com/tiny-http/tiny-http) — 低级HTTP服务器库[！[build badge](https://api.travis-ci.org/tiny-http/tiny-http.svg?branch=master)](https://travis-ci.org/tiny-http/tiny-http)
  * [tokio/axum](https://github.com/tokio-rs/axum) - 使用Tokio、Tower和Hyper[！[Build badge]构建的符合人体工程学的模块化网络框架(https://github.com/tokio-rs/axum/actions/workflows/CI.yml/badge.svg?branch=main)](https://github.com/tokio-rs/axum/actions/workflows/CI.yml)
  * [tomaka/rouille](https://github.com/tomaka/rouille) — Rust[！[build badge]中的Web框架(https://api.travis-ci.org/tomaka/rouille.svg?branch=master)](https://travis-ci.org/tomaka/rouille)
* Miscellaneous
  * [cargonauts](https://github.com/cargonauts-rs/cargonauts) — 一个用于构建可维护、功能完善的web应用程序的web框架。
  * [causal-agent/scraper](https://github.com/causal-agent/scraper) [[刮刀](https://crates.io/crates/scraper)]-使用CSS选择器进行HTML解析和查询。[！[生成状态](https://github.com/causal-agent/scraper/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/causal-agent/scraper/actions)
  * [hominee/dyer](https://github.com/hominee/dyer) [[染料](https://crates.io/crates/dyer)]-dyer专为可靠、灵活和快速的基于请求响应的服务而设计，包括数据处理、网络爬网等，在不影响速度的情况下提供一些友好、灵活、全面的功能。
  * [osohq/oso](https://github.com/osohq/oso) [[oso](https://crates.io/crates/oso)]-应用程序中嵌入的授权策略引擎。[！[生成状态](https://github.com/osohq/oso/workflows/Development/badge.svg?branch=main)](https://github.com/osohq/oso/actions?query=branch%3Amain+工作流%3开发）
  * [pwoolcoc/soup](https://gitlab.com/pwoolcoc/soup) [[汤](https://crates.io/crates/soup)]-一个类似于Python的BeautifulSoup的库，旨在实现对HTML文档的快速轻松操作和查询。[！[生成状态](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)
  * [pyrossh/rust-embed](https://github.com/pyrossh/rust-embed) — 用于将静态资产嵌入rust二进制文件的宏
  * [serenity-rs/serenity](https://github.com/serenity-rs/serenity) [[宁静](https://crates.io/crates/serenity)]-Discord API的Rust库
  * [softprops/openapi](https://github.com/softprops/openapi) — 用于处理openapi规范文件的库
  * [tbot](https://gitlab.com/SnejUgal/tbot) [[待定](https://crates.io/crates/tbot)]-使用Rust轻松制作酷炫的Telegram机器人[！[管道状态](https://gitlab.com/SnejUgal/tbot/badges/master/pipeline.svg)](https://gitlab.com/SnejUgal/tbot/-/commits/master)
  * [teloxide/teloxide](https://github.com/teloxide/teloxide/) - Rust[！[Build Status]的优雅Telegram机器人框架(https://github.com/teloxide/teloxide/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/teloxide/teloxide/actions)
  * [utkarshkukreti/select.rs](https://github.com/utkarshkukreti/select.rs) [[选择](https://crates.io/crates/select)]-一个从HTML文档中提取有用数据的库，适用于web刮取。[！[生成状态](https://api.travis-ci.org/utkarshkukreti/select.rs.svg?branch=master)](https://travis-ci.org/utkarshkukreti/select.rs)
* Reverse Proxy
  * [sozu-proxy/sozu](https://github.com/sozu-proxy/sozu) [[搜狐](https://crates.io/crates/sozu)]-HTTP反向代理。[！[CI](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml)
* Static Site Generators
  * [cobalt-org/cobalt.rs](https://github.com/cobalt-org/cobalt.rs) — 用Rust[！[Build Status]编写的静态站点生成器(https://dev.azure.com/cobalt-org/cobalt-org/_apis/build/status/cobalt.rs?branchName=master)](https://dev.azure.com/cobalt-org/cobalt-org/_build?definitionId=2)
  * [FuGangqiang/mdblog.rs](https://github.com/FuGangqiang/mdblog.rs) [[mdblog](https://crates.io/crates/mdblog)]-来自markdown文件的静态站点生成器。
  * [getzola/zola](https://github.com/getzola/zola) [[佐拉](https://www.getzola.org/)]-一个固执己见的静态站点生成器，内置所有内容。[！[生成状态](https://dev.azure.com/getzola/zola/_apis/build/status/getzola.zola?branchName=master)](https://dev.azure.com/getzola/zola/_build)
  * [leven-the-blog/leven](https://github.com/leven-the-blog/leven) [[列文](https://crates.io/crates/leven)]-一个简单的并行博客生成器。[！[构建徽章](https://api.travis-ci.org/quadrupleslap/leven.svg?branch=master)](https://travis-ci.org/quadrupleslap/leven)
* [WebSocket](https://datatracker.ietf.org/doc/rfc6455/)
  * [housleyjk/ws-rs](https://github.com/housleyjk/ws-rs) — 轻量级、事件驱动的Rust[！[build badge]WebSockets(https://api.travis-ci.org/housleyjk/ws-rs.svg?branch=stable)](https://travis-ci.org/housleyjk/ws-rs)
  * [rust-websocket](https://github.com/websockets-rs/rust-websocket) — 用于处理WebSocket连接（客户端和服务器）的框架[！[build badge](https://api.travis-ci.org/websockets-rs/rust-websocket.svg?branch=master)](https://travis-ci.org/websockets-rs/rust-websocket)
  * [snapview/tungstenite-rs](https://github.com/snapview/tungstenite-rs) — Rust的轻量级基于流的WebSocket实现。
  * [vi/websocat](https://github.com/vi/websocat) — 用于与WebSockets交互的CLI，具有Netcat、Curl和Socat功能。[！[构建徽章](https://api.travis-ci.org/vi/websocat.svg?branch=master)](https://travis-ci.org/vi/websocat)
  * [vityafx/urlshortener-rs](https://github.com/vityafx/urlshortener-rs) — Rust的一个非常简单的urlshorter库。[！[CI](https://github.com/vityafx/urlshortener-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/urlshortener-rs/actions/workflows/ci.yml)[！[板条箱徽章](https://img.shields.io/crates/v/urlshortener.svg)](https://crates.io/crates/urlshortener)

## Registries

A registry allows you to publish your Rust libraries as crate packages, to share them with others publicly and privately.

* [Cloudsmith :heavy_dollar_sign:](https://cloudsmith.com/cargo-registry/) — 一个完全管理的包管理SaaS，对公共和私有Cargo/Rust注册中心（以及许多其他注册中心）提供一流的支持。有一个慷慨的免费层，而且对于开源来说也是完全免费的。
* [Crates](https://crates.io) — Rust/Cargo的官方公共注册。
* [w4/chartered](https://github.com/w4/chartered) - 私人、认证、许可的货物登记处[！[CI](https://github.com/w4/chartered/actions/workflows/ci.yml/badge.svg)](https://github.com/w4/chartered/actions/workflows/ci.yml)

## Resources

* Benchmarks
  * [TeXitoi/benchmarksgame-rs](https://github.com/TeXitoi/benchmarksgame-rs) — [the Computer Language Benchmarks Game]的Rust实现(https://benchmarksgame-team.pages.debian.net/benchmarksgame/)[！[构建徽章](https://api.travis-ci.org/TeXitoi/benchmarksgame-rs.svg?branch=master)](https://travis-ci.org/TeXitoi/benchmarksgame-rs)
* Decks & Presentations
  * [Learning systems programming with Rust](https://speakerdeck.com/jvns/learning-systems-programming-with-rust) — 由[Julia Evans]演示(https://twitter.com/@b0rk）@Rustconf 2016。
  * [Rust: Hack Without Fear!](https://www.youtube.com/watch?v=lO1z-7cuRYI) — 由[Nicholas Matsakis]介绍(https://github.com/nikomatsakis)@C++现在2018
  * [Shipping a Solid Rust Crate](https://www.youtube.com/watch?v=t4CyEKb-ywA) — 由[Michael Gattozzi]介绍(https://github.com/mgattozzi)@RustConf 2017
* [Discover Rust Libraries & Code Snippets](https://kandi.openweaver.com/explore/rust) - Rust库、作者、工具包、教程和kandi学习资源的精选列表
* Learning
  * [Awesome Rust Streaming](https://github.com/jamesmunns/awesome-rust-streaming) - 社区策划的关于Rust的直播列表。
  * [awesome-rust-mentors](https://rustbeginners.github.io/awesome-rust-mentors/) — 愿意接受学员并向他们传授Rust和编程知识的有用Rust导师列表。
  * [Build a language VM](https://blog.subnetzero.io/post/building-language-vm-part-00/)
  * [CodeCrafters.io](https://app.codecrafters.io/tracks/rust) — 在Rust中构建自己的Redis、Git、Docker或SQLite
  * [Easy Rust](https://github.com/Dhghomon/easy_rust) - 用简单的英语学习Rust。
  * [exercism.org](https://exercism.org/tracks/rust) — 帮助您学习Rust中新概念的编程练习。
  * [Hands-on Rust](https://pragprog.com/titles/hwrust/hands-on-rust/) - 通过制作游戏学习Rust的实践指南-由[Herbert Wolverson](https://github.com/thebracket/)（已支付）
  * [Idiomatic Rust](https://github.com/mre/idiomatic-rust) —  同行评议的教授Rust惯用语的文章/谈话/报告集。
  * [Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/) — 通过实现几种不同类型的列表结构，深入探索Rust的内存管理规则。
  * [Little Book of Rust Books](https://lborb.github.io/book/) - 生锈书籍和方法的诅咒列表。
  * [Programming Community Curated Resources for Learning Rust](https://hackr.io/tutorials/learn-rust) — 由编程社区投票的推荐资源列表。
  * [Refactoring to Rust](https://www.manning.com/books/refactoring-to-rust) - 介绍Rust语言的书。
  * [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
  * [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/) — 一组简单的示例，演示了使用Rust生态系统的板条箱完成常见编程任务的良好实践。
  * [Rust for professionals](https://overexact.com/rust-for-professionals/) — 为有经验的软件开发人员快速介绍Rust。
  * [Rust Gym](https://github.com/warycat/rustgym) - Rust解决了大量的编码面试问题。
  * [Rust in Action](https://www.manning.com/books/rust-in-action) — [Tim McNamara]的Rust系统编程实践指南(https://github.com/timClicks)（已支付）
  * [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion?a_aid=cnichols&a_bid=6a993c2e) — [卡罗尔·尼科尔斯]的视频系列(https://github.com/carols10cents)和[Jake Goulding](https://github.com/shepmaster)（已支付）
  * [Rust Language Cheat Sheet](https://cheats.rs/)
  * [Rust Online Courses at Classpert](https://classpert.com/search/rust) — Classpert在线课程搜索中的Rust在线课程列表（付费）
  * [Rust Tiếng Việt](https://rust-tieng-viet.github.io/) - 学习越南语生锈。
  * [rust-how-do-i-start](https://github.com/jondot/rust-how-do-i-start) - 一个专门回答问题的回购：“那么，Rust。我该如何启动？”。初学者只能手工挑选资源和学习轨迹。
  * [rust-learning](https://github.com/ctjhoa/rust-learning) — 学习Rust的有用资源集合
  * [Rustlings](https://github.com/rust-lang/rustlings) — 让你习惯读写Rust代码的小练习
  * [Rusty CS](https://github.com/AbdesamedBendjeddou/Rusty-CS) - 有助于在Rust中实践所学学术知识的计算机科学课程
  * [stdx](https://github.com/brson/stdx) — 首先学习这些板条箱作为std的扩展
  * [Take your first steps with Rust](https://learn.microsoft.com/en-us/training/paths/rust-first-steps/) - 为在Rust中构建快速有效的程序奠定知识基础。
  * [University of Pennsylvania's Comp Sci Rust Programming Course](http://cis198-2016s.github.io/schedule/)
* Podcasts
  * [New Rustacean](https://newrustacean.com) — 关于学习Rust的播客
  * [Rustacean Station](https://rustacean-station.org/) — 为Rust创建播客内容的社区项目
* [Rust Design Patterns](https://github.com/rust-unofficial/patterns)
* [Rust Guidelines](http://aturon.github.io/)
* [Rust Servers, Services and Apps - MEAP](https://www.manning.com/books/rust-servers-services-and-apps) - 在Rust中构建后端服务器、服务和前端，以获得快速、可靠和可维护的应用程序。
* [Rust Subreddit](https://www.reddit.com/r/rust/) — 发布和讨论与锈蚀相关的问题、文章和资源的子reddit（论坛）
* [RustBooks](https://github.com/sger/RustBooks) — RustBooks列表
* [RustCamp 2015 Talks](https://www.youtube.com/playlist?list=PLE7tQUdRKcybdIw61JpCoo89i4pWU5f_t)
* [RustViz](https://github.com/rustviz/rustviz) — generates visualizations from simple Rust programs to assist users in better understanding the Rust Lifetime and Borrowing mechanism.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

