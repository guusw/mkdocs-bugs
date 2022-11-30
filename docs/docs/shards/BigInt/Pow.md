---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# BigInt.Pow

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Big integer represented as bytes. | | `Bytes` |
| `<output>` ||Big integer represented as bytes. | | `Bytes` |
| `Operand` |  | The integer operand, can be a variable | `None` | `Int &Int` |

</div>



## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/BigInt/Pow/Pow.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/BigInt/Pow/Pow.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
