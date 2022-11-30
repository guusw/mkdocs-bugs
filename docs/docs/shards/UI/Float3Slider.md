---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Float3Slider

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | `None` |
| `<output>` ||The value produced. | | `Float3` |
| `Label` | :fontawesome-solid-circle-plus:{title="Optional"}  | The label for this widget. | `None` | `String ` |
| `Style` |  | The text style. | `None` | `{ Any } &{ Any }` |
| `Variable` |  | The variable that holds the input value. | `None` | `Float3 &Float3` |
| `Min` |  | The minimum value. | `None` | `Float3 &Float3` |
| `Max` |  | The maximum value. | `None` | `Float3 &Float3` |

</div>

A numeric slider.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Float3Slider/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Float3Slider/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
