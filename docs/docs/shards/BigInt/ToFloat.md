---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# BigInt.ToFloat

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Big integer represented as bytes. | | `Bytes` |
| `<output>` ||Floating point number representation of the big integer value. | | `Float` |
| `ShiftedBy` |  | The shift is of the decimal point, i.e. of powers of ten, and is to the left if n is negative or to the right if n is positive. | `0` | `Int` |

</div>

Converts a big integer value to a floating point number.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/BigInt/ToFloat/ToFloat.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/BigInt/ToFloat/ToFloat.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
