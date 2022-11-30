---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Audio.Oscillator

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Float` |
| `<output>` || | | `Audio` |
| `Type` |  | The waveform type to oscillate. | `Enum: 0 vendor: 0x66726167 type: 0x77617665` | `Waveform` |
| `Amplitude` |  | The waveform amplitude. | `0.4` | `Float &Float` |
| `Channels` |  | The number of desired output audio channels. | `2` | `Int` |
| `SampleRate` |  | The desired output sampling rate. Ignored if inside an Audio.Channel. | `44100` | `Int` |
| `Samples` |  | The desired number of samples in the output. Ignored if inside an Audio.Channel. | `1024` | `Int` |

</div>

--8<-- "includes/experimental.md"



--8<-- "includes/license.md"
