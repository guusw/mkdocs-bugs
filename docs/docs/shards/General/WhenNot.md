---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# WhenNot

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the predicate. | | `Any` |
| `<output>` ||The input of the shard if `Passthrough` is `true`, or the `Predicate` is `true`; otherwise, the output of the `Action`. | | `Any` |
| `Predicate` | :fontawesome-solid-circle-plus:{title="Optional"}  | The predicate to evaluate in order to trigger Action. | `None` | `Shard [ Shard ] ` |
| `Action` | :fontawesome-solid-circle-plus:{title="Optional"}  | The shards to activate on when Predicate is true for When and false for WhenNot. | `None` | `Shard [ Shard ] ` |
| `Passthrough` |  | The output of this shard will be its input. | `true` | `Bool` |

</div>

Conditonal shard that only executes the action if the predicate is false.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/WhenNot/WhenNot.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/WhenNot/WhenNot.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
