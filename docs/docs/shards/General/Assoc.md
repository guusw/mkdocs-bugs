---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Assoc

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Input sequence that defines which element in the target sequence or table needs to be updated and with what value. Should have even number of elements. | | `[ Any ]` |
| `<output>` ||Modified array or table. Has the same type as the array or table on which Assoc was applied. | | `[ Any ]` |
| `Name` |  | The name of the sequence or table to be updated. | `""` | `String &Any` |
| `Key` | :fontawesome-solid-circle-plus:{title="Optional"}  | Table key for the value that is to be updated. Parameter applicable if target is table. | `None` | `String &String ` |
| `Global` |  | If the variable is or should be available to all the wires in the same mesh. The default value (false) makes the variable local to the wire. | `false` | `Bool` |

</div>

Updates a sequence (array) or a table (associative array/ dictionary) on the basis of an input sequence.

## Details

--8<-- "details/shards/General/Assoc.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Assoc/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Assoc/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Assoc/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Assoc/2.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Assoc/3.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Assoc/3.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
