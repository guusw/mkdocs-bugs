---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Label

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The text to display. | | `String` |
| `<output>` ||The output of this shard will be its input. | | `String` |
| `Wrap` | :fontawesome-solid-circle-plus:{title="Optional"}  | Wrap the text depending on the layout. | `None` | `Bool &Bool ` |
| `Style` |  | The text style. | `None` | `{ Any } &{ Any }` |

</div>

Static text.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Label/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Label/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Label/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Label/2.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Label/3.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Label/3.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
