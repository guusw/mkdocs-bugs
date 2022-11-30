---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# AppendTo

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value to append to the collection. | | `Any` |
| `<output>` ||The input to this shard is passed through as its output. | | `Any` |
| `Collection` |  | The collection to add the input to. | `None` | `&[ Any ] &String &Bytes` |

</div>

Appends the input to the context variable passed to `:Collection`.

## Details

--8<-- "details/shards/General/AppendTo.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/AppendTo/AppendTo.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/AppendTo/AppendTo.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
