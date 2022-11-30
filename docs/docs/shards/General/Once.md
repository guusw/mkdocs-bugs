---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Once

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Any` |
| `<output>` || | | `Any` |
| `Action` |  | The shard or sequence of shards to execute. | `None` | `Shard [ Shard ]` |
| `Every` |  | The number of seconds to wait until repeating the action, if 0 the action will happen only once per wire flow execution. | `0` | `Float` |

</div>

Executes the shard or sequence of shards with the desired frequency in a wire flow execution.

## Details

--8<-- "details/shards/General/Once.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Once/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Once/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Once/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Once/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
