---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Push

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Input is the update value to be pushed into the variables. | | `Any` |
| `<output>` ||The input to this shard is passed through as its output. | | `Any` |
| `Name` |  | The name of the variable. | `""` | `String &Any` |
| `Key` | :fontawesome-solid-circle-plus:{title="Optional"}  | The key of the value to read/write from/in the table (parameter applicable only if the target variable is or will become a table). | `None` | `String &String ` |
| `Global` |  | If the variable is or should be available to all of the wires in the same mesh. | `false` | `Bool` |
| `Clear` |  | If we should clear this sequence at every wire iteration; works only if this is the first push; default: true. | `true` | `Bool` |

</div>

Updates sequences and tables by pushing elements and/or sequences into them.

## Details

--8<-- "details/shards/General/Push.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Push/Push.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Push/Push.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
