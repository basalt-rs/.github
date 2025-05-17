# Basalt

Basalt is a set of applications for hosting a local programming competition.

Documentation for usage of Basalt can be found at <https://basalt-rs.github.io>

There are two core parts of Basalt, each of which are broken into smaller
pieces:

# Community

* [Discord (_primary_)](https://discord.gg/jTGXMPgp6J)
* [Matrix](https://matrix.to/#/#basalt-rs:matrix.org)

# Stack

- **Server**
    - **leucite** [[Source](https://github.com/basalt-rs/leucite)] [[Crate](https://crates.io/crates/leucite)] [[Docs](https://docs.rs/leucite)] - Sandboxed environment for running commands
    - **erudite** [[Source](https://github.com/basalt-rs/erudite)] [[Docs](https://basalt-rs.github.io/erudite/)] - Parallel test runner that uses `leucite` for sandboxing
    - **basalt-server** [[Source](https://github.com/basalt-rs/basalt-server)] [[API Documentation](https://basalt-rs.github.io/basalt-server/)] - Server runtime for Basalt competitions 
- **Client** [[Source](https://github.com/basalt-rs/basalt)] [[Docs](https://github.com/basalt-rs/basalt/wiki)]
    - **Web Application** (NextJS)
    - **Desktop Application** (Tauri + Web Application)
    - **Web Bundler** *provides an embeddable instance of the Web Application in Rust*

To stay organized, we have logically separate repositories and libraries that account for required functionality.
[Leucite](https://crates.io/crates/leucite) for example is a library we created to easily create sandboxed execution
environments.
