---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# GFX.Feature

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `{ Any }` |
| `<output>` || | | `GFX.Feature` |

</div>

The input table supports the following fields:

``` clojure
{
  :Shaders [
    {:Name <string> :Stage <enum> :Before [...] :After [...] :EntryPoint (-> ...)}
  ]
  :State {
    :Blend {...}
  }
  :DrawData [(-> ...)]/(-> ...)
  :Params [
    {:Name <string> :Type <type> :Dimension <number>}
  ]
}```


## Details

--8<-- "details/shards/GFX/Feature.md"


--8<-- "includes/license.md"
