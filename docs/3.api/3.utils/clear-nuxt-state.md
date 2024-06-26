---
title: 'clearNuxtState'
description: Delete the cached state of useState.
links:
  - label: Исходники
    icon: i-simple-icons-github
    to: https://github.com/nuxt/nuxt/blob/main/packages/nuxt/src/app/composables/state.ts
    size: xs
---

::note
This method is useful if you want to invalidate the state of `useState`.
::

## Тип

```ts
clearNuxtState (keys?: string | string[] | ((key: string) => boolean)): void
```

## Параметры

- `keys`: One or an array of keys that are used in [`useState`](/docs/api/composables/use-state) to delete their cached state. If no keys are provided, **all state** will be invalidated.
