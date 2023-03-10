[@haqq/provider-web3-utils - v0.0.9](README.md) / Exports

# @haqq/provider-web3-utils - v0.0.9

## Table of contents

### Functions

- [accountInfo](modules.md#accountinfo)
- [derive](modules.md#derive)
- [generateEntropy](modules.md#generateentropy)
- [generateMnemonic](modules.md#generatemnemonic)
- [generateMnemonicFromEntropy](modules.md#generatemnemonicfromentropy)
- [hashMessage](modules.md#hashmessage)
- [seedFromMnemonic](modules.md#seedfrommnemonic)
- [sign](modules.md#sign)

## Functions

### accountInfo

▸ **accountInfo**(`privateKey`): `Promise`<{ `address`: `string` ; `publicKey`: `string`  }\>

Get account address and public key by privateKey

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `privateKey` | `string` | Private key |

#### Returns

`Promise`<{ `address`: `string` ; `publicKey`: `string`  }\>

#### Defined in

[native-modules.ts:79](https://github.com/haqq-network/haqq-wallet-provider-web3-utils/blob/1ba7a4d/src/native-modules.ts#L79)

___

### derive

▸ **derive**(`seed`, `path`): `Promise`<`string`\>

Derive hd path for seed phrase

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `seed` | `string` | Seed phrase |
| `path` | `string` | HD path |

#### Returns

`Promise`<`string`\>

- Promise resolving to stringified data

#### Defined in

[native-modules.ts:71](https://github.com/haqq-network/haqq-wallet-provider-web3-utils/blob/1ba7a4d/src/native-modules.ts#L71)

___

### generateEntropy

▸ **generateEntropy**(`strength?`): `Promise`<`Buffer`\>

Generate entropy with strength

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `strength` | `number` | `16` | Strength for entropy |

#### Returns

`Promise`<`Buffer`\>

- Promise resolving to stringifies data

#### Defined in

[native-modules.ts:26](https://github.com/haqq-network/haqq-wallet-provider-web3-utils/blob/1ba7a4d/src/native-modules.ts#L26)

___

### generateMnemonic

▸ **generateMnemonic**(`strength?`): `Promise`<`string`\>

Generate mnemonic with strength

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `strength` | `number` | `16` | Strength for mnemonic |

#### Returns

`Promise`<`string`\>

- Promise resolving to stringified data

#### Defined in

[native-modules.ts:48](https://github.com/haqq-network/haqq-wallet-provider-web3-utils/blob/1ba7a4d/src/native-modules.ts#L48)

___

### generateMnemonicFromEntropy

▸ **generateMnemonicFromEntropy**(`entropy`): `Promise`<`string`\>

Generate mnemonic from entropy

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entropy` | `Buffer` | Entropy for mnemonic |

#### Returns

`Promise`<`string`\>

- Promise resolving to stringifies data

#### Defined in

[native-modules.ts:38](https://github.com/haqq-network/haqq-wallet-provider-web3-utils/blob/1ba7a4d/src/native-modules.ts#L38)

___

### hashMessage

▸ **hashMessage**(`message`): `Promise`<`string`\>

Hash message

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `message` | `string` | message for signing |

#### Returns

`Promise`<`string`\>

- Promise resolving to stringified data

- Promise resolving to stringified data

#### Defined in

[native-modules.ts:103](https://github.com/haqq-network/haqq-wallet-provider-web3-utils/blob/1ba7a4d/src/native-modules.ts#L103)

___

### seedFromMnemonic

▸ **seedFromMnemonic**(`mnemonicPhrase`): `Promise`<`string`\>

Generate seed phrase from mnemonic string

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `mnemonicPhrase` | `string` | Mnemonic phrase |

#### Returns

`Promise`<`string`\>

- Promise resolving to stringified data

#### Defined in

[native-modules.ts:60](https://github.com/haqq-network/haqq-wallet-provider-web3-utils/blob/1ba7a4d/src/native-modules.ts#L60)

___

### sign

▸ **sign**(`privateKey`, `message`): `Promise`<`string`\>

Sign transaction

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `privateKey` | `string` | private key |
| `message` | `string` | message for signing |

#### Returns

`Promise`<`string`\>

- Promise resolving to stringified data

- Promise resolving to stringified data

#### Defined in

[native-modules.ts:91](https://github.com/haqq-network/haqq-wallet-provider-web3-utils/blob/1ba7a4d/src/native-modules.ts#L91)
