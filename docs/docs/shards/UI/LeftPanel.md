---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.LeftPanel

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the Contents shards of the panel. | | `Any` |
| `<output>` ||The output of this shard will be its input. | | `Any` |
| `Resizable` | :fontawesome-solid-circle-plus:{title="Optional"}  | TODO | `None` | `Bool ` |
| `DefaultSize` | :fontawesome-solid-circle-plus:{title="Optional"}  | The initial size of the panel. | `None` | `Float ` |
| `MinSize` | :fontawesome-solid-circle-plus:{title="Optional"}  | The minimum allowable size of the panel. | `None` | `Float ` |
| `MaxSize` | :fontawesome-solid-circle-plus:{title="Optional"}  | The maximum allowable size of the panel. | `None` | `Float ` |
| `Contents` | :fontawesome-solid-circle-plus:{title="Optional"}  | The UI contents. | `None` | `Shard [ Shard ]` |

</div>

Layout UI elements into the panel.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/LeftPanel/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/LeftPanel/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
