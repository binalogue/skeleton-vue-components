<template>
  <div :class="$style.hello">
    HelloA
  </div>
</template>

<style module>
.hello {
  color: orange;
}
</style>

<info>
{
  "description": "A component that says \"HelloA\" with orange text."
}
</info>

<example>
  <!-- No props or content are necessary. -->
  <hello-a></hello-a>
</example>
