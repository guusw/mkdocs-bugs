---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.ProgressBar

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The progress amount in the [0.0, 1.0] range, where 1 means completed. | | `Float` |
| `<output>` ||The output of this shard will be its input. | | `Float` |
| `Overlay` | :fontawesome-solid-circle-plus:{title="Optional"}  | The text displayed inside the progress bar. | `None` | `String &String ` |
| `Width` |  | The desired width of the progress bar. Will use all horizontal space if not set. | `None` | `Float &Float` |

</div>

A progress bar with an optional overlay text.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/ProgressBar/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/ProgressBar/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
