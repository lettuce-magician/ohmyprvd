<div class="ompdoc-api-breadcrumbs">
<a href="../../../">Reference</a>
<a href="../../">Core</a>
<a href="../">Loader</a>
</div>

<div class="ompdoc-api-tags">
<span>function</span>
<span>since v0.1</span>
</div>

# loadDescendants

Preload the specified parent by requiring all `ModuleScripts` within it
recursively. An optional `predicate` function can be provided to filter modules.

=== "Luau"

    ```Lua
    function prvd.loadDescendants(
      parent: Instance,
      predicate: ((ModuleScript) -> boolean)?
    ): { unknown }
    ```

=== "TypeScript"

    ```TypeScript
    export const loadDescendants: (
      parent: Instance,
      predicate?: (module: ModuleScript) => boolean
    ) => unknown[]
    ```

---

## Parameters

### parent `#!lua : Instance`

The parent to load ModuleScripts from. Internally uses `#!lua :GetDescendants()`
to load modules.

### predicate `#!lua : (ModuleScript) -> boolean`

An optional predicate function that will be called to filter the modules to load
with.

---

## Learn More

- [Ignition tutorial](../../../tutorials/fundamentals/ignition.md)
