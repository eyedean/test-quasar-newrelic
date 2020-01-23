# Test Quasar New Relic SPA Pro agent (test-quasar-newrelic)

Testing Quasar and New Relic SPA Pro app

## Install the dependencies
```bash
npm install
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
You need [quasar-cli](https://quasar.dev/quasar-cli/installation) to be installed.  It can be achieved via `npm i -g @quasar/cli`.

Then, simply:
```bash
quasar dev
```

### [Optional] Build the app for production
```bash
quasar build && quasar server dist/spa --history -o
```

### Other notes:
#### Changing history mode (hash vs history)
It can be done by changing `vueRouterMode` in `quasar.conf.js`