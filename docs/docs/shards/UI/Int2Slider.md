---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Int2Slider

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | `None` |
| `<output>` ||The value produced. | | `Int2` |
| `Label` | :fontawesome-solid-circle-plus:{title="Optional"}  | The label for this widget. | `None` | `String ` |
| `Style` |  | The text style. | `None` | `{ Any } &{ Any }` |
| `Variable` |  | The variable that holds the input value. | `None` | `Int2 &Int2` |
| `Min` |  | The minimum value. | `None` | `Int2 &Int2` |
| `Max` |  | The maximum value. | `None` | `Int2 &Int2` |

</div>

A numeric slider.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Int2Slider/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Int2Slider/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
