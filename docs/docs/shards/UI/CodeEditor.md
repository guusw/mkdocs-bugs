---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.CodeEditor

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | `None` |
| `<output>` ||The value produced when changed. | | `String` |
| `Variable` |  | The variable that holds the input value. | `None` | `String &String` |
| `Language` |  | The name of the programming language for syntax highlighting. | `None` | `String &String` |

</div>

A TextInput with support for highlighting

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/CodeEditor/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/CodeEditor/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
