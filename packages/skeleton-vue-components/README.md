
# skeleton-vue-components

> 🖖 An example component library built with Vue CLI 3

## Installation

### Directly in the browser

Drop the library in with a `<script>` tag alongside Vue:

```html
<div id="app">
<!-- ... use components here ... -->
</div>

<script src="https://unpkg.com/vue"></script>
<script src="https://unpkg.com/@binalogue/skeleton-vue-components"></script>
<script>
new Vue({ el: '#app' })
</script>
```

Or, if you only want to use a small subset of components, drop them in individually:

```html
<div id="app">
<!-- ... use component here ... -->
</div>

<script src="https://unpkg.com/vue"></script>
<script src="https://unpkg.com/@binalogue/skeleton-vue-components/HelloA"></script>
<script>
new Vue({ el: '#app' })
</script>
```

### In a module system

Install the library with NPM:

```bash
npm install @binalogue/skeleton-vue-components
```

Then either import the library and either globally register all components with:

```js
import SkeletonVueComponents from '@binalogue/skeleton-vue-components'

Vue.use(SkeletonVueComponents)
```

or import and locally register a single component with:

```js
import { HelloA } from '@binalogue/skeleton-vue-components'

export default {
components: { SkeletonVueComponents }
}
```

#### Individually packaged components

If you only want to use a small subset of components, import only individually packaged components to reduce the size of your application:

```js
import HelloA from '@binalogue/skeleton-vue-components/HelloA'
import HelloB from '@binalogue/skeleton-vue-components/HelloB'
```
