---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Horizontal

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the Contents shards of the layout. | | `Any` |
| `<output>` ||The output of this shard will be its input. | | `Any` |
| `Contents` | :fontawesome-solid-circle-plus:{title="Optional"}  | The UI contents. | `None` | `Shard [ Shard ]` |
| `Wrap` |  | Wrap the content once it reaches the right edge. | `false` | `Bool` |

</div>

Layout the contents horizontally.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Horizontal/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Horizontal/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
