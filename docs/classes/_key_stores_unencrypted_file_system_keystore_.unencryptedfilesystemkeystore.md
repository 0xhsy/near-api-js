

# Hierarchy

 [KeyStore](_key_stores_keystore_.keystore.md)

**↳ UnencryptedFileSystemKeyStore**

# Constructors

<a id="constructor"></a>

##  constructor

⊕ **new UnencryptedFileSystemKeyStore**(keyDir: *`string`*): [UnencryptedFileSystemKeyStore](_key_stores_unencrypted_file_system_keystore_.unencryptedfilesystemkeystore.md)

*Defined in [key_stores/unencrypted_file_system_keystore.ts:39](https://github.com/nearprotocol/nearlib/blob/c8da0d8/src.ts/key_stores/unencrypted_file_system_keystore.ts#L39)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| keyDir | `string` |

**Returns:** [UnencryptedFileSystemKeyStore](_key_stores_unencrypted_file_system_keystore_.unencryptedfilesystemkeystore.md)

___

# Properties

<a id="keydir"></a>

##  keyDir

**● keyDir**: *`string`*

*Defined in [key_stores/unencrypted_file_system_keystore.ts:39](https://github.com/nearprotocol/nearlib/blob/c8da0d8/src.ts/key_stores/unencrypted_file_system_keystore.ts#L39)*

___

# Methods

<a id="clear"></a>

##  clear

▸ **clear**(): `Promise`<`void`>

*Overrides [KeyStore](_key_stores_keystore_.keystore.md).[clear](_key_stores_keystore_.keystore.md#clear)*

*Defined in [key_stores/unencrypted_file_system_keystore.ts:67](https://github.com/nearprotocol/nearlib/blob/c8da0d8/src.ts/key_stores/unencrypted_file_system_keystore.ts#L67)*

**Returns:** `Promise`<`void`>

___
<a id="getaccounts"></a>

##  getAccounts

▸ **getAccounts**(networkId: *`string`*): `Promise`<`string`[]>

*Overrides [KeyStore](_key_stores_keystore_.keystore.md).[getAccounts](_key_stores_keystore_.keystore.md#getaccounts)*

*Defined in [key_stores/unencrypted_file_system_keystore.ts:84](https://github.com/nearprotocol/nearlib/blob/c8da0d8/src.ts/key_stores/unencrypted_file_system_keystore.ts#L84)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| networkId | `string` |

**Returns:** `Promise`<`string`[]>

___
<a id="getkey"></a>

##  getKey

▸ **getKey**(networkId: *`string`*, accountId: *`string`*): `Promise`<[KeyPair](_utils_key_pair_.keypair.md)>

*Overrides [KeyStore](_key_stores_keystore_.keystore.md).[getKey](_key_stores_keystore_.keystore.md#getkey)*

*Defined in [key_stores/unencrypted_file_system_keystore.ts:52](https://github.com/nearprotocol/nearlib/blob/c8da0d8/src.ts/key_stores/unencrypted_file_system_keystore.ts#L52)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| networkId | `string` |
| accountId | `string` |

**Returns:** `Promise`<[KeyPair](_utils_key_pair_.keypair.md)>

___
<a id="getkeyfilepath"></a>

## `<Private>` getKeyFilePath

▸ **getKeyFilePath**(networkId: *`string`*, accountId: *`string`*): `string`

*Defined in [key_stores/unencrypted_file_system_keystore.ts:71](https://github.com/nearprotocol/nearlib/blob/c8da0d8/src.ts/key_stores/unencrypted_file_system_keystore.ts#L71)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| networkId | `string` |
| accountId | `string` |

**Returns:** `string`

___
<a id="getnetworks"></a>

##  getNetworks

▸ **getNetworks**(): `Promise`<`string`[]>

*Overrides [KeyStore](_key_stores_keystore_.keystore.md).[getNetworks](_key_stores_keystore_.keystore.md#getnetworks)*

*Defined in [key_stores/unencrypted_file_system_keystore.ts:75](https://github.com/nearprotocol/nearlib/blob/c8da0d8/src.ts/key_stores/unencrypted_file_system_keystore.ts#L75)*

**Returns:** `Promise`<`string`[]>

___
<a id="removekey"></a>

##  removeKey

▸ **removeKey**(networkId: *`string`*, accountId: *`string`*): `Promise`<`void`>

*Overrides [KeyStore](_key_stores_keystore_.keystore.md).[removeKey](_key_stores_keystore_.keystore.md#removekey)*

*Defined in [key_stores/unencrypted_file_system_keystore.ts:61](https://github.com/nearprotocol/nearlib/blob/c8da0d8/src.ts/key_stores/unencrypted_file_system_keystore.ts#L61)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| networkId | `string` |
| accountId | `string` |

**Returns:** `Promise`<`void`>

___
<a id="setkey"></a>

##  setKey

▸ **setKey**(networkId: *`string`*, accountId: *`string`*, keyPair: *[KeyPair](_utils_key_pair_.keypair.md)*): `Promise`<`void`>

*Overrides [KeyStore](_key_stores_keystore_.keystore.md).[setKey](_key_stores_keystore_.keystore.md#setkey)*

*Defined in [key_stores/unencrypted_file_system_keystore.ts:46](https://github.com/nearprotocol/nearlib/blob/c8da0d8/src.ts/key_stores/unencrypted_file_system_keystore.ts#L46)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| networkId | `string` |
| accountId | `string` |
| keyPair | [KeyPair](_utils_key_pair_.keypair.md) |

**Returns:** `Promise`<`void`>

___
<a id="totalaccounts"></a>

##  totalAccounts

▸ **totalAccounts**(): `Promise`<`number`>

*Overrides [KeyStore](_key_stores_keystore_.keystore.md).[totalAccounts](_key_stores_keystore_.keystore.md#totalaccounts)*

*Defined in [key_stores/unencrypted_file_system_keystore.ts:94](https://github.com/nearprotocol/nearlib/blob/c8da0d8/src.ts/key_stores/unencrypted_file_system_keystore.ts#L94)*

**Returns:** `Promise`<`number`>

___
