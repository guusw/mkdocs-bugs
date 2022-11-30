---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# BigInt.FromFloat

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Floating point number. | | `Float` |
| `<output>` ||Big integer represented as bytes. | | `Bytes` |
| `ShiftedBy` |  | The shift is of the decimal point, i.e. of powers of ten, and is to the left if n is negative or to the right if n is positive. | `0` | `Int` |

</div>

Converts a floating point number to a big integer.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/BigInt/FromFloat/FromFloat.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/BigInt/FromFloat/FromFloat.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
