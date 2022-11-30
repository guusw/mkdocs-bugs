---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Checkbox

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | `None` |
| `<output>` ||Indicates whether the checkbox state changed during this frame. | | `Bool` |
| `Label` | :fontawesome-solid-circle-plus:{title="Optional"}  | The text label of this checkbox. | `None` | `String ` |
| `Variable` | :fontawesome-solid-circle-plus:{title="Optional"}  | The variable that holds the input value. | `None` | `Bool &Bool ` |
| `Style` |  | The text style. | `None` | `{ Any } &{ Any }` |

</div>

Boolean on/off widget with text label.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Checkbox/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Checkbox/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Checkbox/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Checkbox/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
