---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# RTake

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The sequence from which elements have to be extracted. | | `Bytes String [ Any ]` |
| `<output>` ||The extracted elements. | | `Any` |
| `Indices` |  | One or more indices (counted backwards from the last element) to extract from a sequence. | `None` | `Int [ Int ] &Int &[ Int ]` |

</div>

Works exactly like `Take` except that the selection indices are counted backwards from the last element in the target sequence. Also, `RTake` works only on sequences, not on tables.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/RTake/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/RTake/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
