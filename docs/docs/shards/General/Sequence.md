---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Sequence

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Any input is ignored. | | `Any` |
| `<output>` ||The input to this shard is passed through as its output. | | `Any` |
| `Name` |  | The name of the variable. | `""` | `String &Any` |
| `Key` | :fontawesome-solid-circle-plus:{title="Optional"}  | The key of the value to read/write from/in the table (parameter applicable only if the target variable is or will become a table). | `None` | `String &String ` |
| `Global` |  | If the variable is or should be available to all of the wires in the same mesh. | `false` | `Bool` |
| `Clear` |  | If we should clear this sequence at every wire iteration; works only if this is the first push; default: true. | `true` | `Bool` |
| `Types` |  | The sequence inner types to forward declare. | `Enum: 1 vendor: 0x66726167 type: 0x74797065` | `Type [ Type ] [ Type [ Type ] Self ]` |

</div>

Creates an empty sequence (or table if a key is passed).

## Details

--8<-- "details/shards/General/Sequence.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Sequence/Sequence.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Sequence/Sequence.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
