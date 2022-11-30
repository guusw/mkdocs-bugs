---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.ImageButton

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the Action shards of the button. | | `Image GFX.Texture` |
| `<output>` ||Indicates whether the button was clicked during this frame. | | `Bool` |
| `Action` | :fontawesome-solid-circle-plus:{title="Optional"}  | The shards to execute when the button is pressed. | `None` | `Shard [ Shard ]` |
| `Scale` |  | Scaling to apply to the source image | `(1, 1)` | `Float2 &Float2` |
| `Selected` | :fontawesome-solid-circle-plus:{title="Optional"}  | Indicates whether the button is selected. | `None` | `Bool &Bool ` |

</div>

Clickable button with image.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/ImageButton/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/ImageButton/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/ImageButton/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/ImageButton/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
