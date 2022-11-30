---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Await

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Must match the input types of the first shard in the sequence. | | `Any` |
| `<output>` ||Will match the output types of the first shard of the sequence. | | `Any` |
| `Shards` | :fontawesome-solid-circle-plus:{title="Optional"}  | The shards to activate. | `None` | `Shard [ Shard ] ` |

</div>

Executes a shard or a sequence of shards asynchronously and awaits their completion.

## Details

--8<-- "details/shards/General/Await.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Await/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Await/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Await/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Await/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
