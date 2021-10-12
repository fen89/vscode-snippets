# Useful VS Code Snippets

Visual Studio Code Snippets for daily use with Angular, Vue, Typescript and Javascript.

![Use Extension](images/use-extension.gif)

See the [CHANGELOG](CHANGELOG.md) for the latest changes.

## Usage

Type part of a snippet, press `enter` and the snippet unfolds. Pressing space at anytime shows the description and preview of a snippet.

## General Snippets

| Snippet          | Description                                                                                       |
| ---------------- | ------------------------------------------------------------------------------------------------- |
| `import`         | Import entire module: `import Module from 'module'`                                               |
| `import-no-name` | Import entire module without module name: `import 'module'`                                       |
| `import-all`     | Import all as alias from module: `import * as alias from 'module'`                                |
| `import-part`    | Import only a specific part from a module: `import { part } from 'module'`                        |
| `import-as`      | Import only a specific part from a module with an alias: `import { part as alias } from 'module'` |
| `clog`           | Print a message to the console: `console.log(message)`                                            |
| `clogo`          | Print object to the console: `console.log('object': object)`                                      |
| `cwarn`          | Print warning to console: `console.warn(message)`                                                 |
| `ccount`         | Print occurrences to console: `console.count(message)`                                            |
| `cdir`           | Print object represantation: `console.dir(object)`                                                |
| `cerror`         | Print error: `console.error(object)`                                                              |
| `ctable`         | Print a collection as table: `console.table(collection)`                                          |

## Typescript Snippets

| Snippet    | Description                             |
| ---------- | --------------------------------------- |
| `ts-class` | Class with `Partial` constructor assign |

## Angular Snippets

| Snippet                  | Description                                |
| ------------------------ | ------------------------------------------ |
| `ng-module`              | Module                                     |
| `ng-module-with-routing` | Module with Routing (for child)            |
| `ng-service`             | Service (provided in root)                 |
| `ng-component`           | Component (change detection on push)       |
| `ng-directive`           | Directive                                  |
| `ng-guard`               | Guard (can activate)                       |
| `ng-interceptor`         | Http Interceptor                           |
| `ng-pipe`                | Pipe                                       |
| `ng-route-404`           | 404 Route                                  |
| `ng-route-default`       | Default Route                              |
| `ng-route-eager`         | Eager loaded Route                         |
| `ng-route-lazy`          | Lazy loaded Route (with new import syntax) |
| `ng-route-children`      | Route with children                        |
| `ng-output`              | `@Output` event emitter                     |

## Vue 3 Snippets

### General


| Snippet                        | Description                                    |
| ------------------------------ | ---------------------------------------------- |
| `vue-sfc`                      | Vue Single File Component                      |
 
### Javascript / Typescript

| Snippet                               | Description                                             |
| ------------------------------------- | ------------------------------------------------------- |
| `vue-import-component`                | Import a component                                      |
| `vue-import-component-dynamic`        | Import a lazy loaded component                          |
| `vue-import-lib`                      | Import a library                                        |
| `vue-define-component`                | Vue Typescript component                                |
| `vue-test`                            | Unit test Single File Component                         |
| `vue-prop`                            | Vue Composition API - prop                              |
| `vue-ref`                             | Vue Composition API - ref                               |
| `vue-reactive`                        | Vue Composition API - reactive                          |
| `vue-computed`                        | Vue Composition API - computed                          |
| `vue-watch`                           | Vue Composition API - `watch()` for single source       |
| `vue-watch-array`                     | Vue Composition API - `watch()` for array of sources    |
| `vue-watcheffect`                     | Vue Composition API - `watchEffect()`method             |
| `vue-life-onmounted`                  | Vue Composition API - `onMounted()` Lifecycle hook      |
| `vue-life-onbeforemount`              | Vue Composition API - `onBeforeMount()` Lifecycle hook  |
| `vue-life-onbeforeupdate`             | Vue Composition API - `onBeforeUpdate()` Lifecycle hook |
| `vue-life-onupdated`                  | Vue Composition API - `onUpdated()` Lifecycle hook      |
| `vue-life-onerrorcaptured`            | Vue Composition API - `onErrorCaptured()` Lifecycle hook|
| `vue-life-onbeforeunmount`            | Vue Composition API - `onBeforeUnmount()` Lifecycle hook|
| `vue-life-onunmounted`                | Vue Composition API - `onUnmounted()` Lifecycle hook    |

### Html

Before these snippets started with only `v-`. New syntax starts with `vue-`.

| Snippet            | Description                                        |
| ----------------   | -------------------------------------------------- |
| `vue-html`         | Bind HTML directly to an element with `:html`      |
| `vue-class`        | Bind CSS class to an element with `:class`         |
| `vue-if`           | Conditional statement                              |
| `vue-if-else`      | Conditional statement with else clause             |
| `vue-if-else-if`   | Conditional statement with else-if and else clause |
| `vue-show`         | Displaying or hiding an element with `v:show`      |
| `vue-for`          | Loop                                               |
| `vue-for-index`    | Indexed loop                                       |
| `vue-for-object`   | L                                                  |
| `vue-for-range`    | Loop over a range                                  |
| `vue-on`           | Event Listener                                     |
| `vue-on-args`      | Event Listener with arguments                      |
| `vue-on-modified`  | Event Listener with event modifier                 |
| `vue-model`        | Model                                              |
| `vue-model-number` | Model with type number                             |


## Vue 2 Snippets

### General

| Snippet                        | Description                                    |
| ------------------------------ | ---------------------------------------------- |
| `vue2-component`               | Vue Class Component                            |


### Typescript

| Snippet              | Description                                                       |
| -------------------- | ----------------------------------------------------------------- |
| `vue2-global-component` | Register a global component                                       |
| `vue2-router-class`     | Router Class                                                      |
| `vue2-route-default`    | Default Route                                                     |
| `vue2-route-eager`      | Eager loaded Route                                                |
| `vue2-route-lazy`       | Lazy loaded Route                                                 |
| `vue2-route-children`   | Route with children                                               |
| `vue2-component`        | Component with `vue-class-component` and `vue-property-decorator` |
| `vue2-store`            | Dynamic Vuex Store                                                |
| `vue2-store-module`     | Dynamic Vuex Store Module                                         |
| `vue2-model`            | Interface and class with `create` and `update` functions          |

### Typescript Class Component

All of them need a reference to `vue-property-decorator`.

Prior these snippets started with only `v-`. New syntax starts with `vue2-class-` as these are legacy snippets.

| Snippet                        | Description                                    |
| ------------------------------ | ---------------------------------------------- |
| `vue2-component`               | Generates a vue single class component         |
| `vue2-class-prop`              | Property                                       |
| `vue2-class-prop-default`      | Property with default value                    |
| `vue2-class-prop-sync`         | Reactive Property                              |
| `vue2-class-prop-sync-default` | Reactive Property with default value           |
| `vue2-class-model`             | Model                                          |
| `vue2-class-watch`             | Watcher                                        |
| `vue2-class-watch-options`     | Watcher with default options                   |
| `vue2-class-emit`              | Event Emitter - method name is used as `$emit` |
| `vue2-class-emit-self`         | Event Emitter - name is used as `$emit`        |
| `vue2-class-ref`               | Reference to another component                 |
| `vue2-class-ref-key`           | Reference to another HTML element              |

## Emmet

If you want intellisense to show emmet before the snippets, you can force the emmet suggestions to show up at the top, by add the following to your editor user settings:

```javascript
{
  "emmet.showSuggestionsAsSnippets": true,
  "editor.snippetSuggestions": "top"
}
```
