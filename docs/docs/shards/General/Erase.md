---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Erase

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Any input is ignored. | | `Any` |
| `<output>` ||The input to this shard is passed through as its output. | | `Any` |
| `Indices` |  | One or multiple indices to filter from a sequence. | `None` | `Int [ Int ] &Int &[ Int ] String [ String ] &String &[ String ]` |
| `Name` |  | The name of the variable. | `""` | `String &Any` |
| `Key` |  | The key of the value to read/write from/in the table (this variable will become a table). | `None` | `String` |
| `Global` |  | If the variable is or should be available to all of the wires in the same mesh. | `false` | `Bool` |

</div>

Deletes identified element(s) from a sequence or key-value pair(s) from a table.

## Details

--8<-- "details/shards/General/Erase.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Erase/Erase.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Erase/Erase.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
