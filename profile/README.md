# Basalt

Basalt is a free and open source suite of programs for creating, hosting, and participating in local programming competitions.

Documentation for usage of Basalt can be found at <https://basalt-rs.github.io>



# Community

We're actively looking for more community members and contributors to the project! Feel free to join the Discord and inquire for more information.
We also have GitHub issues in our repositories that anyone is welcome to solve.

* [Discord (_primary_)](https://discord.gg/jTGXMPgp6J)
* [Matrix](https://matrix.to/#/#basalt-rs:matrix.org)

# Stack

- Rust
- React (Next.js) + Tauri
- Docker

# Components

Basalt is comprised of a handful of core pieces:

- **Server**
    - **basalt-server** [[Source](https://github.com/basalt-rs/basalt-server)] [[API Documentation](https://basalt-rs.github.io/basalt-server/)] - Server runtime for Basalt competitions 
    - **leucite** [[Source](https://github.com/basalt-rs/leucite)] [[Crate](https://crates.io/crates/leucite)] [[Docs](https://docs.rs/leucite)] - Sandboxed environment for running commands
    - **erudite** [[Source](https://github.com/basalt-rs/erudite)] [[Docs](https://basalt-rs.github.io/erudite/)] - Parallel test runner that uses `leucite` for sandboxing
- **Client** [[Source](https://github.com/basalt-rs/basalt)] [[Docs](https://github.com/basalt-rs/basalt/wiki)]
    - **Web Application** (NextJS)
    - **Desktop Application** (Tauri + Web Application)
    - **Web Bundler** *provides an embeddable instance of the Web Application in Rust*
- **CLI** [[Source](https://github.com/basalt-rs/basalt-cli)] [[Docs](https://basalt.rs/cli)]

To stay organized, we have logically separate repositories and libraries that account for required functionality.
[Leucite](https://crates.io/crates/leucite) for example is a library we created to easily create sandboxed execution
environments.
