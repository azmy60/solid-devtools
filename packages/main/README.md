<a href="https://github.com/thetarnav/solid-devtools/tree/main/packages/main#readme" target="_blank">
  <p>
    <img width="100%" src="https://assets.solidjs.com/banner?type=Devtools&background=tiles&project=Library" alt="Solid Devtools">
  </p>
</a>

# solid-devtools

The main package of Solid Devtools. It contains the following subpackages:

- [Debugger](https://github.com/thetarnav/solid-devtools/tree/main/packages/debugger#readme)
- [Extension Adapter](https://github.com/thetarnav/solid-devtools/tree/main/packages/extension-adapter#readme) _(this one is automatically enabled)_
- [Locator](https://github.com/thetarnav/solid-devtools/tree/main/packages/locator#readme)

## Getting started

### Installation

```bash
npm i solid-devtools
# or
yarn add solid-devtools
# or
pnpm add solid-devtools
```

### Attaching Debugger to your application

Currently you have to manually attach the debugger to the reactive graph of your application logic.

[**Follow this guide of the debugger**](https://github.com/thetarnav/solid-devtools/tree/main/packages/debugger#attaching-debugger-to-your-application)

```tsx
import { attachDebugger } from "solid-devtools"

// simply place the attachDebugger hook in the App component:
function App() {
  attachDebugger()
  return <>...</>
}
```

### Using the locator package

The `solid-devtools` package comes with the [Locator](https://github.com/thetarnav/solid-devtools/tree/main/packages/locator#readme) package included.

[**Follow this guide of the locator package**](https://github.com/thetarnav/solid-devtools/tree/main/packages/locator#Getting-Started)

## Changelog

See [CHANGELOG.md](./CHANGELOG.md).