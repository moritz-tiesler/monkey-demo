## Monkey Language Setup Demo

This repo contains an [Monkeylang](https://github.com/moritz-tiesler/monkey) executable and two packaged VSCode extensions.

- [Language Server Extension](https://github.com/moritz-tiesler/monkey-lsp)
- [Debugger Extension](https://github.com/moritz-tiesler/monkey-debug)

The extensions can be installed with

`code --install-extension <extension.vsix>`

or via the VSCode UI.


A quick browser demo is available [here](https://github.com/moritz-tiesler/repl)

To run the Monkey language from the command line use

`monkey -c` for interactive mode and

`monkey -c -f <file.mky>` for running a Monkey file.