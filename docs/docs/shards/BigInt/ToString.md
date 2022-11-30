---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# BigInt.ToString

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Big integer represented as bytes. | | `Bytes` |
| `<output>` ||String representation of the big integer value. | | `String` |

</div>

Converts the value to a string representation.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/BigInt/ToString/ToString.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/BigInt/ToString/ToString.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
