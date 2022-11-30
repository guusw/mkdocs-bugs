---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# BigInt.Shift

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Big integer represented as bytes. | | `Bytes` |
| `<output>` ||Big integer represented as bytes. | | `Bytes` |
| `By` |  | The shift is of the decimal point, i.e. of powers of ten, and is to the left if n is negative or to the right if n is positive. | `0` | `Int &Int` |

</div>



## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/BigInt/Shift/Shift.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/BigInt/Shift/Shift.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
