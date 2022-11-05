notes:

# doc
https://nodejs.dev/en/learn/nodejs-with-typescript/

# setup

`npm init -y`

`npm i -D typescript`

`touch example.ts`


# compile using the `tsc` command

- `tsc example.ts`

This is probably what I will use most the time. Just checks with ts to see if typescript has any errors for me

- `ts-node example.ts`

ts-node is a package that can be installed globally which will do the above command.

# to see when to use `tsc` or `ts-node` read:
`https://stackoverflow.com/questions/51448376/whats-the-difference-between-tsc-typescript-compiler-and-ts-node`

- `npx tsc example.ts`
this will generate a whole new .js file.

if I run `npx tsc example.ts` it will generate an `example.js` file as well.
