---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Grid

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the Contents shards of the grid. | | `Any` |
| `<output>` ||The output of this shard will be its input. | | `Any` |
| `Contents` | :fontawesome-solid-circle-plus:{title="Optional"}  | The UI contents. | `None` | `Shard [ Shard ]` |
| `Striped` | :fontawesome-solid-circle-plus:{title="Optional"}  | Whether to alternate a subtle background color to every other row. | `false` | `Bool &Bool ` |
| `MinWidth` |  | Minimum column width. | `None` | `Float &Float` |
| `MaxWidth` |  | Maximum column width. | `None` | `Float &Float` |
| `Spacing` |  | Spacing between columns/rows. | `None` | `Float2 &Float2` |

</div>

Simple grid layout.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Grid/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Grid/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
