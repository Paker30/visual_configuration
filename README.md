# paco-snippets README

I have to warn you, this is **my first VSCode** configuration :)

This configuration only have the few custom JavaScript snippets I like to use when I work, I do hope it will help you as much as they help me.

## Features

Those are the snippets:
- `ust`: 'use strict';
- `afn`: ($1) => {$3}$2;
- `inlineArfn`: ($1) => $2
- `adreq`: const $2 = require('$1');$3
- `pfn`: Promise((resolve, reject) => {$2});$1
- `presolve`: Promise.resolve($2)$1
- `preject`: Promise.reject($2)$1
- `admap`: map(($2) => {$3})($1)
- `adfilter`: map(($2) => {$3})($1)
- `adreduce`: filter(($2) => {$3})($1)
- `mapArr`: $1.map(($2) => {$3})
- `filterArr`: $1.filter(($2) => {$3})
- `reduceArr`: $1.reduce(($3) => {$4},$2)
- `Bcombinator`: compose($1)($1);
- `getProp`: const $1 = get($2);
