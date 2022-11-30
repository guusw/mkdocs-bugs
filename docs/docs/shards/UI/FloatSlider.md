---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.FloatSlider

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | `None` |
| `<output>` ||The value produced. | | `Float` |
| `Label` | :fontawesome-solid-circle-plus:{title="Optional"}  | The text label for this widget. | `None` | `String ` |
| `Style` |  | The text style. | `None` | `{ Any } &{ Any }` |
| `Variable` |  | The variable that holds the input value. | `None` | `Float &Float` |
| `Min` |  | The minimum value. | `None` | `Float &Float` |
| `Max` |  | The maximum value. | `None` | `Float &Float` |

</div>

A numeric slider.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/FloatSlider/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/FloatSlider/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
