# Completely Uninstall Node.js + npm from Mac OS X

This guide is usefull if you already have `Node.js` installed on Mac OS X but want to install `npm` packages globally without the `sudo` command

## Delete the following directories and/or files from you harddisk

1. go to `/usr/local/lib` and delete any `node` and `node_modules` directory
2. go to `/usr/local/include` and delete any `node` and `node_modules` directory
3. go to `~/local` and delete any `node` and `node_modules` directory
4. go to `~/lib` and delete any `node` and `node_modules` directory
5. go to `~/include` and delete any `node` and `node_modules` directory
6. go to `/usr/local/bin` and delete any `node executable` (`gulp`, `grunt`, `yo`, `npm`, `...`)
7. go to `/usr/local/bin` and delete `npm`
8. go to `/usr/local/include` and delete `node`
8. go to `/usr/local/share/man/man1` and delete `node.1`
9. go to `/usr/local/lib/dtrace` and delete `node.d`
10. go to `/opt/local/include` and delete `node`
11. go to `/opt/local/lib` and delete `node_modules`
12. go to `~/` and delete `.npm`
13. go to `~/` and delete `.node-gyp`

Inspired by [this post by Benjie Bantecil](http://benznext.com/completely-uninstall-node-js-from-mac-os-x/)

## Now it's time to install Node.js the right way:
[Install npm packages globally without sudo on OS X and Linux](https://github.com/ronnidc/guides/blob/master/npm-global-without-sudo.md)
