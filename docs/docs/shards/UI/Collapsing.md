---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.Collapsing

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the Contents shards of the collapsing header. | | `Any` |
| `<output>` ||The output of this shard will be its input. | | `Any` |
| `Heading` | :fontawesome-solid-circle-plus:{title="Optional"}  | The heading text or widgets for this collapsing header. | `None` | `String Shard [ Shard ] ` |
| `Contents` | :fontawesome-solid-circle-plus:{title="Optional"}  | The UI contents. | `None` | `Shard [ Shard ]` |
| `DefaultOpen` |  | Whether the collapsing header is opened by default. | `false` | `Bool` |

</div>

A header which can be collapsed/expanded, revealing a contained UI region.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Collapsing/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Collapsing/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/Collapsing/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/Collapsing/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
