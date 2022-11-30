---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Mutant

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Any` |
| `<output>` || | | `Any` |
| `Shard` |  | The shard to mutate. | `None` | `Shard` |
| `Indices` |  | The parameter indices to mutate of the inner shard. | `None` | `[ Int ]` |
| `Mutations` |  | Optional wires of shards (or Nones) to call when mutating one of the parameters, if empty a default operator will be used. | `None` | `[ Shard [ Shard ] None ]` |
| `Options` | :fontawesome-solid-circle-plus:{title="Optional"}  | Mutation options table - a table with mutation options. | `None` | `{ Any }` |

</div>



--8<-- "includes/license.md"
