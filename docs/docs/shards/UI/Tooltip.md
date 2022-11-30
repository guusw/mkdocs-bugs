---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Tooltip

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to both the Contents and OnHover shards of the tooltip. | | `Any` |
| `<output>` ||The output of this shard will be its input. | | `Any` |
| `Contents` | :fontawesome-solid-circle-plus:{title="Optional"}  | The UI contents. | `None` | `Shard [ Shard ]` |
| `OnHover` | :fontawesome-solid-circle-plus:{title="Optional"}  | The tooltip contents. | `None` | `String Shard [ Shard ] ` |

</div>

Display a tooltip when the contents is hovered.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Tooltip/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Tooltip/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
