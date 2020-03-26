# berry + next + typescript repro

You can reproduce the bug by running:

```bash
cd packages/website
yarn next build
```

And you'll get:

```text
Creating an optimized production build

Failed to compile.

ERROR in undefined(undefined,undefined):
undefined:undefined Cannot find type definition file for 'node'.


> Build error occurred
Error: > Build failed because of webpack errors
    at build (/Users/ulyssecarion/dev/src/github.com/ucarion/berry-next-typescript-repro/.yarn/$$virtual/next-virtual-089af99451/0/cache/next-npm-9.3.1-25a6eb45dc-2.zip/node_modules/next/dist/build/index.js:12:900)
```
