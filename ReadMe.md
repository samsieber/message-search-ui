<center>
<h1>vue-parcel-starter</h1>
  <a href="https://travis-ci.org/edm00se/vue-parcel-starter">
    <img alt="build and deploy status" src="https://travis-ci.org/edm00se/vue-parcel-starter.svg?branch=master">
  </a>
  <a href="https://github.com/edm00se/vue-parcel-starter/actions?workflow=Node+CI">
    <img alt="npm test status" src="https://github.com/edm00se/vue-parcel-starter/workflows/Node%20CI/badge.svg">
  </a>
</center>

This is a simple starter file for [vue.js][vue] with [parcel][parcel]. I love both vue.js and parcel, so having a base starter to use just makes sense.

Alternatively, you can just load up this starter at [its corresponding codesandbox url][codesandbox-link]:
https://codesandbox.io/s/github/edm00se/vue-parcel-starter

## Features

- [vue.js](https://npm.im/vue) with SFCs (single file components)
- [parcel](https://npm.im/parcel-bundler) for bundling and dev server
- [jest](https://npm.im/jest) for unit tests
- [vs code jest config](.vscode/launch.json) for debugging with tests
- [prettier](https://npm.im/prettier) for formatting
- [travis ci config](.travis.yml) for deploy via [GitHub Pages](https://pages.github.com/)

## Installation

- `git clone `
- `cd vue-parcel-starter`
- `npm install`

## Usage

- `npm run dev` gives you a development server with hot reloading
- `npm run build` creates a production ready build
- `npm test` runs test suites

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request 🙂

## History

This is based heavily upon the example of parcel with vue.js from the [parcel examples repo][parcel-examples]. This will grow over time to build out inclusion of some features unique from the source example.

## Unique Features (So Far)

- sass/scss support
- testing via [jest][jest]

## Related

- [edm00se/create-vue-parcel][npm-init] an npm initializer

## Credits

- [parcel][parcel]
- [vue.js][vue]
- [parcel-bundler/examples/Vue][parcel-examples-vue], upon which this is based

## License

MIT

[vue]: https://vuejs.org/
[parcel]: https://parceljs.org/
[parcel-examples]: https://github.com/parcel-bundler/examples
[parcel-examples-vue]: https://github.com/parcel-bundler/examples/tree/master/vue
[jest]: https://jestjs.io/
[codesandbox-link]: https://codesandbox.io/s/github/edm00se/vue-parcel-starter
[npm-init]: https://github.com/edm00se/create-vue-parcel
