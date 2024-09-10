# Semantic Version manager (`@m3o/version`)

[![JSR](https://jsr.io/badges/@m3o)](https://jsr.io/@m3o)
[![JSR](https://jsr.io/badges/@m3o/version)](https://jsr.io/@m3o/version)
[![JSR Score](https://jsr.io/badges/@m3o/version/score)](https://jsr.io/@m3o/version/score)
![GitHub License](https://img.shields.io/github/license/marco-souza/version)
![GitHub Release](https://img.shields.io/github/v/release/marco-souza/version)

A JavaScript and TypeScript library to manage semantic versions.

> about Semantic Versioning: https://semver.org

This is compatible with Node.js, Deno and Bun via [`jsr.io`](httos://jsr.io).

## Installation

```sh
# with Deno
deno add jsr:@m3o/version

# with node
npx jsr add @m3o/version

# with Bun
bunx jsr add @m3o/version
```


## Usage


As CLI tool:

```sh
deno install -A jsr:@m3o/version/main.ts

version patch # default is deno.json
version minor deno.jsonc
version minor package.json
version major package.json
```
