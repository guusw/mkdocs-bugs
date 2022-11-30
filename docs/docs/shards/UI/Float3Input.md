---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Float3Input

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | `None` |
| `<output>` ||The value produced. | | `Float3` |
| `Variable` |  | The variable that holds the input value. | `None` | `Float3 &Float3` |
| `Prefix` | :fontawesome-solid-circle-plus:{title="Optional"}  | Display a prefix before the number. | `None` | `String ` |

</div>

A numeric input.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Float3Input/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Float3Input/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
