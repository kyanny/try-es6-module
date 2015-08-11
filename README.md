Babelの手ほどき - さまざまな環境で使う | CodeGrid
https://app.codegrid.net/entry/babel-2

https://github.com/codegrid/2015-babel/tree/master/2/modules/es6

メモ:

- babel は変換するだけ。 concat とかは別途必要。
- babel a.js -m common babel b.js -m common babel index.js -m common してそれぞれできたやつを cat で連結しても node bundle.js で動かなかった...
