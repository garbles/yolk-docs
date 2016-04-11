# Motivation

Yolk is a very small user interface library built on top of [RxJS 5](https://github.com/ReactiveX/RxJS/). With an
understanding of Observables and function composition, the conceptual leap from writing
[React](https://github.com/facebook/react) flavored JavaScript applications is very small. In addition, Yolk intentionally
exposes a very limited API so that you don't have spend weeks getting up to speed.

Yolk components consume RxJS observable streams as if they were plain values. From a websocket connection to a
generator function to an event handler. If it can be represented as an observable, then it can be rendered directly
into your markup.

Being able to describe user interactions, control flow and plain values as observable streams means that application
design becomes entirely declarative. There is no need to manually subscribe to observables in order to mutate or set
component state.
