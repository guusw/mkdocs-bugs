---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# BigInt.ToBytes

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Big integer represented as bytes. | | `Bytes` |
| `<output>` || | | `Bytes` |
| `Bits` |  | The desired amount of bits for the output or 0 for automatic packing. | `0` | `Int` |

</div>



## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/BigInt/ToBytes/ToBytes.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/BigInt/ToBytes/ToBytes.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
