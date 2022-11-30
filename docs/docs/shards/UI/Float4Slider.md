---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Float4Slider

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | `None` |
| `<output>` ||The value produced. | | `Float4` |
| `Label` | :fontawesome-solid-circle-plus:{title="Optional"}  | The label for this widget. | `None` | `String ` |
| `Style` |  | The text style. | `None` | `{ Any } &{ Any }` |
| `Variable` |  | The variable that holds the input value. | `None` | `Float4 &Float4` |
| `Min` |  | The minimum value. | `None` | `Float4 &Float4` |
| `Max` |  | The maximum value. | `None` | `Float4 &Float4` |

</div>

A numeric slider.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Float4Slider/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Float4Slider/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
