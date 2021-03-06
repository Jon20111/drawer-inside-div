# drawer-inside-div
A preconfigured Material-UI Drawer nested under an AppBar and inside a div

Read here to understand the [Stlying and Positioning](https://smartdevpreneur.com/how-to-position-a-material-ui-drawer-inside-a-container/)

## Table of Contents

- [Features](#features)
- [Implementation](#implementation)
- [Contributors](#contributors)
- [License](#license)

## Features

Material-UI Drawer nested under an AppBar and inside a div.
Can be anchored:
- left
- right

All the usual props can be passed to the AppBar and Drawer.

Toolbar Icon can be customized but click handler is set to open Drawer.

## Implementation

Install the Drawer:

```
npm install @jon20111/drawer-inside-div
```

Import the Drawer:
```js
import { DrawerInsideDiv } from '@jon20111/drawer-inside-div'
```
The filter takes the following props:
- appBarComponent: Use this to pass a component to the AppBar
- appBarIcon: Custom AppBar icon
- anchor: 'left' or 'right' to anchor to a side
- drawerComponent: The child component to be injected into the Drawer
- appBarProps: All the usual AppBar props
- drawerProps: All the usual Drawer props

## Contributors

Jon Middaugh (https://github.com/Jon20111) and (https://smartdevpreneur.com/)

## License

MIT @jon20111
