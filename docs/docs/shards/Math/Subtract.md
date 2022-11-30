---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Math.Subtract

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Any valid integer(s), floating point number(s), or a sequence of such entities supported by this operation. | | `Int Int2 Int3 Int4 Int8 Int16 Float Float2 Float3 Float4 Color [ Any ]` |
| `<output>` ||The result of the operation, usually in the same type as the input value. | | `Int Int2 Int3 Int4 Int8 Int16 Float Float2 Float3 Float4 Color [ Any ]` |
| `Operand` |  | The operand for this operation. | `0` | `Int &Int Int2 &Int2 Int3 &Int3 Int4 &Int4 Int8 &Int8 Int16 &Int16 Float &Float Float2 &Float2 Float3 &Float3 Float4 &Float4 Color &Color [ Any ] &[ Any ]` |

</div>

Applies the binary operation on the input value and the operand and returns the result (or a sequence of results if the input and the operand are sequences).

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/Math/Subtract/Subtract.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/Math/Subtract/Subtract.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
