---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Maybe

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Must match the input types of the first shard in the sequence. | | `Any` |
| `<output>` ||Will match the output types of the first shard of the sequence. | | `Any` |
| `Shards` | :fontawesome-solid-circle-plus:{title="Optional"}  | The shards to activate. | `None` | `Shard [ Shard ] ` |
| `Else` | :fontawesome-solid-circle-plus:{title="Optional"}  | The shards to activate on failure. | `None` | `Shard [ Shard ] ` |
| `Silent` |  | If logging should be disabled while running the shards (this will also disable (Log) and (Msg) shards) and no warning message should be printed on failure. | `false` | `Bool` |

</div>

Attempts to activate a shard or a sequence of shards. Upon failure, activate another shard or sequence of shards.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Maybe/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Maybe/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Maybe/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Maybe/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
