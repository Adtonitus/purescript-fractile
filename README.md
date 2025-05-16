> ⚠️ This project is in it's beginning phase, nothing works yet. Many parts are still being implemented. Contributions, feedback, and discussion are welcome!

# purescript-fractile

A **cross-platform Graphics library** for drawing graphics and building reactive user interfaces with PureScript.

## Features

### 🌐 Cross-Platform by Design 🌐

Platform-agnostic `Layout` and `Drawing` abstractions — declare your graphics once, render seamlessly across Web and Native.

### 🧩 Beautifully Stateless Code 🧩

The rendering code is completely free of state — instead, it purely defines how some Graphics should look based on the given data and which actions it may trigger. State management is handled separately.

### ⚙️ Reactive and Modular ⚙️

Built around [purescript-signal](https://pursuit.purescript.org/packages/purescript-signal/13.0.0) with a cute `Action` newtype wrapping `Effect` and the `Live` monad, making composition and state management a breeze.

### ⚡ No Diffing, Just Updates ⚡

Changes in state trigger **immediate updates** to the Graphics — **exactly** where and when needed, with **no diffing**. This keeps the UI fast and efficient.

## Usage
