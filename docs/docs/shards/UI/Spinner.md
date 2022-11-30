---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Spinner

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | `Any` |
| `<output>` ||The output of this shard will be its input. | | `Any` |
| `Size` |  | Overrides the size of the spinner. This sets both the height and width, as the spinner is always square. | `None` | `Float &Float` |

</div>

A spinner widget used to indicate loading.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Spinner/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Spinner/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
