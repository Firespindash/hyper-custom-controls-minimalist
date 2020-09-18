# hyper-custom-controls-minimalist

> A minimalist version of the hyper-custom-controls by @guilhermerodz

It does autohide titlebar and hamburger menu by default, but it is not configurable yet.
And it is just a code example and probably can't be installed for now, because i don't have enough time nor a npm login to publish it.
The real change is in the `index.js` file and you should be able to copy it over the @guilhermerodz/hyper-custom-controls-minimalist `index.js` and it works.

> Add Mac-like controls to Hyper Terminal, but highly customizable

*A screenshot taken in KDE linux environment* \
![The visual approach](https://raw.githubusercontent.com/Firespindash/hyper-custom-controls-minimalist/master/media/result.png)

## Configuration

In your `~/.hyper.js`, you can configure settings for `hyper-custom-controls`.

```js
modules.exports = {
  config: {
    // NOTE: All properties below are optional and have a default value.
    hyperCustomControls: {
      side: 'left', // Default: 'left'
      circleSize: 11, // Default: 11
      circleGap: 7.5, // Default: 7.5
      distanceToSide: 15, // Default: 15
      opacity: 1, // Default: 1
      hoverOpacity: 0.5, // Default: 0.5

      // Default controls below:
      // NOTE: You can remove a control, if you want to.
      controls: [
        {
          type: 'close',
          color: '#F24F55',
        },
        {
          type: 'minimize',
          color: '#FBC536',
        },
        {
          type: 'maximize',
          color: '#39EA48',
        },
      ],
    },
  },
};
```
