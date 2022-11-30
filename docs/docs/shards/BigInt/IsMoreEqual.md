---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# BigInt.IsMoreEqual

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Big integer represented as bytes. | | `Bytes` |
| `<output>` ||A boolean value repesenting the result of the logic operation. | | `Bool` |
| `Operand` |  | The bytes variable representing the operand | `None` | `&Bytes` |

</div>



## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/BigInt/IsMoreEqual/IsMoreEqual.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/BigInt/IsMoreEqual/IsMoreEqual.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
