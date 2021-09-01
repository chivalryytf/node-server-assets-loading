# Nodejs Simple Static Asset Serving Server Project

- [Contents](#what's-nodejs?)
  - [Installing Node](#installing-node)
  - [API (async code)](#api-async-code)

## What's Nodejs?
> Nodejs is an environment to run javascript outside browser.
*Features:*
- Open Source Runtime System
- Built on Chrome's V8 javascript engine
*Applications:*
- Tooling (build, automation, etc.)
- APIs (REST,Realtime/Streaming, etc.)
- CDNs
- Shareable libraries
- Desktop Applications
- IOT

### Installing Node

Install node with [nodenv](https://github.com/nodenv/nodenv). 
See all the versions installable:
```bash
nodenv install -l
```

Install the version of your choice (for eg. version 14.15.1)
```bash
nodenv install 14.15.1
```

Important: After installing node, please run `npm install i` or `npm install` to install the dependencies located in the `package.json` file.


### API (async code)
* commands
  * start the server - `node src/server.js`

It's a simple static asset server. The server uses promise to asynchronously load assets from the `assets` folder.



