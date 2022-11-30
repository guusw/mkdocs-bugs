---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Repeat

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The input will be passed to both the action and the `:Until` condition if used. | | `Any` |
| `<output>` ||The output of this shard will be its input. | | `Any` |
| `Action` |  | The shards to repeat. | `None` | `Shard [ Shard ]` |
| `Times` |  | How many times we should repeat the action. | `0` | `Int [ Int ] &Int &[ Int ]` |
| `Forever` |  | If we should repeat the action forever. | `false` | `Bool` |
| `Until` | :fontawesome-solid-circle-plus:{title="Optional"}  | Optional shards to use as predicate to continue repeating until it's true | `None` | `Shard [ Shard ] ` |

</div>

Repeat an action a given number of times or until a condition is no longer `true`.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Repeat/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Repeat/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Repeat/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Repeat/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
