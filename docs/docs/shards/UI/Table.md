---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Table

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `[ Any ]` |
| `<output>` || | | `[ Any ]` |
| `Rows` |  | Sequence of shards to build the rows. | `None` | `[ None Shard [ Shard ] ]` |
| `Columns` |  | Configuration of the columns. | `None` | `[ { Any } ]` |
| `Striped` | :fontawesome-solid-circle-plus:{title="Optional"}  | Whether to alternate a subtle background color to every other row. | `None` | `Bool &Bool ` |
| `Resizable` | :fontawesome-solid-circle-plus:{title="Optional"}  | Whether columns can be resized within their specified range. | `None` | `Bool &Bool ` |
| `RowIndex` | :fontawesome-solid-circle-plus:{title="Optional"}  | Variable to hold the row index, to be used within Rows. | `ContextVariable: Table.RowIndex` | `Int &Int ` |

</div>

Table layout.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Table/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Table/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Table/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Table/2.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Table/3.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Table/3.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
