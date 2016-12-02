# Angular2 QuickStart + Electron

This is a very barebones attempt at getting the [Angular2 Quickstart Application](https://github.com/angular/quickstart) running inside [Electron](http://electron.atom.io/). The assumption is that you'll grab this app and then cargo cult and massage it until it says something other than "Hello Angular".

# Obsolescence Warning

This was done in Dec 2016. Angular2 is moving at break-neck speed, so if you're looking at this after early 2017 and it hasn't been updated...well...there might be something worthwhile here, but it's probably too old to really represent the current state of Angular2.

The explict versions used here are:
- [Angular2 Quickstart App #2867b](https://github.com/angular/quickstart/commit/2867bc166145459a7ea7e25345a19311595fc93e) (Based on Angular Core 2.2.0)
- [Electron Prebuilt 1.4.10](https://github.com/electron/electron/tree/v1.4.10)

# Running It
```bash
npm install
npm run tsc
npm run electron
```

# Important files

- app/electron.ts - The Electron app that spawns the browser window and loads the HTML page with the Angular2 app in it.
- app/index.html - The HTML file loaded in the browser window
- app/main.ts - The entry point for the Angular app.
