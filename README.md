<p align="center">
  <img width="500px"  src="vue-adblock.png">
</p>

# 

- __Lead Maintainer:__ [David Roche][Lead]


Vue adblock is a plugin for vue js. It detects if a user visting your website has adblock running
in their browser. If adblock is running the plugin emit's a value back to the parent component.


- Post a [github issue][Issue],


## Install
To install via npm,

```
install vue-adblock
```

## Quick Example



```html
<template>
  <div id="app">
      <adblock @passValue="add = $event"></adblock>
  </div>
</template>
```

```js

import adblock from 'vue-adblock'

export default {
  name: 'app',
  components: {
    adblock
  },
  data () {
    return {
      add:''
    }
  }
}
```

```css
<style>

</style>

```

## Contributing

If you feel you can help in any way, be
it with bug reporting, documentation, examples, extra testing, or new features feel free
to [create an issue][Issue], or better yet, [submit a [Pull Request][Pull]. 




[Issue]: https://github.com/davidwroche/vue-adblock/issues
[Lead]: https://github.com/davidwroche
[Npm]: https://www.npmjs.com/package/vue-adblock
[Pull]: https://github.com/davidwroche/vue-adblock/pulls
