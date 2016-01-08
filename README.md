# bem-flex

bem-flex is a simple flex helper SASS with [BEM](https://css-tricks.com/bem-101/) fashion.

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

## Usage

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

## License

[WTFPL](/LICENSE.md)
