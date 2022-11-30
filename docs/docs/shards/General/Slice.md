---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Slice

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The string or sequence from which characters/elements have to be extracted. | | `[ Any ] Bytes String` |
| `<output>` ||The extracted characters/elements. | | `Any` |
| `From` |  | The position/index of the first character or element that is to be extracted (including). Negative position/indices simply loop over the target string/sequence counting backwards. | `0` | `Int [ Int ] &Int &[ Int ]` |
| `To` | :fontawesome-solid-circle-plus:{title="Optional"}  | The position/index of the last character or element that is to be extracted (excluding). Negative position/indices simply loop over the target string/sequence counting backwards. | `None` | `Int [ Int ] &Int &[ Int ] ` |
| `Step` |  | The increment between each position/index. Chooses every nth sample to extract, where n is the increment. Value has to be greater than zero. | `1` | `Int` |

</div>

Extracts characters from a string or elements from a sequence based on the start and end positions/indices and an increment parameter. Operation is non-destructive; the target string/sequence is not modified.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Slice/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Slice/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
