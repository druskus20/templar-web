# templar-web

The website for Templar.

The setup is based off of [Surma's blog](https://github.com/surma/surma.dev).

## Building and Running
```
npm run build -> runs ./full-build.sh, compiles the scss into css, uses parcel
                 to build .tmp/index.html into _site and publish it
npm run serve ->  serves node-server with npm
npm run watch ->  watches the eleventy and scss files
npm run dev   -> serve + watch
npm run fmt   -> formats the code
```
