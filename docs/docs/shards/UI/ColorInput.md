---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.ColorInput

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | `None` |
| `<output>` ||The selected color | | `Color` |
| `Variable` | :fontawesome-solid-circle-plus:{title="Optional"}  | The variable that holds the input value. | `None` | `Color &Color ` |

</div>

A widget where a color can be selected.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/ColorInput/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/ColorInput/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
