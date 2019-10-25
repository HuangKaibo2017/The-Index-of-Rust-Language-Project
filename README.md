# The Index of Rust Language Project
I am trying to do something on Rust project, before that it needs to build up proper help tools, that is, rebuild some gears. First thing first, I need to know what gears I need that doesn't have a proper implement. So how about make a list/index of the rust I found might useful to me or someone else?  Let me do it now.... :)

## Standard of my selection
##### Score
The index only relative to the works i might be interested in.
##### Not Score
The projects need not be 'awesome' as those 'Awesome XXX project' listed. The index would be a try of complete list of Rust Language project even it might be *complete* if nutcases are enough to fulfill the impossible task.

## Search Method Description
The results cames from search feature of github UI and keyword as 'Rust' and filter as 'Rust Language'.
status:
1. https://github.com/search?l=Rust&p=12&q=rust&type=Repositories
2. https://awesomeopensource.com/projects/rust?projectPage=6

## Similar Works
https://github.com/rust-unofficial/awesome-rust - I have to read it too :D. There are some diff of mine against that list.
https://crates.io/ - full list of crates.
https://github.com/rust-windowing/winit/wiki/Missing-features-provided-by-other-crates - About GUI.
https://github.com/rust-lang-nursery - baby rust projects.
https://github.com/cmr/this-week-in-rust - Content for this-week-in-rust.org. Made available under CC-BY-SA.

## Okey, Now the list

### Books & newsletters & blogs
[2019-10-20][Active] https://github.com/rust-lang-nursery/nomicon - The Dark Arts of Advanced and Unsafe Rust Programming. This book digs into all the awful details that are necessary to understand in order to write correct Unsafe Rust programs. Due to the nature of this problem, it may lead to unleashing untold horrors that shatter your psyche into a billion infinitesimal fragments of despair.
[2019-10-20][Active] https://github.com/rust-lang-nursery/reference - Official of The Rust Language Reference
[2019-10-18][Active] https://github.com/rust-lang/book 
[2019-10-18][Died] https://github.com/rustcc/RustPrimer
[2019-10-18][Active] https://github.com/rust-lang/rust-clippy - A collection of lints to catch common mistakes and improve your Rust code.
[2019-10-18][Active] https://github.com/nrc/r4cppp - A Rust tutorial for experienced C and C++ programmers.
[2019-10-18][Died] https://github.com/stevedonovan/gentle-intro
[2019-10-20][Active] https://github.com/rust-lang-nursery/failure/
[2019-10-23][Active] https://github.com/flosse/rust-web-framework-comparison - A comparison of some web frameworks and libs written in Rust.
[2019-10-23][Active] https://github.com/cmr/this-week-in-rust/ - https://this-week-in-rust.org/
[2019-10-22][Active] https://github.com/dtolnay/proc-macro-workshop - This repo contains a selection of projects designed to learn to write Rust procedural macros — Rust code that generates Rust code. Procedural macros in expression position.
[2019-10-23][Active] https://github.com/crazymykl/rust-koans -Each koan builds up your knowledge of Rust and builds upon itself. By following the failures and errors presented, you will know what to work on next. As you finish one koan file, the next will be added to path_to_enlightenment.rs.
[2019-10-25][Active] https://docs.rs/releases - docs of Rust?

Others:
http://acm.timus.ru/help.aspx?topic=rust
https://www.oreilly.com/programming/free/files/why-rust.pdf
https://open.kattis.com/problems
http://rosettacode.org/wiki/Rosetta_Code
Rosetta Code is a programming chrestomathy site. The idea is to present solutions to the same task in as many different languages as possible, to demonstrate how languages are similar and different, and to aid a person with a grounding in one approach to a problem in learning another

### Rust Language General
Bro, don't die! https://github.com/rust-lang/rustup.rs It keeps Rust Programming Language live
https://github.com/rust-lang-nursery/reference - Official of The Rust Language Reference
https://github.com/rust-lang/rfcs - RFCs
[2019-10-18][Active] https://github.com/dtolnay/quote - This crate provides the quote! macro for turning Rust syntax tree data structures into tokens of source code.
[2019-10-20][Active] https://github.com/rust-lang-nursery/rustc-perf - Website for Rust Compiler Performance Monitoring & Benchmarking. https://perf.rust-lang.org
[2019-10-20][Active] https://github.com/rust-lang-nursery/rust-toolstate - This repository records the compilation and testing status of development tools bundled with the Rust build system.
[2019-10-20][Active] https://github.com/rust-lang/rust-clippy - A collection of lints to catch common mistakes and improve your Rust code.
[2019-10-20][Active] https://github.com/rust-lang/miri - An interpreter for Rust's mid-level intermediate representation. An experimental interpreter for Rust's mid-level intermediate representation (MIR). It can run binaries and test suites of cargo projects and detect certain classes of undefined behavior.
[2019-10-22][Active] https://github.com/mehcode/config-rs - Layered configuration system for Rust applications (with strong support for 12-factor applications).
[2019-10-22][Active] https://github.com/seanmonstar/try-lock - A light-weight lock guarded by an atomic boolean.
[2019-10-22][Active] https://github.com/dtolnay/anyhow - A better Box<dyn Error> 
[2019-10-22][Active] https://github.com/BurntSushi/ripgrep - ripgrep is a line-oriented search tool that recursively searches your current directory for a regex pattern. 
[2019-10-20][Active] https://github.com/rust-lang-nursery/error-chain - take full advantage of Rust's error handling features without the overhead of maintaining boilerplate error types and conversions. It implements an opinionated strategy for defining your own error types, as well as conversions from others' error types.
[2019-10-20][Active] https://github.com/rust-lang-nursery/rustc-pr-tracking/
[2019-10-23][Died] https://github.com/contain-rs/cons-list - An immutable singly-linked list, as seen in basically every functional language.
[2019-10-23][Active] https://github.com/edef1c/libfringe - libfringe is a library implementing safe, lightweight context switches, without relying on kernel services. It can be used in hosted environments (using std) as well as on bare metal (using core).
https://github.com/rust-lang-nursery/rustfix - The goal of this tool is to read and apply the suggestions made by rustc.

### Design Pattern
[2019-10-25][Active] https://github.com/rust-lang-nursery/lazy-static.rs - it is possible to have statics that require code to be executed at runtime in order to be initialized. This includes anything requiring heap allocations, like vectors or hash maps, as well as anything that requires non-const function calls to be computed.

### Log
[2019-10-18][Active] https://github.com/sfackler/log4rs
[2019-10-18][Active] https://github.com/rust-lang-nursery/log - A Rust library providing a lightweight logging facade.
[2019-10-22][Active] https://github.com/seanmonstar/pretty-env-logger - A simple logger built on top off env_logger(https://docs.rs/env_logger/0.7.1/env_logger/). It is configured via an environment variable and writes to standard error with nice colored output for log levels.
[2019-10-22][Active] https://github.com/tokio-rs/tracing - Application level tracing for Rust. https://tokio.rs. is a framework for instrumenting Rust programs to collect structured, event-based diagnostic information. 
[2019-10-22][Active] https://github.com/rust-lang/rust-log-analyzer - Analyzing Travis and Azure Pipelines logs to find encountered errors.The Rust Log Analyzer (RLA) is a tool that analyzes the CI build logs of the rust-lang/rust repository with the purpose of automatically extracting error messages from failed builds.

### Async & Parallel computing
[2019-10-18][Active] https://github.com/Matthias247/futures-intrusive
[2019-10-18][Active] https://github.com/tokio-rs/tokio A runtime for writing reliable asynchronous applications with Rust. Provides I/O, networking, scheduling, timers, ... https://tokio.rs
[2019-10-20][Active] https://github.com/rust-lang-nursery/futures-rs - Zero-cost asynchronous programming in Rust http://rust-lang-nursery.github.io/futures-rs
[2019-10-22][Active] https://github.com/tokio-rs/async-stream - Asynchronous streams for Rust using async & await notation.
[2019-10-22][Active] https://github.com/tokio-rs/async - Utilities building on top of Rust's async primitives. 
[2019-10-22][Active] https://github.com/mvdnes/spin-rs - This Rust library implements a simple spinlock, and is safe for #[no_std] environments.
[2019-10-23][Active] https://github.com/rayon-rs/rayon - A data parallelism library. Rayon is a data-parallelism library for Rust. It is extremely lightweight and makes it easy to convert a sequential computation into a parallel one. It also guarantees data-race freedom. (You may also enjoy this blog post about Rayon, which gives more background and details about how it works, or this video, from the Rust Belt Rust conference.) Rayon is available on crates.io, and API Documentation is available on docs.rs.
[2019-10-23][Active] https://github.com/wez/cancel-rs - This crate provides a simple token that can be used to co-operatively manage cancellation of an operation. Setting a deadline/timeout is also supported.
[2019-10-23][Died] https://github.com/dgrunwald/rust-cancellation - CancellationToken for composable cancellation in Rust.

### Test
[2019-10-22][Active] https://github.com/crossbario/autobahn-testsuite - used by 
[2019-10-23][Active] https://github.com/BurntSushi/quickcheck - QuickCheck is a way to do property based testing using randomly generated input. This crate comes with the ability to randomly generate and shrink integers, floats, tuples, booleans, lists, strings, options and results. All QuickCheck needs is a property function—it will then randomly generate inputs to that function and call the property for each set of inputs. If the property fails (whether by a runtime error like index out-of-bounds or by not satisfying your property), the inputs are "shrunk" to find a smaller counter-example.
[2019-10-23][Active] https://github.com/mitsuhiko/rust-incidents - This library provides an experiment for error handling in Rust. It provides efficient error handling and provides powerful debugging features.

### System & IO
[2019-10-22][Active] https://github.com/tokio-rs/mio - Mio is a lightweight I/O library for Rust with a focus on adding as little overhead as possible over the OS abstractions.
[2019-10-22][Active] https://github.com/tokio-rs/bytes - A utility library for working with bytes.
[2019-10-22][Died] https://github.com/AtheMathmo/toy-os - Once I had a simple C kernel working I decided to switch to Rust! This was a fairly painful transition initially. Adapting my boot loader proved to be very error prone. Eventually I switched to GRUB and began following Philipp Oppermann's awesome blog(http://os.phil-opp.com/). Which is crazy good.
[2019-10-22][Active] https://github.com/gz/rust-x86 - Library to program x86 (amd64) hardware. Contains x86 specific data structure descriptions, data-tables, as well as convenience function to call assembly instructions typically not exposed in higher level languages. https://docs.rs/x86
[2019-10-23][Active] https://github.com/tsgates/rust.ko - A minimal Linux kernel module written in rust. 
[2019-10-23][Active] https://github.com/BurntSushi/ripgrep - ripgrep recursively searches directories for a regex pattern
[2019-10-23][Died] https://github.com/jwilm/rust_daemon_template - This is a template for writing a daemon using Rust.
[2019-10-23][Active] https://github.com/CraneStation/cranelift - Generates target binary code giving c language?

### CI or maintainments
[2019-10-18][Active] https://github.com/rust-lang/rustup.rs
[2019-10-18][Active] https://github.com/chyh1990/yaml-rust
[2019-10-18][Active] https://github.com/crossbeam-rs/rfcs - There is a RPC process and templates I could ref for my own.
[2019-10-22][Active] https://github.com/nix-rust/nix - Rust friendly bindings to nix APIs. ref: https://github.com/NixOS/nixpkgs (Nix Packages collection)
[2019-10-23][Active] https://github.com/rust-lang/git2-rs - git2-rs works with stable Rust, and typically works with the most recent prior stable release as well. Check the MSRV job of the CI script to see the oldest version of Rust known to pass tests.
[2019-10-22][Active] https://github.com/mre/idiomatic-rust - A peer-reviewed collection of articles/talks/repos which teach concise, idiomatic Rust. 
[2019-10-25][Active] https://github.com/mgeisler/version-sync - Rust projects typically reference the crate version number in several places, such as the README.md file. The version-sync crate makes it easy to add an integration test that checks that README.md is updated when the crate version changes.
[2019-10-25][Active] - docs.rs — Automatic documentation generation of crates

### Algorithms
[2019-10-18][Died] https://github.com/TheAlgorithms/Rust - the algorthm list is useful. Python/C algorithms are good ref.
[2019-10-18][Active] https://github.com/reem/rust-ordered-float
[2019-10-18][Active] ttps://github.com/rust-random/rand
[2019-10-22][Active] https://github.com/EbTech/rust-algorithms - Common data structures and algorithms in Rust. Contest Algorithms in Rust.
[2019-10-22][Active] https://github.com/rust-num/num - A collection of numeric types and traits for Rust.
[2019-10-22][Active] https://github.com/rust-ndarray/ndarray - ndarray: an N-dimensional array with array views, multidimensional slicing, and efficient operations https://docs.rs/ndarray/
[2019-10-22][Died] https://github.com/AtheMathmo/rusty-data - Basic data handling library.
[2019-10-22][Active] https://github.com/rust-rosetta/rust-rosetta -  https://rosettacode.org/wiki/Category:Rust. Rosetta Code is a programming chrestomathy site.
[2019-10-25][Active] https://github.com/petgraph/fixedbitset - https://github.com/petgraph/fixedbitset
[2019-10-25][Active] https://github.com/petgraph/petgraph - Graph data structure library. Known to support Rust 1.37 and later. It implements many graph algoithms.
[2019-10-25][died] https://github.com/eternaleye/rust-critbit - A crit bit tree, also known as a Binary Patricia Trie is a trie (https://en.wikipedia.org/wiki/Trie), also called digital tree and sometimes radix tree or prefix tree (as they can be searched by prefixes), is an ordered tree data structure that is used to store a dynamic set or associative array where the keys are usually strings. Unlike a binary search tree, no node in the tree stores the key associated with that node; instead, its position in the tree defines the key with which it is associated. more ref: https://github.com/jfager/functional-critbit, also http://cr.yp.to/critbit.html


### Data or Database/Datawarehouse opt relatives
[2019-10-18][Active] https://github.com/pingcap/rust-prometheus
[2019-10-18][Died] https://github.com/nickel-org/nickel-postgres
[2019-10-18][Died] https://github.com/sfackler/r2d2-postgres - A generic connection pool for Rust. 
[2019-10-18][Active] https://github.com/sfackler/rust-postgres - postgres db driver.
[2019-10-18][Active] https://github.com/sfackler/rust-postgres-large-object
[2019-10-19][Active] https://github.com/sfackler/foreign-types
[2019-10-22][Active] https://github.com/rust-rocksdb/rust-rocksdb - rust wrapper for rocksdb.
[2019-10-23][Active] https://github.com/diesel-rs/diesel - ORM. A safe, extensible ORM and Query Builder for Rust.
[2019-10-23][Active] https://github.com/graphql-rust/juniper - GraphQL server library for Rust. *Juniper* makes it possible to write GraphQL servers in Rust that are type-safe and blazingly fast. We also try to make declaring and resolving GraphQL schemas as convenient as possible as Rust will allow.
[2019-10-23][Active] https://github.com/sfackler/rust-phf - Compile time static maps for Rust with CHD algorithm.

### Data Format relative
[2019-10-19][Active] https://github.com/serde-rs/serde - Serde is a framework for serializing and deserializing Rust data structures efficiently and generically.

### ML-DL
[2019-10-20][Active] https://github.com/RustAudio/deepspeech-rs - The library is open source and performs Speech-To-Text completely offline. They provide pretrained models for English. It binds to https://github.com/mozilla/DeepSpeech.
[2019-10-22][Died] https://github.com/AtheMathmo/rusty-machine -Rusty-machine is a general purpose machine learning library implemented entirely in Rust. It aims to combine speed and ease of use - without requiring a huge number of external dependencies.
[2019-10-22][Died] https://github.com/AtheMathmo/rulinalg - Rulinalg is a linear algebra library written in Rust that doesn't require heavy external dependencies. The goal of rulinalg is to provide efficient implementations of common linear algebra techniques in Rust.
[2019-10-22][Died] https://github.com/AtheMathmo/rugrads - A proof of concept automatic differentiation library for Rust.
[2019-10-22][Died] https://github.com/AtheMathmo/vision-rs - Access to computer vision benchmarking datasets in Rust. This library provides access to common machine learning benchmarking datasets.
[2019-10-22][Active] https://github.com/arrayfire/arrayfire-rust - ArrayFire is a high performance library for parallel computing with an easy-to-use API. It enables users to write scientific computing code that is portable across CUDA, OpenCL and CPU devices. This project provides Rust bindings for the ArrayFire library. https://github.com/arrayfire/arrayfire: ArrayFire: a general purpose GPU library.
[2019-10-22][Died] https://github.com/autumnai/leaf - Open Machine Intelligence Framework for Hackers. (GPU/CPU) 
[2019-10-22][Died] https://github.com/jackm321/RustNN - RustNN is a feedforward neural network library. The library generates fully connected multi-layer artificial neural networks that are trained via backpropagation. Networks are trained using an incremental training mode.
[2019-10-22][Died] https://github.com/jackm321/Rust_Classifier - A naive Bayes classifier crate for Rust 
[2019-10-22][Died] https://github.com/japaric-archived/nvptx - How to: Run Rust code on your NVIDIA GPU
[2019-10-23][Active] https://github.com/bheisler/RustaCUDA - RustaCUDA helps you bring GPU-acceleration to your projects by providing a flexible, easy-to-use interface to the CUDA GPU computing toolkit. RustaCUDA makes it easy to manage GPU memory, transfer data to and from the GPU, and load and launch compute kernels written in any language.
[2019-10-23][Active] https://github.com/YunYang1994/ai-notebooks - reimplements articles code with tensorflow.

### InterActive with Other Programming-Language/Platform
[2019-10-18][Active] https://github.com/RustPython/RustPython - Looks good to me
[2019-10-18][Active] https://github.com/alexcrichton/cc-rs - Compile c/c++ code to binary and call by Rust. https://docs.rs/cc
[2019-10-19][Active] https://github.com/eqrion/cbindgen - A project for generating C bindings from Rust code.
[2019-10-22][Active] https://github.com/rust-lang/libc - Raw bindings to platform APIs for Rust. libc provides all of the definitions necessary to easily interoperate with C code (or "C-like" code) on each of the platforms that Rust supports. This includes type definitions (e.g. c_int), constants (e.g. EINVAL) as well as function headers (e.g. malloc).
[2019-10-23][Active] https://github.com/dgrunwald/rust-cpython - Rust bindings for the python interpreter.
[2019-10-25][Died] https://github.com/blas-lapack-rs/lapack-sys - Bindings to LAPACK (Fortran) 

### Middleware relatives
[2019-10-18][Active] https://github.com/pingcap/raft-rs - A distributed consensus algorithm implemented in Rust.
[2019-10-18][Active] https://github.com/crossbeam-rs/crossbeam - Tools for concurrent programming in Rust, RPC, PIPE, SYNC and etc.

### Networking
[2019-10-18][Active] https://github.com/sfackler/rust-socks
[2019-10-18][Active] https://github.com/alexcrichton/socket2-rs
[2019-10-22][Active] https://github.com/stepancheg/rust-protobuf - Rust implementation of Google protocol buffers.
[2019-10-18][Active] https://github.com/cloudflare/boringtun a replacement of OpenVPN
[2019-10-18][Active] https://github.com/hyperium/http - A general purpose library of common HTTP types.
[2019-10-19][Active] https://github.com/paritytech/jsonrpc
[2019-10-22][Active] https://github.com/seanmonstar/reqwest - An ergonomic, batteries-included HTTP Client for Rust. Base on hyper crate.
[2019-10-22][Active] https://github.com/hyperium/hyper - An HTTP library for Rust https://hyper.rs. Hyper is a relatively low-level library, if you are looking for simple high-level HTTP client, then you may wish to consider reqwest, which is built on top of this library.
[2019-10-22][Active] https://github.com/hyperium/tonic - A native gRPC client & server implementation with async/await support. https://docs.rs/tonic.
[2019-10-22][Active] https://github.com/hyperium/h2 - The h2 library has implemented more of the details of the HTTP/2.0 specification than any other Rust library. It also passes the h2spec set of tests.
[2019-10-22][Active] https://github.com/hyperium/hyper-tls - Provides an HTTPS connector for use with hyper.
[2019-10-22][Active] https://github.com/hyperium/http-body - Asynchronous HTTP body trait.
[2019-10-22][Active] https://github.com/hyperium/http-connection - 
[2019-10-22][Active] https://github.com/shadowsocks/shadowsocks-rust - This is a port of shadowsocks, which is VPN Client.
[2019-10-22][Active] https://github.com/websockets-rs/rust-websocket - Rust-WebSocket is a WebSocket (RFC6455) library written in Rust.
[2019-10-22][Active] https://github.com/tikv/grpc-rs - The gRPC library for Rust built on C Core library and futures.
[2019-10-22][Active] https://github.com/stepancheg/grpc-rust - 
[2019-10-22][Active] https://github.com/servo/rust-url - 
[2019-10-23][Active] https://github.com/libp2p/rust-libp2p - Rust Implementation of libp2p networking stack. https://libp2p.io Modular peer-to-peer networking stack (used by IPFS and others)

### Serialization
[2019-10-23][Active] https://github.com/BurntSushi/byteorder - Rust library for reading/writing numbers in big-endian and little-endian.
[2019-10-20][Active] https://github.com/serde-rs/serde - Serde is a framework for serializing and deserializing Rust data structures efficiently and generically.
[2019-10-22][Active] https://github.com/stepancheg/rust-protobuf - Rust implementation of Google protocol buffers. Base on https://github.com/carllerche/bytes.
[2019-10-22][Active] https://github.com/tafia/quick-protobuf - 
[2019-10-22][Active] https://github.com/danburkert/prost - 
[2019-10-22][Active] https://github.com/dflemstr/serde-protobuf - 
[2019-10-23][Active] https://github.com/google/flatbuffers - FlatBuffers is a cross platform serialization library architected for maximum memory efficiency. It allows you to directly access serialized data without parsing/unpacking it first, while still having great forwards/backwards compatibility.
[2019-10-23][Active] https://github.com/mvdnes/zip-rs - Zip implementation in Rust.

### Crypto
[2019-10-18][Active] https://github.com/sfackler/rust-openssl - OpenSSL bindings for Rust.
[2019-10-18][Active] https://github.com/sfackler/hyper-native-tls - An abstraction over platform-specific TLS implementations.
[2019-10-22][Active] https://github.com/ctz/rustls - Rustls is a TLS library that aims to provide a good level of cryptographic security, requires no configuration to achieve that security, and provides no unsafe features or obsolete cryptography.
[2019-10-22][Died] https://github.com/DaGenix/rust-crypto - A (mostly) pure-Rust implementation of various cryptographic algorithms. 
[2019-10-23][Active] https://github.com/jedisct1/libhydrogen - A lightweight, secure, easy-to-use crypto library suitable for constrained environments. https://libhydrogen.org
[2019-10-23][Active] https://github.com/sodiumoxide/sodiumoxide - Sodium is a portable, cross-compilable, installable, packageable fork of NaCl (based on the latest released upstream version nacl-20110221), with a compatible API. Sodium Oxide: Fast cryptographic library for Rust (bindings to libsodium) 
https://github.com/dcuddeback/des_crack

### Web Server
[2019-10-18][Active] https://github.com/nickel-org/nickel.rs
[2019-10-22][Active] https://github.com/SergioBenitez/Rocket - Rocket is a web framework for Rust (nightly) with a focus on ease-of-use, expressibility, and speed. 
[2019-10-22][Active] https://github.com/websockets-rs/rust-websocket - 
[2019-10-22][Active] https://github.com/iron/iron - An Extensible, Concurrent Web Framework for Rust http://ironframework.io
[2019-10-23][Died] https://github.com/rustless/rustless - REST-like API micro-framework for Rust. Works with Iron. 
[2019-10-23][Active] https://github.com/flosse/rust-web-framework-comparison - A comparison of some web frameworks and libs written in Rust.
[2019-10-23][Active] https://github.com/servo/rust-mozjs - Rust bindings to SpiderMonkey, which is the code name for the first JavaScript engine, written by Brendan Eich at Netscape Communications, later released as open-source and currently maintained by the Mozilla Foundation. 

### GUI/Game relatives
[2019-10-19][Active] https://github.com/gfx-rs/gfx - A low-overhead Vulkan-like GPU API for Rust.
[2019-10-19][Active] https://github.com/amethyst/rendy - State of the art "build your own engine" kit powered by gfx-hal, which mimics the Vulkan API.
[2019-10-19][Active] https://github.com/gfx-rs/wgpu - WebGPU native implementation in Rust.
[2019-10-19][Active] https://github.com/brendanzab/gl-rs - An OpenGL function pointer loader for Rust.
[2019-10-19][Active] https://github.com/kvark/vange-rs - The idea of this project is to replicate the old look and behavior, but with native hardware acceleration for the graphics.
[2019-10-19][Active] https://github.com/rust-windowing/glutin - A low-level library for OpenGL context creation, written in pure Rust. 
[2019-10-19][Active] https://github.com/rust-windowing/winit - winit, Cross-platform window creation and management in Rust, like Qt.
[2019-10-20][Active] https://github.com/rust-windowing/raw-window-handle - provides a common interface that window creation libraries (e.g. Winit, SDL) can use to easily talk with graphics libraries (e.g. gfx-hal).
[2019-10-20][Died] https://github.com/oakes/SolidOak - SolidOak is a simple IDE for Rust
[2019-10-23][Active] https://github.com/mvdnes/rboy - A Gameboy Emulator in Rust 
[2019-10-23][Active] https://github.com/rust-windowing/winit - Cross-platform window creation and management in Rust(js)
[2019-10-23][Active] https://github.com/phaazon/luminance-rs - Type-safe, type-level and stateless Rust graphics framework. luminance provides an API that is, for sure, a bit less low-level — and hence, yes, it’s likely you will not have the same performances as with gfx-hal (even though no benchmarks have been done so far), and the API is not Vulkan-based — but easier to start with, especially if you don’t already have a background experience with OpenGL or Vulkan.

### UI/Console tools
[2019-10-18][Active] https://github.com/rust-lang-nursery/mdBook compile md via Rust.
[2019-10-19][Active] https://github.com/lotabout/skim  navigate files, lines, commands. It is a general fuzzy finder that saves you time.
[2019-10-20][Active] https://github.com/integer32llc/rust-playground/ - This is the home of the Rust Playground(https://play.rust-lang.org/), also hosted by Integer 32(https://play.integer32.com/).

### Multi-media
[2019-10-19][Active] https://github.com/jeremyletang/rust-sfml - A gent to Simple and Fast Multimedia Library(SFML) - https://www.sfml-dev.org/
[2019-10-20][Active] https://github.com/RustAudio/rust-portaudio - PortAudio is a free, cross-platform, open-source, audio I/O library.
[2019-10-20][Active] https://github.com/RustAudio/deepspeech-rs - The library is open source and performs Speech-To-Text completely offline. They provide pretrained models for English. It binds to https://github.com/mozilla/DeepSpeech.
[2019-10-20][Active] https://github.com/RustAudio/rust-lv2 - A safe, fast, and ergonomic Rust library to create LV2 plugins for audio processing or synthesis, on any platform.
[2019-10-20][Active] https://github.com/RustAudio/cpal - Cross-platform audio I/O library in pure Rust.
[2019-10-20][Active] https://github.com/RustAudio/lewton - Vorbis decoder written in pure Rust.
[2019-10-20][Active] https://github.com/RustAudio/coreaudio-rs - A friendly rust interface to Apple's Core Audio API. 
[2019-10-20][Active] https://github.com/meh/rust-ffmpeg - Safe FFmpeg wrapper. 

### Mobile device
[2019-10-19][Active] https://github.com/rust-windowing/android-rs-glue - Glue between Rust and Android

### Tools
[2019-10-20][Active] https://github.com/servo/servo - The Servo Browser Engine https://servo.org/
[2019-10-22][Active] https://github.com/racer-rust/racer - Rust Code Completion utility.
[2019-10-22][Active] https://github.com/xi-editor/xi-editor - an Editor by Rust.

### IoT
[2019-10-23][Active] https://github.com/dcuddeback/termios-rs - The termios crate provides safe bindings for the Rust programming language to the terminal I/O interface implemented by Unix operating systems.
[2019-10-23][Active] https://github.com/dcuddeback/libusb-rs - This crate provides a safe wrapper around the native libusb library. It applies the RAII pattern and Rust lifetimes to ensure safe usage of all libusb functionality. All systems supported by the native libusb library are also supported by the libusb crate. It's been tested on Linux, OS X, and Windows.
[2019-10-23][Active] https://github.com/dcuddeback/libusb-sys - the libusb-sys crate provides declarations and linkage for the libusb C library. Following the *-sys package conventions, the libusb-sys crate does not define higher-level abstractions over the native libusb library functions.

### Others
[2019-10-19][Active] https://github.com/dtolnay/syn - Parser for Rust source code.
[2019-10-23][Active] https://github.com/kevinmehall/rust-peg - rust-peg is a simple yet flexible parser generator based on the Parsing Expression Grammar formalism. It provides a Rust macro that builds a recursive descent parser from a concise definition of the grammar.

### Blockchain
[2019-10-22][Active] https://github.com/holochain/holochain-rust - The core Holochain framework written in rust, a container API for running it (with rust and node implementations), and hdk-rust library for writing Zomes.
[2019-10-23][Active] https://github.com/rust-bitcoin/rust-bitcoin - Library with support for de/serialization, parsing and executing on data structures and network messages related to Bitcoin.
[2019-10-23][Active] https://github.com/libra/libra - too well known.

### Some not relative stuff
contribuing guide: https://github.com/nix-rust/nix/blob/master/CONTRIBUTING.md; https://github.com/rust-rosetta/rust-rosetta/blob/master/CONTRIBUTING.md
rfc template: https://github.com/nix-rust/rfcs/blob/master/0000-template.md

# License
Licensed under either of
    Apache License, Version 2.0 (LICENSE-APACHE or http://www.apache.org/licenses/LICENSE-2.0)
    MIT license (LICENSE-MIT or http://opensource.org/licenses/MIT)
at your option.

## Some Great Contributor
https://github.com/sfackler
https://github.com/meh
https://github.com/mehcode
https://github.com/seanmonstar
https://github.com/hyperium
https://github.com/tokio-rs
https://github.com/dtolnay
https://github.com/stepancheg
https://github.com/cmr
https://github.com/libp2p
https://github.com/dgrunwald

## Other relative stuff
https://github.com/crossbario - Seamless connectivity for the IoT and real-time microservices.  https://crossbar.io
