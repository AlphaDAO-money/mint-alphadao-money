
# [Alpha Mint  :trident:](https://mint.alphadao.money)

---

- ***Mint*** is a web application to interactively build ***KRC compliant*** contracts out of components from OpenZeppelin for deployment on the [**KCC network**](https://kcc.io). 

- Select the kind of contract that you want, set your parameters and desired features, and ***Mint*** will generate all of the code necessary. 

- The resulting code is ready to be compiled and deployed on the [***KCC network***](https://kcc.io).

- Cureently supports ***KRC-20, KRC-721, KRC-1155, and Governor*** libraries.


![](https://i.ibb.co/tX2Nd5p/94-A34-FE1-3793-47-ED-B008-1250644-DDA5-A.jpg)

---

## Development 📦

```
git clone https://GitHub.com/AlphaDao1337/nft-alphadao-money

cd nft-alphadao-money 

cd packages

cd ui

sudo yarn install

sudo yarn run dev

```

- spins up a local server `@ 127.0.0.1:5000` to develop the ui.

- `packages/ui` is the interface built in Svelte.

- make your changes and refresh your browser to load your edits in real time. 

- `packages/core` contains the code generation logic.

---

## Embedding 🛏 

To embed ***Mint*** on your site, first include the script tag:

```html
<script async src="https://mint.alphadao.money/build/embed.js"></script>
```

Then place `<oz-wizard></oz-wizard>` in the body where you want ***Mint*** to load.

Optionally focus on a specific tab with the `data-tab` attribute as in `<oz-wizard data-tab="ERC721"></oz-wizard>`.
