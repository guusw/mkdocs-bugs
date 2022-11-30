---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# BigInt.Add

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Any valid big integer(s) represented as bytes supported by this operation. | | `Bytes [ Bytes ]` |
| `<output>` ||The result of the operation, usually in the same type as the input value. | | `Bytes [ Bytes ]` |
| `Operand` |  | The bytes variable representing the operand | `0` | `&Bytes &[ Bytes ]` |

</div>

Applies the binary operation on the input value and the operand and returns the result (or a sequence of results if the input and the operand are sequences).

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/BigInt/Add/Add.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/BigInt/Add/Add.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
