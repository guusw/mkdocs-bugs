---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Math.Cosh

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Any valid integer(s), floating point number(s), or a sequence of such entities supported by this operation. | | `Int Int2 Int3 Int4 Int8 Int16 Float Float2 Float3 Float4 Color [ Any ]` |
| `<output>` ||The result of the operation, usually in the same type as the input value. | | `Int Int2 Int3 Int4 Int8 Int16 Float Float2 Float3 Float4 Color [ Any ]` |

</div>

Applies the unary operation on the input value and returns the result (or a sequence of results if the input and the operand are sequences).

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/Math/Cosh/Cosh.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/Math/Cosh/Cosh.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
