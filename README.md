> ⚠️ This project is in early development. The architecture is in place, but many parts are still being implemented. Contributions, feedback, and discussion are welcome!

# purescript-fractile

A **cross-platform UI library** for building declarative layouts and reactive user interfaces using PureScript.

## Features

- **Cross-platform support**: `Layout` and `Drawing` abstractions for both web and native applications
- **Reactive and Modular**: Built around [purescript-signal](https://pursuit.purescript.org/packages/purescript-signal/13.0.0) with a cute `Action` newtype wrapping `Effect` and the `Live` monad, making composition and state management a breeze.
- **Pure and functional**: No side-effects in UI construction — everything is purely functional.

### 🧩 Separation of Concerns: UI Code is Stateless 🧩

The UI code is completely state-free — it only defines how the layout should look based on the given data. State management is handled separately.

### ⚡ No Diffing, Just Updates ⚡

Changes in state trigger **immediate updates** to the DOM — **exactly** where and when needed, with **no diffing**. This keeps the UI fast and efficient.

## Usage
