---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.RenderTarget

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The image to display | | `GFX.Texture` |
| `<output>` ||The output of this shard will be its input. | | `GFX.Texture` |
| `Scale` |  | Scaling to apply to the source texture | `(1, 1)` | `Float2 &Float2` |

</div>

Display the contents of a render target. Consumes input on the region

--8<-- "includes/license.md"
