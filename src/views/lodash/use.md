# 安装/使用


## npm 安装

推荐使用 npm 的方式安装，它能更好地和 webpack 打包工具配合使用。
```shell
npm install @angxuejian/lodash --save
```

## 使用

### js 使用
在需要调用方法的 js文件中引入[jssdk文件](https://github.com/angxuejian/funcify/tree/main/package/lodash/umd/lodash.js)
``` js
import lodash from './umd/lodash.js' // 项目本地路径
// or
const lodash = require('./umd/lodash.js')
// or
<script src='./umd/lodash.js'></script>
```

### npm 使用
全部引用
```js
import lodash from '@angxuejian/lodash'
// or
const lodash = require('@angxuejian/lodash')
```

按需引用

在默认 **@angxuejian/lodash**路径后加入引入方法的名称即可
```js
import _isTypeOf from '@angxuejian/lodash/isTypeOf'
// or
const _isTypeOf = require('@angxuejian/lodash/isTypeOf')
```

## 全部方法
所有方法前缀都有 **_** 下划线

function | desc
---  | ---  
[_isTypeOf](#/lodash/isTypeOf) | 判断类型是否一致
[_toSpinalCase](#/loadsh/toSpinalCase) | 将驼峰命名转为脊柱命名
[_getDepthValue](#/lodash/getDepthValue) | 获取对象多层嵌套的值
[_getParams](#/loadsh/getParams) | 获取url中value值
[_ImageMode](#/lodash/ImageMode) | 图片模式
[_debounce](#/loadsh/debounce) | 防抖
[_throttle](#/loadsh/throttle) | 节流
[_hexToRgb](#/lodash/hexToRgb) | hex转rgb
[_hsvToRgb](#/loadsh/hsvToRgb) | hsv转rgb
[_rgbToHex](#/lodash/rgbToHex) | rgb转hex
[_rgbToHsv](#/loadsh/rgbToHsv) | rgb转hsv
[_Calendar](#/loadsh/rgbToHsv) | 日期对象
