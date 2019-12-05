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

### Typescript Angular Snippets

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
| `ng-route-eager`         | Eager Loaded Route                         |
| `ng-route-lazy`          | Lazy Loaded Route (with new import syntax) |
| `ng-route-children`      | Route with children                        |
| `ng-output`              | `@Output`event emitter                     |

### Typescript Vue Snippets

| Snippet             | Description                                                       |
| ------------------- | ----------------------------------------------------------------- |
| `vue-service`       | Service                                                           |
| `vue-router`        | Router                                                            |
| `vue-component`     | Component with `vue-class-component` and `vue-property-decorator` |
| `vue-prop`          | Property with `vue-property-decorator`                            |
| `vue-prop-default`  | Property with `vue-property-decorator` and default value          |
| `vuex-store`        | Dynamic Vuex Store                                                |
| `vuex-store-module` | Dynamic Vuex Store Module                                         |
| `vuex-model`        | Interface and class with `create` and `update` functions          |

## Emmet

If you want intellisense to show emmet before the snippets, you can force the emmet suggestions to show up at the top, by add the following to your editor user settings:

```javascript
{
  "emmet.showSuggestionsAsSnippets": true,
  "editor.snippetSuggestions": "top"
}
```
