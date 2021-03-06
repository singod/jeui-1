# JEUI

> Jeui a set of Vue 2.0 based high quality, simple, easy to use, lightweight front-end UI component library!

## Install

Using npm:
```
npm install jeui --save
```

## Start

Using a script tag for global use:
```html

<script src="https://cdn.jsdelivr.net/npm/vue"></script>
<script src="https://cdn.jsdelivr.net/npm/jeui"></script>

```
You can find more info [on the website](https://www.jemui.com/).

## Usage

```vue
<template>
  <je-layer v-model="show" >
    <p>Jeui a set of Vue 2.0 based high quality, simple, easy to use, lightweight front-end UI component library!</p>
  </je-layer>
</template>
<script>
  export default {
    data () {
      return {
        show: false
      }
    }
  }
</script>
```

Using css via `import`:

```js
import 'jeui/lib/jeui.css';
```

## License
[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2019-present, JEUI
