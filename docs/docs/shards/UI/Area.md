---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Area

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the Contents shards of the area. | | `Any` |
| `<output>` ||The output of this shard will be its input. | | `Any` |
| `Position` |  | Absolute position; or when anchor is set, relative offset. | `None` | `Float2 &Float2` |
| `Anchor` |  | Corner or center of the screen. | `None` | `Anchor` |
| `Contents` | :fontawesome-solid-circle-plus:{title="Optional"}  | The UI contents. | `None` | `Shard [ Shard ]` |

</div>

Places UI element at a specific position.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Area/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Area/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
