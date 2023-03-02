# Mirror World Marketplace Storefront Template

This repo contains a plug n' play template for the Mirror World SDK Marketplace.

## Pre-requisites
1. Have a developer account on [Mirror World Developer Dashboard](https://app.mirrorworld.fun)
2. Project API Key (Copy from your project on dashboard)
3. Collection Addresses (Copy from your project on dashboard)

## Usage
### 1. Clone this template repo:
```sh
git clone git@github.com:alexa0211/Axela-NFT-Marketplace.git
```

### 2. Install dependencies
```sh
yarn install
```

### 3. Setup storefront `userConfig.json` variables. Please put your API Key and Collection addresses in this config
Example config:
```json
{
  "collections": [
    "9uREUXzinvyfeVeuPccEws37GMUiZzpMbXjWawpcKGGs",
    "DJEuWxWma8SereaE4RyXm4ytWgVmiTEYmCzW3bEfUFhR",
    "AyFhBKnKtVVrXL6H42KgchhVDfSiRNEU8uzGvAA943Ho",
    "AK4tTnhsjHfFwDb37egvk79PBeZ6yjF78JYaZyjkgfVK"
  ],
  "xApiKey": "mw_3e7BQ7DSQSipzi9KyBlbHgvZKp1C30voZIG",
  "serviceFee": "4.25",
  "currencyOption": "SOL",
  "name": "Axela NFT Marketplace",
  "logo": "https://collections.mirrorworld.fun/1677793442999-Untitled design.png",
  "network": "devnet"
}
```


###  4. Run dev server
```sh
yarn dev
```

### 5. That's it! Deploy your static site!
You can deploy yoru Next.js site using [Vercel](https://vercel.com) or [Netlify](https://netlify.com), or [Cloudflare Pages](https://pages.cloudflare.dev).

## LICENSE
MIT License
