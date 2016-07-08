# bem-flex

A simple flex helper SASS with [BEM](https://css-tricks.com/bem-101/) fashion.

For now, only SASS is supported.

## Install

1. Install the package

  ```sh
  npm i --save bem-flex
  ```

2. Add the SCSS file in your project's SCSS file, etc.

  ```scss
  @import "node_modules/bem-flex/main";
  ```

## Example

```html
<div class="display--flex">     <!-- display: flex -->
  <div class="flex--one">       <!-- flex: 1 -->
    Hello World
  </div>
  <button class="flex--center"> <!-- self-align: center -->
    Click me
  </button>
</div>
```

## API

```
.display--flex
.flex--center
.flex--end
.flex--column

.flex-wrap--nowrap
.flex-wrap--wrap
.flex-wrap--wrap-reverse

.flex--one
.flex--two
...
.flex--eleven
.flex--twelve
```

## License

[WTFPL](/LICENSE.md)
