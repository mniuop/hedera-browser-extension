# Hedera browser extension for Firefox

<a href="https://www.mozilla.org/firefox/new/" target="_blank">
  <img src="https://cdn.rawgit.com/RDCH106/i-love-firefox/183266a9/get-firefox.png" alt="Get Firefox" border="0"/>
</a>

![CircleCI](https://img.shields.io/circleci/project/github/hashgraph/hedera-browser-extension/master.svg?label=circleci)

## Dependencies

```bash
# all dependencies in package.json
npm i
# keep prettier-stylelint separate
npm i -g prettier-stylelint
```

## Contributing / Development

```bash
npm run dev
```

## Test Firefox extension

-   Navigate to about:debugging in Firefox Browser;
-   Click on 'Load Temporary Add-on...';
-   Go to the Wallet folder;
-   Upload the extension.

## Tips (for manifest.json)

- Set a unique id for each extension (not required if you use web-ext run);
- Set a minimal version of Firefox on which the extension works (not mandatory).

## License

Copyright (c) 2018-present, Hedera Hashgraph LLC.

Licensed under Apache-2.0
