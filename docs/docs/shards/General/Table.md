---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Table

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Any input is ignored. | | `Any` |
| `<output>` ||The input to this shard is passed through as its output. | | `Any` |
| `Name` |  | The name of the variable. | `""` | `String &Any` |
| `Key` | :fontawesome-solid-circle-plus:{title="Optional"}  | The key of the value to read/write from/in the table (parameter applicable only if the target variable is or will become a table). | `None` | `String &String ` |
| `Global` |  | If the variable is or should be available to all of the wires in the same mesh. | `false` | `Bool` |
| `Types` |  | The table inner types to forward declare. | `Enum: 1 vendor: 0x66726167 type: 0x74797065` | `Type [ Type ] [ Type [ Type ] Self ]` |

</div>

Creates an empty table.

## Details

--8<-- "details/shards/General/Table.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Table/Table.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Table/Table.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
