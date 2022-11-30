---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Combo

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||A sequence of values. | | `[ Any ]` |
| `<output>` ||The selected value. | | `Any` |
| `Label` | :fontawesome-solid-circle-plus:{title="Optional"}  | The text label of this checkbox. | `None` | `String ` |
| `Index` | :fontawesome-solid-circle-plus:{title="Optional"}  | The index of the selected item. | `None` | `Int &Int ` |
| `Width` |  | The width of the button and menu. | `None` | `Float &Float` |
| `Style` |  | The text style. | `None` | `{ Any } &{ Any }` |

</div>



## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Combo/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Combo/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Combo/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Combo/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
