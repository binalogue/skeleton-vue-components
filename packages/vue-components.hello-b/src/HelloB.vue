<template>
  <div :class="$style.hello">
    HelloB
  </div>
</template>

<style module>
.hello {
  color: green;
}
</style>

<info>
{
  "description": "A component that says \"HelloB\" with green text."
}
</info>

<example>
  <!-- No props or content are necessary. -->
  <hello-b></hello-b>
</example>
