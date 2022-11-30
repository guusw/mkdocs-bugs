---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI

```clojure
(UI
  :Queue [(ContextVar [(Object)])]
  :Contents [(None) (Shard) (Seq [(Shard)])]
)
```


## Definition




## Parameters

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | N/A | `[(Any)]` |
| `<output>` || | N/A | `[(Any)]` |
| `Queue` | :fontawesome-solid-circle-plus:{ title="Optional" } | The draw queue | `None` | `[(ContextVar [(Object)])]` |
| `Contents` | :fontawesome-solid-circle-plus:{ title="Optional" } | The UI contents. | `None` | `[(None) (Shard) (Seq [(Shard)])]` |

</div>

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/UI/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/UI/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
