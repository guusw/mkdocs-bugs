---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Int2Input

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | `None` |
| `<output>` ||The value produced. | | `Int2` |
| `Variable` |  | The variable that holds the input value. | `None` | `Int2 &Int2` |
| `Prefix` | :fontawesome-solid-circle-plus:{title="Optional"}  | Display a prefix before the number. | `None` | `String ` |

</div>

A numeric input.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Int2Input/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Int2Input/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
