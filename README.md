![build](https://github.com/chibat/chrome-extension-typescript-starter/workflows/build/badge.svg)

# VerifyPage - Chrome Browser Extension
You can install this extension from the Chrome-App-Store [here](https://chrome.google.com/webstore/detail/verifypage/gadnjidhhadchnegnpadkibmjlgihiaj?hl=en-GB&authuser=0). Current Version 1.2.

This is a verification client for the micro-pkc https://github.com/inblockio/micro-PKC
it uses the CLI verification tool as an external dependency https://github.com/inblockio/data-accounting-external-verifier. If you want the latest build, or you want to build it yourself, follow the instructions given here.

Chrome Extension, TypeScript, HTML

## Prerequisites

* [node + npm](https://nodejs.org/) (Current Version)

## Includes the following

* TypeScript
* Webpack
* React
* Jest
* Example Code
    * Chrome Storage
    * Options Version 2
    * content script
    * count up badge number
    * background

## Project Structure

* src/typescript: TypeScript source files
* src/assets: static files
* dist: Chrome Extension directory
* dist/js: Generated JavaScript files

## Setup

```
npm install
```

## Build

```
npm run build
```

## Build in watch mode

### terminal

```
npm run watch
```

## Load extension to chrome
Open Chrome.

Enter 'chrome://extensions' in the URL.

Enable Developer Mode in the top right hand corner of the screen.

If the Dist folder has been compressed or zipped, extract it.

Click the Load unpacked button in the top left hand corner of the screen, then select the extracted Dist folder from the previous step.

The VerifyPage extension should now be visible and enabled in the extensions list.

You can also load a pre-build version of the extension.

## Test
`npx jest` or `npm run test`
