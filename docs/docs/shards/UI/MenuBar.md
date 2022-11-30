---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.MenuBar

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the Contents shards of the menu bar. | | `Any` |
| `<output>` ||A boolean value indicating whether the menu bar is active. | | `Bool` |
| `Contents` | :fontawesome-solid-circle-plus:{title="Optional"}  | The UI contents. | `None` | `Shard [ Shard ]` |

</div>

The menu bar goes well in a `UI.TopPanel`.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/MenuBar/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/MenuBar/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
