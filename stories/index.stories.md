```js script
import { html } from '@open-wc/demoing-storybook';
import '../dw-virtual-list.js';

export default {
  title: 'DwVirtualList',
  component: 'dw-virtual-list',
  options: { selectedPanel: "storybookjs/knobs/panel" },
};
```

# DwVirtualList

A component for...

## Features:

- a
- b
- ...

## How to use

### Installation

```bash
yarn add dw-virtual-list
```

```js
import 'dw-virtual-list/dw-virtual-list.js';
```

```js preview-story
export const Simple = () => html`
  <dw-virtual-list></dw-virtual-list>
`;
```

## Variations

###### Custom Title

```js preview-story
export const CustomTitle = () => html`
  <dw-virtual-list title="Hello World"></dw-virtual-list>
`;
```
