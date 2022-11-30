---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Menu

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the Contents shards of the menu. | | `Any` |
| `<output>` ||A boolean value indicating whether the menu is active. | | `Bool` |
| `Title` |  | The title of the menu. | `None` | `String` |
| `Contents` | :fontawesome-solid-circle-plus:{title="Optional"}  | The UI contents. | `None` | `Shard [ Shard ]` |

</div>

Creates a menu button that when clicked will show the given menu. 

      If called from within a menu this will instead create a button for a sub-menu.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Menu/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Menu/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
