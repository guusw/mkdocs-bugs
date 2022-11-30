---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Console

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The raw logs | | `String` |
| `<output>` ||The output of this shard will be its input. | | `String` |
| `ShowFilters` |  | Whether to display filter controls. | `false` | `Bool` |
| `Style` |  | The console style. | `None` | `{ Any } &{ Any }` |

</div>

A console with formatted logs.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Console/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Console/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Console/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Console/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
