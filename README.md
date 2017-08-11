# popover

> [Element](https://github.com/ElemeFE/element) Popover clone, and did just a little change. If you have a better idea of this component improvement, please share it and I will update it immediately.

## Install

```bash
npm install vue-multiple-popover -S
```

## Quick Start

```bash
import Vue from 'vue'
import Popover from 'vue-multiple-popover'
Vue.use(Popover)
```

then, you can use:

```
    <vm-popover
        ref="popover"
        title="Title"
        content="your content">
    </vm-popover>
    <button v-popover:popover></button>
```

OR

```bash
import Vue from 'vue'
import {Popover,  directive} from 'vue-multiple-popover'
Vue.component('vm-popover', Popover)
Vue.directive('vm-popover', directive)
```

then, you can use:

```
    <vm-popover
        ref="popover"
        title="Title"
        content="your content">
    </vm-popover>
    <button v-vm-popover:popover></button>
```


For more information, please refer to [Popover](https://vue-multiple.github.io/popover) in our documentation.

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run demo:dev

# build for demo with minification
npm run demo:build

# build for gh-pages with minification
npm run demo:prepublish

# build for production with minification
npm run build

# generate gh-pages
npm run deploy
```

## LICENSE

[MIT](http://opensource.org/licenses/MIT)