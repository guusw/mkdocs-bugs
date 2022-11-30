---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.ScrollArea

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the Contents shards of the scroll area. | | `Any` |
| `<output>` ||The output of this shard will be its input. | | `Any` |
| `Contents` | :fontawesome-solid-circle-plus:{title="Optional"}  | The UI contents. | `None` | `Shard [ Shard ]` |
| `Horizontal` |  | Enable horizontal scrolling. | `false` | `Bool` |
| `Vertical` |  | Enable vertical scrolling. | `true` | `Bool` |
| `AlwaysShow` |  | Always show the enabled scroll bars even if not needed. | `false` | `Bool` |

</div>

Add vertical and/or horizontal scrolling to a contained UI.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/ScrollArea/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/ScrollArea/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
