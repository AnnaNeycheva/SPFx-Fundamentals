## ofp-app-customizer

This is where you include your WebPart documentation.

### Building the code

```bash
git clone the repo
npm i
npm i -g gulp
gulp
```

This package produces the following:

* lib/* - intermediate-stage commonjs build artifacts
* dist/* - the bundled script, along with other resources
* deploy/* - all resources which should be uploaded to a CDN.

### Build options

gulp clean - TODO
gulp test - TODO
gulp serve - TODO
gulp bundle - TODO
gulp package-solution - TODO

### To debug
set NODE_NO_HTTP2=1 && gulp serve --nobrowser
set NODE_NO_HTTP2=1 && gulp serve --config ofpWeb

?loadSPFX=true&debugManifestsFile=https://localhost:4321/temp/manifests.js&customActions={"b5158e7b-f334-4e70-a21d-e18ab519be98":{"location":"ClientSideExtension.ApplicationCustomizer"}}