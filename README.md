# commander subcommand loses argument order demo

demonstrate that [commander](https://github.com/tj/commander.js) can lose the order or arguments passed to subcommands

## Install
```sh
git clone https://github.com/maxlath/commander-subcommand-argument-order-demo.git
cd commander-subcommand-argument-order-demo
npm install
```

## Demo
```sh
 ./yo foo --someflag 1 2
# > from yo-foo
# > program.args [ '2', '1' ]
# > program.someflag true
```
