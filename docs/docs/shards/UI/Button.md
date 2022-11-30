---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Button

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the Action shards of the button. | | `Any` |
| `<output>` ||Indicates whether the button was clicked during this frame. | | `Bool` |
| `Label` |  | The text label of this button. | `None` | `String` |
| `Action` | :fontawesome-solid-circle-plus:{title="Optional"}  | The shards to execute when the button is pressed. | `None` | `Shard [ Shard ]` |
| `Wrap` | :fontawesome-solid-circle-plus:{title="Optional"}  | Wrap the text depending on the layout. | `None` | `Bool ` |
| `Style` |  | The text style. | `None` | `{ Any } &{ Any }` |

</div>

Clickable button with text.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Button/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Button/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Button/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Button/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
