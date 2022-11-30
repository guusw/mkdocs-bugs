---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Audio.Channel

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Any` |
| `<output>` || | | `Any` |
| `InputBus` |  | The input bus number, 0 is the audio device ADC. | `0` | `Int` |
| `InputChannels` |  | The list of input channels to pass as input to Shards. | `None` | `[ Int ]` |
| `OutputBus` |  | The output bus number, 0 is the audio device DAC. | `0` | `Int` |
| `OutputChannels` |  | The list of output channels to write from Shards's output. | `None` | `[ Int ]` |
| `Volume` |  | The volume of this channel. | `0.7` | `Float &Float` |
| `Shards` | :fontawesome-solid-circle-plus:{title="Optional"}  | The shards that will process audio data. | `None` | `Shard [ Shard ] ` |

</div>

--8<-- "includes/experimental.md"



--8<-- "includes/license.md"
