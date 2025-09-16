# Projects Workspace

This folder holds small example projects for multiple languages with VS Code launch configurations.

Structure:
- rust/hello_rust: Rust example using Cargo and CodeLLDB.
- python/hello_python: Python example with `main.py`.
- lua/hello_lua: Lua example with `init.lua` (needs Lua debug extension).

See each project's `.vscode/launch.json` for how to run/debug.

Recommended VS Code extensions:
- rust-lang.rust-analyzer
- vadimcn.vscode-lldb or mataz.kdl-debugger (CodeLLDB)
- ms-python.python
- sumneko.lua (or luau) - Lua language server
- tomblind.local-lua-debugger (or similar) for Lua debugging
