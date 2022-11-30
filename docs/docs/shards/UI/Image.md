---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Image

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The image to display | | `Image GFX.Texture` |
| `<output>` ||The output of this shard will be its input. | | `Image GFX.Texture` |
| `Scale` |  | Scaling to apply to the source image | `(1, 1)` | `Float2 &Float2` |

</div>

Display an image in the UI.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Image/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Image/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Image/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Image/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
