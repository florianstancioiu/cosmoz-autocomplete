# `cosmoz-autocomplete`

#### `render`

```html
<div
  class="chips"
  slot="prefix"
>
  <div class="chip">
    <span class="chip-text">
      Item 1
    </span>
    <iron-icon
      class="chip-clear"
      icon="clear"
    >
    </iron-icon>
  </div>
</div>
<paper-input
  aria-disabled="false"
  id="input"
  tabindex="0"
>
  <slot
    name="prefix"
    slot="prefix"
  >
  </slot>
  <slot
    name="suffix"
    slot="suffix"
  >
  </slot>
</paper-input>
```
