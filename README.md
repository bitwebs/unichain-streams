# unichain-streams

External implementation of a WriteStream and ReadStream for Unichain

```
npm install @web4/unichain-streams
```

## Usage

``` js
const { WriteStream, ReadStream } = require('@web4/unichain-streams')

const ws = new WriteStream(feed)
const rs = new ReadStream(feed, {
  start: 0,
  live: true,
  valueEncoding: 'json'
})
```

## License

MIT
