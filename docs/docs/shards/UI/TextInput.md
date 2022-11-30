---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.TextInput

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | `None` |
| `<output>` ||The value produced when changed. | | `String` |
| `Variable` |  | The variable that holds the input value. | `None` | `String &String` |
| `Multiline` |  | Support multiple lines. | `false` | `Bool` |

</div>

A widget where text can be entered.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/TextInput/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/TextInput/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/TextInput/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/TextInput/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
