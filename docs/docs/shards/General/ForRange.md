---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# ForRange

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The input value is not used and will pass through. | | `Any` |
| `<output>` ||The output of this shard will be its input. | | `Any` |
| `From` |  | The initial iteration value (inclusive). | `0` | `Int &Int` |
| `To` |  | The final iteration value (inclusive). | `1` | `Int &Int` |
| `Action` | :fontawesome-solid-circle-plus:{title="Optional"}  | The action to perform at each iteration. The current iteration value will be passed as input. | `None` | `Shard [ Shard ] ` |

</div>

Executes a shard while an iteration value is within a range.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/ForRange/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/ForRange/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
