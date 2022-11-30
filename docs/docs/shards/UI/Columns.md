---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Columns

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the Contents shards (each column). | | `Any` |
| `<output>` ||The output of this shard will be its input. | | `Any` |
| `Contents` |  | A sequence of UI contents. | `None` | `[ None Shard [ Shard ] ]` |

</div>

Splits the contents into several columns.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Columns/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Columns/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
