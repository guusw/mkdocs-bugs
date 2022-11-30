---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Physics.KinematicBody

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `None` |
| `<output>` || | | `[ Float4 ] [ [ Float4 ] ]` |
| `Shapes` | :fontawesome-solid-circle-plus:{title="Optional"}  | The shape or shapes of this rigid body. | `None` | `&Object &Object ` |
| `Position` |  | The initial position of this rigid body. Can be updated in the case of a kinematic rigid body. | `(0, 0, 0)` | `Float3 &Float3 [ Float3 ] &[ Float3 ]` |
| `Rotation` |  | The initial rotation of this rigid body. Either axis angles in radians Float3 or a quaternion Float4. Can be updated in the case of a kinematic rigid body. | `(0, 0, 0, 1)` | `Float4 &Float4 [ Float4 ] &[ Float4 ]` |
| `Name` | :fontawesome-solid-circle-plus:{title="Optional"}  | The optional name of the variable that will be exposed to identify, apply forces (if dynamic) and control this rigid body. | `None` | `String ` |

</div>



--8<-- "includes/license.md"
