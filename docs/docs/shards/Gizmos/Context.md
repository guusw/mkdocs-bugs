---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Gizmos.Context

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Any` |
| `<output>` || | | `Any` |
| `View` |  | The view used to render the gizmos.When drawing over a scene, the view should be the same | `None` | `&GFX.View` |
| `Queue` |  | The queue to draw into | `None` | `&GFX.DrawQueue` |
| `Content` | :fontawesome-solid-circle-plus:{title="Optional"}  | Content | `None` | `Shard [ Shard ] ` |

</div>

Provides a context for rendering gizmos

--8<-- "includes/license.md"
