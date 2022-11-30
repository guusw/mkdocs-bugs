---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Sub

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The input value passed to this Sub flow (and hence to the shard or sequence of shards in this Sub flow). | | `Any` |
| `<output>` ||The output of this Sub flow (which is the same as its input). | | `Any` |
| `Shards` | :fontawesome-solid-circle-plus:{title="Optional"}  | The shard or sequence of shards to execute in the Sub flow. | `None` | `Shard [ Shard ] ` |

</div>

Activates a shard or a sequence of shards independently, without consuming the input. I.e. the input of the Sub flow will also be its output regardless of the shards activated in this Sub flow.

## Details

--8<-- "details/shards/General/Sub.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Sub/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Sub/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Sub/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Sub/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
