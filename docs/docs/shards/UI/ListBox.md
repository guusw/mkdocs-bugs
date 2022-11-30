---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.ListBox

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||A sequence of values. | | `[ Any ]` |
| `<output>` ||The selected value. | | `Any` |
| `Index` | :fontawesome-solid-circle-plus:{title="Optional"}  | The index of the selected item. | `None` | `Int &Int ` |

</div>



## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/ListBox/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/ListBox/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
