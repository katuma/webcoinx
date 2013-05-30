webcoinx ready-to-hack distribution
===================================
* Result looks like http://katuma.github.io/webcoinx
* Fork this repo
* Make sure you edit in ```gh-pages``` branch (should be default)
* Your changes appear immediately live at ```http://yourusername.github.io/webcoinx```

more intricate details
======================

[blah](katuma/webcoinx)
This is just quick and dirty to get people started. Actual code for browser code happens to live in
[bitcoinjs-gui](https://github.com/katuma/bitcoinjs-gui) and [bitcoinjs-lib](https://github.com/katuma/bitcoinjs-lib),
any upstream changed should be pull requested there.

Server, which only provides access to bulk blockchain data lives in
[node-bitcoin-exit](https://github.com/katuma/node-bitcoin-exit) and is [rather intricate to setup](https://github.com/katuma/node-bitcoin-exit/blob/master/README.md).
You will also need Linux VPS if you really want to run server websocket node (nodejs cloud hosting wont do).

Visit #bitcoinx @ freenode (my nick is tumak) if you have further questions.

Have fun!
