---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Wasm.Run

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `String` |
| `<output>` || | | `String` |
| `Module` |  | The wasm module to run. | `""` | `Path String` |
| `Arguments` | :fontawesome-solid-circle-plus:{title="Optional"}  | The arguments to pass to the module entrypoint function. | `None` | `[ String ] &[ String ]` |
| `EntryPoint` |  | The entry point function to call when activating. | `"_start"` | `String` |
| `StackSize` |  | The stack size in kilobytes to use. | `1024` | `Int` |
| `ResetRuntime` |  | If the runtime should be reset every activation, altho slow this might be useful if certain modules fail to execute properly or leak on multiple activations. | `true` | `Bool` |
| `CallConstructors` |  | Use if it might be necessary to force a call to `__wasm_call_dtors`, modules generated with WASI rust might need this. | `false` | `Bool` |

</div>



--8<-- "includes/license.md"
