# react-reading-progress for TWBlog

> Reading progress bar component fork

**For my blog only**

## Install

```sh
$ npm i react-reading-progress
```

## Usage

```js
import ReadingProgress from 'react-reading-progress'

...

<ReadingProgress targetEl="#target-el" />

<article id="target-el">
  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Vel pharetra vel turpis nunc. Ut sem viverra aliquet eget sit amet tellus. Lacus suspendisse faucibus interdum posuere lorem ipsum dolor sit. In mollis nunc sed id semper risus in hendrerit gravida. Eleifend donec pretium vulputate sapien nec sagittis aliquam malesuada. Amet purus gravida quis blandit. Et ultrices neque ornare aenean euismod elementum nisi quis. Vitae aliquet nec ullamcorper sit amet.
</article>
```

## Props

### `targetEl={ String }`

Target article's selector. If this prop is not specified, `document.body` will be used.

### `rootEl={ String }`

Root element selector. If this prop is not specified, `window` will be used.


## License

MIT
