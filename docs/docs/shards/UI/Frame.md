---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Frame

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the Contents shards of the frame. | | `Any` |
| `<output>` ||The output of this shard will be its input. | | `Any` |
| `Contents` | :fontawesome-solid-circle-plus:{title="Optional"}  | The UI contents. | `None` | `Shard [ Shard ]` |
| `InnerMargin` |  | The UI contents. | `None` | `Float4` |
| `OuterMargin` |  | The UI contents. | `None` | `Float4` |
| `Rounding` |  | The UI contents. | `None` | `Float4` |
| `FillColor` | :fontawesome-solid-circle-plus:{title="Optional"}  | The UI contents. | `None` | `Color &Color ` |
| `StrokeColor` | :fontawesome-solid-circle-plus:{title="Optional"}  | The UI contents. | `None` | `Color &Color ` |
| `StrokeWidth` |  | The UI contents. | `None` | `Float` |

</div>

Visually groups the contents together.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Frame/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Frame/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
