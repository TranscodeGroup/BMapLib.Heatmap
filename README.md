# BMapLib.Heatmap

## Installation

### NPM

```bash
$ npm i --save bmaplib.heatmap
```

### CDN

```html
<script src="//unpkg.com/bmaplib.heatmap"></script>
```

## Usage

### ES Next

```js
import Heatmap from 'bmaplib.heatmap'

// You should use this lib after BaiduMap loaded. For Example:

loadBaiduMap.then(() => {
  new Heatmap()
})
```

### CDN

```html
<script src="//api.map.baidu.com/api?v=2.0"></script>
<script src="//unpkg.com/bmaplib.heatmap"></script>
<script>
  new BMapLib.Heatmap()
</script>
```

## Related documents

- Source: [JavaScript API v3.0 > openlibrary](https://lbsyun.baidu.com/index.php?title=jspopular3.0/openlibrary#:~:text=wiki%EF%BC%9A%E6%9F%A5%E7%9C%8BWiki-,%E7%83%AD%E5%8A%9B%E5%9B%BE,-%E6%8F%90%E4%BE%9B%E7%83%AD%E5%8A%9B%E5%9B%BE)
- Reference: [BMapLib.HeatmapOverlay](https://api.map.baidu.com/library/Heatmap/2.0/docs/symbols/BMapLib.HeatmapOverlay.html)
