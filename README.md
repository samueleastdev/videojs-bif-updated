## Getting Started

#### Include

```html
<script src="/path/to/videojs.bif.min.js"></script>
```

#### Enable

```js
// Generally BIF files are large, so you have the ability to manage fetching on your own.
// If this is the route you take, you can update plugin configuration at any time by rerunning the plugin.
//
// See documentation or example for more detail.
videojs('player_id').bif({
  src: '/path/to/bif.bif',
});
```

> Note: There are multiple ways to enable plugins. For more information, please visit [Video.js](https://github.com/videojs/video.js).

## Contributing + Example

```bash
npm install -g grunt-cli

npm install

npm start
```

## License

Code licensed under [The MIT License](https://github.com/chemoish/videojs-bif/blob/master/LICENSE).
