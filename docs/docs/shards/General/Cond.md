---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Cond

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to each predicate and action to execute. | | `Any` |
| `<output>` ||The input of the shard if `Passthrough` is `true`; otherwise, the output of the action of the first matching condition. | | `Any` |
| `Wires` |  | A sequence of shards, interleaving condition test predicate and action to execute if the condition matches. | `None` | `[ Shard [ Shard ] None ]` |
| `Passthrough` |  | The output of this shard will be its input. | `true` | `Bool` |
| `Threading` |  | Will not short circuit after the first true test expression. The threaded value gets used in only the action and not the test part of the clause. | `false` | `Bool` |

</div>

Takes a sequence of conditions and predicates. Evaluates each condition one by one and if one matches, executes the associated action.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Cond/Cond.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Cond/Cond.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
