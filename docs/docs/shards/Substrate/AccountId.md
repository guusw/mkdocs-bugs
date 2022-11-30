---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Substrate.AccountId

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The public key bytes, must be a valid Sr25519 or Ed25519 public key. | | `Bytes` |
| `<output>` ||The Substrate account id in SS58 format. | | `String` |
| `ECDSA` |  | If the input public key is an ECDSA and not the default Sr25519/Ed25519. | `false` | `Bool` |
| `Version` |  | The substrate version prefix. | `42` | `Int` |

</div>

Returns the account id of the input public key.

--8<-- "includes/license.md"
