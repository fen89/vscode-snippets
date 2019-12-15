# Useful VS Code Snippets

Visual Studio Code Snippets for daily use with Angular, Vue, Typescript and Javascript.

![Use Extension](images/use-extension.gif)

See the [CHANGELOG](CHANGELOG.md) for the latest changes.

## Usage

Type part of a snippet, press `enter` and the snippet unfolds. Pressing space at anytime shows the description and preview of a snippet.

### General Snippets

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

### Typescript Snippets

| Snippet    | Description                             |
| ---------- | --------------------------------------- |
| `ts-class` | Class with `Partial` constructor assign |

### Angular Typescript Snippets

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
| `ng-output`              | `@Output`event emitter                     |

### Vue Typescript Snippets

| Snippet              | Description                                                       |
| -------------------- | ----------------------------------------------------------------- |
| `v-global-component` | Register a global component                                       |
| `v-router-class`     | Router Class                                                      |
| `v-route-default`    | Default Route                                                     |
| `v-route-eager`      | Eager loaded Route                                                |
| `v-route-lazy`       | Lazy loaded Route                                                 |
| `v-route-children`   | Route with children                                               |
| `v-component`        | Component with `vue-class-component` and `vue-property-decorator` |
| `v-store`            | Dynamic Vuex Store                                                |
| `v-store-module`     | Dynamic Vuex Store Module                                         |
| `v-model`            | Interface and class with `create` and `update` functions          |

### Vue Typescript Class Component Snippets

All of them need a reference to `vue-property-decorator`

| Snippet               | Description                                    |
| --------------------- | ---------------------------------------------- |
| `v-prop`              | Property                                       |
| `v-prop-default`      | Property with default value                    |
| `v-prop-sync`         | Reactive Property                              |
| `v-prop-sync-default` | Reactive Property with default value           |
| `v-model`             | Model                                          |
| `v-watch`             | Watcher                                        |
| `v-watch-options`     | Watcher with default options                   |
| `v-emit`              | Event Emitter - method name is used as `$emit` |
| `v-emit-self`         | Event Emitter - name is used as `$emit`        |
| `v-ref`               | Reference to another component                 |
| `v-ref-key`           | Reference to another HTML element              |

### Vue Html Snippets

| Snippet          | Description                                        |
| ---------------- | -------------------------------------------------- |
| `v-html`         | Bind HTML directly to an element with `:html`      |
| `v-class`        | Bind CSS class to an element with `:class`         |
| `v-if`           | Conditional statement                              |
| `v-if-else`      | Conditional statement with else clause             |
| `v-if-else-if`   | Conditional statement with else-if and else clause |
| `v-show`         | Displaying or hiding an element with `v:show`      |
| `v-for`          | Loop                                               |
| `v-for-index`    | Indexed loop                                       |
| `v-for-object`   | L                                                  |
| `v-for-range`    | Loop over a range                                  |
| `v-on`           | Event Listener                                     |
| `v-on-args`      | Event Listener with arguments                      |
| `v-on-modified`  | Event Listener with event modifier                 |
| `v-model`        | Model                                              |
| `v-model-number` | Model with type number                             |

## Emmet

If you want intellisense to show emmet before the snippets, you can force the emmet suggestions to show up at the top, by add the following to your editor user settings:

```javascript
{
  "emmet.showSuggestionsAsSnippets": true,
  "editor.snippetSuggestions": "top"
}
```
