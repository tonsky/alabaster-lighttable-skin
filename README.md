# Light skin & theme for LightTable

![Alabaster Preview](https://github.com/tonsky/alabaster-lighttable-skin/blob/master/preview.jpg)

## Prerequisites

- This skin plays well with [Fira Code](https://github.com/tonsky/FiraCode), you might want to install it
- Rainbow plugin (install through LightTable `Plugins: Show plugin manager`)

## Installation

1. Go to `Plugins: Show plugin manager` → `Available`
2. Search for `Alabaster`
3. Install
4. Go to `Settings: User behaviors` and add:

```clj
  [:app :lt.objs.style/set-skin "alabaster"]
  [:editor :lt.objs.style/set-theme "alabaster"]
  [:editor :lt.objs.style/font-settings "Fira Code" 9 1.7]
```

