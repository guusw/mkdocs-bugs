---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Hyperlink

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The URL. | | `String` |
| `<output>` ||The output of this shard will be its input. | | `String` |
| `Label` | :fontawesome-solid-circle-plus:{title="Optional"}  | Optional label for the hyperlink | `None` | `String ` |
| `Style` |  | The text style. | `None` | `{ Any } &{ Any }` |

</div>

A clickable hyperlink.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Hyperlink/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Hyperlink/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Hyperlink/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Hyperlink/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
