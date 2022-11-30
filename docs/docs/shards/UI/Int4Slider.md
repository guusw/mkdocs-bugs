---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Int4Slider

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | `None` |
| `<output>` ||The value produced. | | `Int4` |
| `Label` | :fontawesome-solid-circle-plus:{title="Optional"}  | The label for this widget. | `None` | `String ` |
| `Style` |  | The text style. | `None` | `{ Any } &{ Any }` |
| `Variable` |  | The variable that holds the input value. | `None` | `Int4 &Int4` |
| `Min` |  | The minimum value. | `None` | `Int4 &Int4` |
| `Max` |  | The maximum value. | `None` | `Int4 &Int4` |

</div>

A numeric slider.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Int4Slider/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Int4Slider/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Int4Slider/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Int4Slider/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
