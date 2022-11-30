---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.IntSlider

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | `None` |
| `<output>` ||The value produced. | | `Int` |
| `Label` | :fontawesome-solid-circle-plus:{title="Optional"}  | The text label for this widget. | `None` | `String ` |
| `Style` |  | The text style. | `None` | `{ Any } &{ Any }` |
| `Variable` |  | The variable that holds the input value. | `None` | `Int &Int` |
| `Min` |  | The minimum value. | `None` | `Int &Int` |
| `Max` |  | The maximum value. | `None` | `Int &Int` |

</div>

A numeric slider.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/IntSlider/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/IntSlider/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/IntSlider/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/IntSlider/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
