# Welcome

Demo website for [angular-user-settings](https://github.com/jvandemo/angular-user-settings).

View live demo at: [http://angular-user-settings-demo.surge.sh](http://angular-user-settings-demo.surge.sh/).

## How to get started

First install all dependencies:

```bash
$ jspm install
$ npm install
```

To start the local development server:

```bash
$ node index.js
```

then navigate to: `<ip>:9000` in your browser.

## To push to surge

```bash
$ npm run build
$ npm run compile
$ surge
```

Only push the `/dist` directory to surge.

The `/dist/_jspm_packages` can be removed before pushing to surge.

## Development

For more details about the technical details, check out the [Angular Express boilerlate documentation](https://github.com/ngx-boilerplates/default).

## Change log

### v0.1.0

- Initial version
