---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# PrependTo

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value to prepend to the collection. | | `Any` |
| `<output>` ||The input to this shard is passed through as its output. | | `Any` |
| `Collection` |  | The collection to add the input to. | `None` | `&[ Any ] &String &Bytes` |

</div>

Prepends the input to the context variable passed to `:Collection`.

## Details

--8<-- "details/shards/General/PrependTo.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/PrependTo/PrependTo.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/PrependTo/PrependTo.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
