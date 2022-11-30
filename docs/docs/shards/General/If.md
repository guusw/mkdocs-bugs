---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# If

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the predicate. | | `Any` |
| `<output>` ||The input of the shard if `Passthrough` is `true`; otherwise, the output of the action that was performed (i.e. `Then` or `Else`). | | `Any` |
| `Predicate` | :fontawesome-solid-circle-plus:{title="Optional"}  | The predicate to evaluate in order to trigger `Then` (when `true`) or `Else` (when `false`). | `None` | `Shard [ Shard ] ` |
| `Then` | :fontawesome-solid-circle-plus:{title="Optional"}  | The shards to activate when `Predicate` is `true`. | `None` | `Shard [ Shard ] ` |
| `Else` | :fontawesome-solid-circle-plus:{title="Optional"}  | The shards to activate when `Predicate` is `false`. | `None` | `Shard [ Shard ] ` |
| `Passthrough` |  | The output of this shard will be its input. | `false` | `Bool` |

</div>

Evaluates a predicate and executes an action.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/If/If.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/If/If.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
