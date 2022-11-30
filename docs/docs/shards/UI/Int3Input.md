---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Int3Input

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | `None` |
| `<output>` ||The value produced. | | `Int3` |
| `Variable` |  | The variable that holds the input value. | `None` | `Int3 &Int3` |
| `Prefix` | :fontawesome-solid-circle-plus:{title="Optional"}  | Display a prefix before the number. | `None` | `String ` |

</div>

A numeric input.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Int3Input/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Int3Input/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
