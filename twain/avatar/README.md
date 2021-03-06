# `@twain/avatar`

> A circular image representing one person

## Usage

`npm -i @twain/avatar`

- [NPM](https://www.npmjs.com/package/@twain/avatar)
- [UNPKG](http://unpkg.com/@twain/avatar)

### React

```jsx
import Avatar from "@twain/avatar";
import "@twain/avatar.css";

<Avatar
  src="path/to/avatar.png"
  alt="some avatar"
  size={4}
  inset={true}
/>;
```

### CSS

First, link the stylesheet, relative to your platform.

```html
<span class="Avatar Avatar--size_4 Avatar--inset_true">
  <img src="path/to/avatar.png" alt="some avatar" />
</span>
```

## Properties

### size: `string | number`

Controls size in `8px` increments.

values: `3, 4, 5, 6, 7, 8, 9, "20px", "profile"`

### inset: `boolean`

Insets the component

## Theming with CSS Custom Properties

```css
:root {
  --twain-avatar-inset-color: white;
}
```