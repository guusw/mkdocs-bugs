---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Math.Dec

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Any valid integer(s), floating point number(s), or a sequence of such entities supported by this operation. | | `Any` |
| `<output>` ||The result of the operation, usually in the same type as the input value. | | `Any` |
| `Value` |  | The value to apply the operation to. | `None` | `&Int &Int2 &Int3 &Int4 &Int8 &Int16 &Float &Float2 &Float3 &Float4 &Color &[ Any ]` |

</div>

Applies the unary operation on the input value and returns the result (or a sequence of results if the input and the operand are sequences).

## Details

--8<-- "details/shards/Math/Dec.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/Math/Dec/Dec.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/Math/Dec/Dec.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
