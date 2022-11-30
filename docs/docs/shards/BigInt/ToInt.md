---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# BigInt.ToInt

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Big integer represented as bytes. | | `Bytes` |
| `<output>` ||Integer representation of the big integer value. | | `Int` |

</div>

Converts a big integer value to an integer.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/BigInt/ToInt/ToInt.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/BigInt/ToInt/ToInt.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
