# Simplified style guide from official vuejs.org

## Essential

- multi-word component names (prevents conflicts with html names)
- component data must be a function (that returns an object)
- prop definitions should be as detailed as possible
- always use `key` with `v-for`
- scope component style (`scoped` attribute, css module, BEM convention, using unique css class name...)
- use `$_` to prefix private property names (e.g. `$_yourPluginName_`) to ovoid conflicts withg Vue properties

## Strongly recommended

- each component should be in its own file (CI will concatenate them)
- single file component should either be PascalCase of kebab-case (PascalCase better for completion in IDE, mixed case works better in case insensitive filesystems)
- base component (a.k.a presentational, dumb, or pure components) that apply app-specific styling should all begin with a specific prefix, such as `Base`, `App`, or `V` (they will be listed together, allows to import them globally with webpack)
- single instance component should begin with `The` to denote that there can be only one
- 

## See also
- [VueJs official style guide](https://vuejs.org/v2/style-guide/)
