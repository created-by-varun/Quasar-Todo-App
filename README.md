# Todo (quasar-todo)

A Quasar Framework app   
**Live Link: https://todo-quasar.netlify.app/**    
  
Quasar (pronounced /ˈkweɪ.zɑɹ/) is an MIT licensed open-source Vue.js based framework, which allows you as a web developer to quickly create responsive++ websites/apps in many flavours:

    SPAs (Single Page App)
    SSR (Server-side Rendered App) (+ optional PWA client takeover)
    PWAs (Progressive Web App)
    BEX (Browser Extension)
    Mobile Apps (Android, iOS, …) through Cordova or Capacitor
    Multi-platform Desktop Apps (using Electron)

## Install the dependencies
```bash
npm install -g @quasar/cli
npm install
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```


### Build the app for production
```bash
# build for production
$ quasar build

# SSR
$ quasar build -m ssr

# PWA
$ quasar build -m pwa

# Mobile App
$ quasar build -m cordova -T [android|ios]
# or the short form:
$ quasar build -m [android|ios]

# passing extra parameters and/or options to
# underlying "cordova" executable:
$ quasar build -m ios -- some params --and options --here

# Electron App
$ quasar build -m electron
```

### Customize the configuration
See [Configuring quasar.conf.js](https://quasar.dev/quasar-cli/quasar-conf-js).
