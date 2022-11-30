---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Indent

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the Contents shards. | | `Any` |
| `<output>` ||The output of this shard will be its input. | | `Any` |
| `Contents` | :fontawesome-solid-circle-plus:{title="Optional"}  | The UI contents. | `None` | `Shard [ Shard ]` |

</div>

Creates a child ui which is indented to the right.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Indent/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Indent/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
