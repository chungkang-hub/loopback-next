---
lang: en
title: 'Components'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/Components.html
---

## Overview

A `Component` is an extensibility class, which allows for creating various types
of LoopBack 4 extensions.

Apart from its own properties, `Component` class can have the following
properties:

- `controllers` - An array of [controller](Controllers.md) classes.
- `providers` - A map of providers to be bound to the application context.
- `classes` - A map of TypeScipt classes to be bound to the application context.
- `servers` - A map of name/class pairs for [servers](Server.md).
- `lifeCycleObservers` - An array of [life cycle observers](Life-cycle.md).
- `bindings` - An array of [bindings](Bindings.md) to be aded to the application
  context.

These properties contribute to the application to add additional features and
capabilities.

See [Using components](Using-components.md) and
[Creating components](Creating-components.md) for more information.
