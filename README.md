## Monkey Language Setup Demo

This repo contains a [Monkey](https://github.com/moritz-tiesler/monkey) executable and two packaged VS Code extensions.

- [Language Server Extension](https://github.com/moritz-tiesler/monkeylang-lsp)
- [Debugger Extension](https://github.com/moritz-tiesler/monkeylang-debug)

The extensions can be installed with

`code --install-extension <extension.vsix>`

or via the VS Code UI.


A quick browser demo is available [here](https://github.com/moritz-tiesler/repl)

To run the Monkey language from the command line use

`monkey -c` for interactive mode or

`monkey -c -f <file.mky>` for running a Monkey file.
