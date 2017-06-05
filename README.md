<h1 align="center">Fetch Inject</h1>

DEPRECATED.

This is a fork of fetch-inject in a self-contained dependency.
Simply instantiate fetch-inject.js and be on your way!

## UPDATE

Thanks to jhadbas for this update (2017/06/05):

I've updated the build system to make it easier to use and you can get a ES5 bundle of Fetch Inject by doing the following:

`npm i && npm run build && cat dist/fetch-inject.umd.js` for UMD
`npm i && npm run build && cat dist/fetch-inject.js` for vanilla IIFE

**EDIT:** This process is the exact same as before, but the NPM scripts have now been simplified.

The dist bundles are also available both in minified and non-minified version on jsDelivr here:

https://cdn.jsdelivr.net/npm/fetch-inject@latest/dist/ - for edge bundles
https://cdn.jsdelivr.net/npm/fetch-inject@1.7.2/dist/fetch-inject.js for IIFE pinned at `1.7.2`

Cheers.

## License
Same terms as the original fetch-inject module.
