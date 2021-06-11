# Instagram-Feed-Embed

[![GitHub package.json version][npm-image]][npm-url]
[![License][license-image]][license-url]

React component embedding users Instagram feed

```bash
yarn add instagram-feed-embed

# or

npm i instagram-feed-embed
```

## Screenshots

<img src="docs/screenshot.png" width="320" alt="screenshot">

[Live demo](https://instagram-feed-embed.vercel.app/)

## Usage

```tsx
import Feed from "instagram-feed-embed";

<Feed
  userName="javascript.js"
  limit={12}
  width={320}
  maxContainerHeight={510}
/>;
```

## props

- `userName` {String} Instagram User Name. Required
- `width` {Number} The width. Default `320`
- `maxContainerHeight` {Number} Max continer height. Default `510`
- `limit` {Number} Max limit. Maximum size is `12`. Default `12`

## License

[MIT][license-url]

[license-image]: https://img.shields.io/:license-mit-blue.svg?style=flat-square
[license-url]: https://raw.githubusercontent.com/Hamaad-Siddiqui/instagram-feed-embed/main/LICENSE
[npm-url]: https://www.npmjs.com/package/instagram-feed-embed
[npm-image]: https://img.shields.io/github/package-json/v/hamaad-siddiqui/instagram-feed-embed
