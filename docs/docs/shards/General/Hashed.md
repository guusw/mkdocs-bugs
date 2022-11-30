---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Hashed

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value passed to the first shard in the hashed sequence. | | `Any` |
| `<output>` ||The hash of the output of the last shard in the hashed sequence. | | `Any` |
| `Shards` | :fontawesome-solid-circle-plus:{title="Optional"}  | The shards to execute in the hashed flow. | `None` | `Shard [ Shard ] ` |

</div>

Hashes the output of a shard or of a sequence of shards.

## Details

--8<-- "details/shards/General/Hashed.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Hashed/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Hashed/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Hashed/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Hashed/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
