---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Link

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the Action shards of the link. | | `Any` |
| `<output>` ||Indicates whether the link was clicked during this frame. | | `Bool` |
| `Label` | :fontawesome-solid-circle-plus:{title="Optional"}  | Optional label for the link | `None` | `String ` |
| `Action` | :fontawesome-solid-circle-plus:{title="Optional"}  | The shards to execute when the link is clicked. | `None` | `Shard [ Shard ]` |
| `Style` |  | The text style. | `None` | `{ Any } &{ Any }` |

</div>

A clickable link.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Link/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Link/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Link/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Link/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
