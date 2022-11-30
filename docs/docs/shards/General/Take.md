---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Take

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The sequence or table from which elements/key-values have to be extracted. | | `Int2 Int3 Int4 Int8 Int16 Float2 Float3 Float4 Bytes Color String [ Any ] { Any }` |
| `<output>` ||The extracted elements/key-values. | | `Any` |
| `Indices/Keys` |  | One or more indices/keys to extract from a sequence/table. | `None` | `Int [ Int ] &Int &[ Int ] String [ String ] &String &[ String ]` |

</div>

Extracts one or more elements/key-values from a sequence or a table by using the provided sequence index/indices or table key(s). Operation is non-destructive; doesn't modify target sequence/table.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Take/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Take/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
