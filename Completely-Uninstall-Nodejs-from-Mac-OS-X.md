# Completely Uninstall Node.js from Mac OS X


Inspired by [this post by Benjie Bantecil](http://benznext.com/completely-uninstall-node-js-from-mac-os-x/)


## Remove the following directories and/or files

1. go to `/usr/local/lib` and delete any `node` and `node_modules`
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
12. `~/.npm`
13. `~/.node-gyp`


Inspired by [this post by Benjie Bantecil](http://benznext.com/completely-uninstall-node-js-from-mac-os-x/)
