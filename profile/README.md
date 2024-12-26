# Basalt

Basalt is a set of applications for hosting a local programming competition.

There are two parts to Basalt, each of which are broken into smaller
pieces:

- **Server**
    - Sandboxed Test Runner
        - **Leucite** [[Source](https://github.com/basalt-rs/leucite)] [[Crate and Docs](https://crates.io/crates/leucite)]
    - HTTP Server
- **Client** [[Source](https://github.com/basalt-rs/basalt)] [[Docs](https://github.com/basalt-rs/basalt/wiki)]
    - **Web Application** (NextJS)
    - **Desktop Application** (Tauri + Web Application)
    - **Web Bundler** *provides an embeddable instance of the Web Application in Rust*

To stay organized, we have logically separate repositories and libraries that account for required functionality.
[Leucite](https://crates.io/crates/leucite) for example is a library we created to easily create sandboxed execution
environments.
