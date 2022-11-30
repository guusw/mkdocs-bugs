---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# BigInt.Abs

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Big integer represented as bytes. | | `Bytes` |
| `<output>` ||Big integer represented as bytes. | | `Bytes` |

</div>

Computes the absolute value of a big integer.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/BigInt/Abs/Abs.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/BigInt/Abs/Abs.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
