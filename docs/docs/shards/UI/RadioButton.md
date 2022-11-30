---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.RadioButton

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | `None` |
| `<output>` ||Indicates whether the radio button was clicked during this frame. | | `Bool` |
| `Label` | :fontawesome-solid-circle-plus:{title="Optional"}  | The text label of this radio button. | `None` | `String ` |
| `Variable` |  | The variable that holds the input value. | `None` | `Any &Any` |
| `Value` |  | The value to compare with. | `None` | `Any` |
| `Style` |  | The text style. | `None` | `{ Any } &{ Any }` |

</div>

A radio button for selecting a value amongst multiple choices.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/RadioButton/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/RadioButton/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/RadioButton/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/RadioButton/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
