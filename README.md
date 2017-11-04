# Scalameta language-server

This is an experimental [Language Server Protocol](https://github.com/Microsoft/language-server-protocol)
implementation for Scala based on Scalameta.

## Project structure
- `language-server` contains a Scala implementation of a language server
- `vscode-extension` contains a Visual Studio Code extension, implementing a client for the language server

## Trying this out
- publish the `language-server` locally

```sh
cd language-server
sbt publishLocal
```

- open the vscode-extension in Visual Studio Code

```sh
cd vscode-extension
code .
```

and press F5 to start debugging.