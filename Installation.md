# Cheatsheet Installation

See a more complete options of how to install ghost at [https://ghost.org/docs/install/](https://ghost.org/docs/install/). This cheatsheet will only discuss self hosted installation, for SaaS installation see the link above.

## Quick Installation

### Install via ghost-cli

You can install ghost with [NPM](https://www.npmjs.com/) via [ghost-cli](https://www.npmjs.com/package/ghost-cli), `ghost-cli` is designed to make setting up and maintaining a Ghost site as straight forward as possible for people who do not want to use Ghost(Pro).
`NOTE: This CLI is not designed to work with any Ghost versions < 1.0.0`

```bash
# Install ghost cli globally
$ npm install ghost-cli@latest -g

# Run/Test ghost-cli helper
# Note: if command ghost not found, then add in your .bashrc or .zshrc
$ ghost help

# Install & Download Ghost source code via ghost-cli
# Note: Make sure you are in empty folder when run this command.
# After run install ghost-cli will be automatically run ghost start
# scirpt with default web server `http://localhost:2368/`
$ ghost install local

# Stop Ghost Web Server via ghost-cli
$ ghost stop

# Start Manually Web Server via ghost-cli
$ ghost start
```
