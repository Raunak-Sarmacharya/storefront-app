<p align="center">
  <img src="https://flb-assets.s3.ap-southeast-1.amazonaws.com/static/storefront-logo.svg" width="380" height="100" />
</p>
<p align="center">
Open source ecommerce mobile app for on-demand orders. Setup ecommerce marketplace or shop.
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@fleetbase/sdk">
    <img src="https://img.shields.io/npm/v/@fleetbase/sdk" alt="Version" />
  </a>
  <a href="https://www.npmjs.com/package/@fleetbase/sdk">
    <img src="https://img.shields.io/npm/dw/@fleetbase/sdk" alt="Downloads/week" />
  </a>
  <a href="https://bundlephobia.com/package/@fleetbase/sdk@1.0.0">
    <img src="https://img.shields.io/bundlephobia/min/@fleetbase/sdk" alt="Bundle Size" />
  </a>
  <a href="https://github.com/fleetbase/fleetbase-js/blob/master/LICENSE.md">
    <img src="https://img.shields.io/github/license/fleetbase/fleetbase-js" alt="License" />
  </a>
  <br>
  <a href="https://fleetbase.io">fleetbase.io</a> | <a href="https://twitter.com/fleetbase_io">@fleetbase_io</a> | <a href="https://discord.gg/fjP4sReEvH">Discord</a>
</p>

<p align="center">
  <img src="https://flb-assets.s3.ap-southeast-1.amazonaws.com/static/storefront-app-preview.png" width="224" height="385" />
</p>

## Powered by Fleetbase & Storefront SDK

### Installation

```
git clone git@github.com:fleetbase/storefront-app.git
cd storefront-app
yarn
npx pod-install
touch .env
```

### Configure Environment

In your .env file supply your Storefront store key, your Fleetbase API secret key, your google maps api key. 
Currently the Storefront app can only use the Stripe payment gateway, to use the Stripe gateway plug your Stripe 
api key. You'll also need to supply your app/bundle identifier. 

```
# .env

STOREFRONT_KEY=
FLEETBASE_KEY=
GOOGLE_MAPS_KEY=
STRIPE_KEY=
APP_IDENTIFIER=
```

### Running the App in iOS Simulator

```
npx react-native run-ios
```

### Running the App in Android Simulator

```
npx react-native run-ios
```

## Documentation

See the [documentation webpage](https://fleetbase.io/docs).

If you would like to make contributions to the Fleetbase Javascript SDK documentation source, here is a [guide](https://github.com/fleetbase/fleetbase-js/blob/master/CONTRIBUTING.md) in doing so.

## Roadmap

 - Global state management with redux
 - Write proper react hooks for sdks
 - Add debounce on products search
 - Add network/marketplace views