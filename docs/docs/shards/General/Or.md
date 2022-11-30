---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Or

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The first operand to be evaluated. | | `Bool` |
| `<output>` ||The output of this shard will be its input. | | `Bool` |

</div>

Computes the logical OR between the input of this shard and the output of the next shard.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Or/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Or/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
