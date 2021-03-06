# The MeteorFlux Project

*MeteorFlux is developed and maintained by [@luisherranz](https://github.com/LuisHerranz) from [@worona](https://github.com/worona).*


**MeteorFlux** are tools to use the **Flux architecture** in the **Meteor framework**.

There is more info about what is **Flux** and why you should use it in the [Dispatcher documentation](https://github.com/worona/meteorflux/tree/devel/packages/dispatcher).

## MeteorFlux - Dispatcher

A Flux Dispatcher for Meteor, based on Facebook's Dispatcher.

```
$ meteor add meteorflux:dispatcher
```

Check the [documentation here](https://github.com/worona/meteorflux/tree/devel/packages/dispatcher). It also explains the basics of Flux.

## MeteorFlux - Dispatcher Blaze Helper

A helper to dispatch Flux actions directly from Blaze.

```
$ meteor add meteorflux:dispatcher-helper
```

Check the [documentation here](https://github.com/worona/meteorflux/tree/devel/packages/dispatcher-helper).


## MeteorFlux - ReactiveState

ReactiveState is a reactive object tree to save complex state in Meteor. It also exposes that state to Blaze.

```
$ meteor add meteorflux:reactive-state
```

Check the [documentation here](https://github.com/worona/meteorflux/tree/devel/packages/reactive-state).

## MeteorFlux - First, Then, Finally! (FTF)

This is a **highly experimental** new framework for extensible Flux apps.

```
$ meteor add meteorflux:first-then-finally
```

Check the [documentation here](https://github.com/worona/meteorflux/tree/devel/packages/first-then-finally).

## MeteorFlux - FTF Blaze Helper

A helper to dispatch Flux actions directly from Blaze.

```
$ meteor add meteorflux:first-then-finally-blaze
```

Check the [documentation here](https://github.com/worona/meteorflux/tree/devel/packages/first-then-finally-blaze).

## MeteorFlux - FTF Debug

A simple package to see actions and their payloads on console while developing with FTF.

```
$ meteor add meteorflux:first-then-finally-debug
```

Check the [documentation here](https://github.com/worona/meteorflux/tree/devel/packages/first-then-finally-debug).

## MeteorFlux - AppState

**Deprecated, use ReactiveState or FTF instead.**

AppState is a single object tree to save all the state of your app in a MeteorFlux application. It also exposes that state to Blaze and forces you to modify the state of your app only responding to Flux actions.

It uses a single instance of ReactiveState in the background.

```
$ meteor add meteorflux:appstate
```

Check the [documentation here](https://github.com/worona/meteorflux/tree/devel/packages/appstate).
