---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Drop

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Any input is ignored. | | `Any` |
| `<output>` ||The input to this shard is passed through as its output. | | `Any` |
| `Name` |  | The name of the variable. | `""` | `String &Any` |
| `Key` | :fontawesome-solid-circle-plus:{title="Optional"}  | The key of the value to read/write from/in the table (parameter applicable only if the target variable is or will become a table). | `None` | `String &String ` |
| `Global` |  | If the variable is or should be available to all of the wires in the same mesh. | `false` | `Bool` |

</div>

Drops the last element of the sequence variable passed in the `:Name` parameter. Works only on sequences.

## Details

--8<-- "details/shards/General/Drop.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Drop/Drop.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Drop/Drop.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
