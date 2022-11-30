---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Sort

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Any input is ignored. | | `None` |
| `<output>` ||Output is the sorted sequence. | | `[ Any ]` |
| `From` |  | The name of the sequence variable to edit in place. | `None` | `&[ Any ]` |
| `Join` |  | Other columns to join sort/filter using the input (they must be of the same length). | `None` | `&[ Any ] [ &[ Any ] ]` |
| `Desc` |  | If sorting should be in descending order, defaults ascending. | `false` | `Bool` |
| `Key` | :fontawesome-solid-circle-plus:{title="Optional"}  | The shards to use to transform the collection's items before they are compared. Can be None. | `None` | `Shard [ Shard ] ` |

</div>

Sorts the elements of a sequence. Can also move around the elements of a joined sequence in alignment with the sorted sequence.

## Details

--8<-- "details/shards/General/Sort.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Sort/Sort.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Sort/Sort.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
