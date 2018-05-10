# `<mtz-sweet-alert>` - a Polymer 1.x wrapper for [SweetAlert2](https://github.com/sweetalert2/sweetalert2)

<!--
```
<custom-element-demo height="450">
  <template>
    <link rel="import" href="sweet-alert.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<mtz-sweet-alert title="Oops..." text="Something went wrong!" type="error"></mtz-sweet-alert>

<script>
  document.querySelector('mtz-sweet-alert').open()
</script>
```

# Installation

```bash
bower install --save MaritzSTL/mtz-sweet-alert
```

# Usage

```html
<link rel="import" href="bower_components/mtz-sweet-alert/mtz-sweet-alert.html">

<mtz-sweet-alert type="success" title="Awesome"></mtz-sweet-alert>
