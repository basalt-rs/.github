# Basalt

Basalt is a set of applications for hosting a local programming competition.

There are two parts to Basalt, each of which are broken into smaller
pieces:

- The server
    - Sandboxed Test Runner
        - [leucite](https://crates.io/crates/leucite)
    - HTTP Server
- The client (host/competitor UI)
    - Web bundler -- for bundling the web application into the server
    - Tauri + Next.js


