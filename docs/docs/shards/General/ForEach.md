---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# ForEach

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Sequence/table whose elements or key-value pairs need to be processed. | | `[ Any ] { Any }` |
| `<output>` ||The output from processing the sequence/table elements or key-value pairs. | | `[ Any ] { Any }` |
| `Apply` |  | The processing logic (in the form of a shard or sequence of shards) to apply to the input sequence/table. | `None` | `Shard [ Shard ]` |

</div>

Processes every element or key-value pair of a sequence/table with a given shard or sequence of shards.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/ForEach/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/ForEach/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/ForEach/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/ForEach/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
