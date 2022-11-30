---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Plot

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Any` |
| `<output>` || | | `Any` |
| `Contents` | :fontawesome-solid-circle-plus:{title="Optional"}  | The UI contents. | `None` | `Shard [ Shard ]` |
| `ViewAspect` | :fontawesome-solid-circle-plus:{title="Optional"}  | Width / height ratio of the plot region. | `None` | `Float &Float ` |
| `DataAspect` | :fontawesome-solid-circle-plus:{title="Optional"}  | Width / height ratio of the data. | `None` | `Float &Float ` |
| `Legend` | :fontawesome-solid-circle-plus:{title="Optional"}  | Whether to display the legend. | `None` | `Bool ` |

</div>



## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Plot/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Plot/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Plot/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Plot/2.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Plot/3.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Plot/3.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
