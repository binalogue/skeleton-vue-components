# Skeleton Vue Components

> 🖖 An example component library built with Vue CLI 3

## Usage

### Directly in the browser

Drop the library in with a `<script>` tag alongside Vue to globally install all components:

```html
<div id="app">
  <hello-a></hello-a>
  <hello-b></hello-b>
</div>

<script src="https://unpkg.com/vue"></script>
<script src="https://unpkg.com/@binalogue/vue-components"></script>
<script>
  new Vue({ el: '#app' })
</script>
```

Or, if you only want to use a small subset of components, drop them in individually:

```html
<div id="app">
  <hello-a></hello-a>
  <hello-b></hello-b>
</div>

<script src="https://unpkg.com/vue"></script>
<script src="https://unpkg.com/@binalogue/vue-components/HelloA"></script>
<script src="https://unpkg.com/@binalogue/vue-components/HelloB"></script>
<script>
  new Vue({ el: '#app' })
</script>
```

### In a module system

Install the library with NPM:

```bash
npm install @binalogue/vue-components
```

Then register the library as a plugin to globally install all components:

```js
import BinawebVueComponents from '@binalogue/vue-components'

Vue.use(BinawebVueComponents)
```

Or, import components individually for local registration:

```js
import { HelloA, HelloB } from '@binalogue/vue-components'

export default {
  components: { HelloA, HelloB }
}
```

#### Individually packaged components

If you only want to use a small subset of components, only import individually packaged components to reduce the size of your application:

```js
import HelloA from '@binalogue/vue-components.HelloA'
import HelloB from '@binalogue/vue-components.HelloB'
```
