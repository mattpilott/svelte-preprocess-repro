## Readme

The repro is set to use the `sass` package and the build fails when using `:global()` with sass code

However reverting to `node-sass` makes it work. I believe these should behave the same.

All the test code is in `/src/index.svelte`
