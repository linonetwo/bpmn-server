[bpmn-server](../README.md) / ILogger

# Interface: ILogger

A logging tool to take various message for monitoring and debugging

it can also keep the message in memory till saved later through saveToFile
msgs can be cleared by the clean method

## Implemented by

- [`Logger`](../classes/logger.md)

## Table of contents

### Methods

- [clear](ilogger.md#clear)
- [debug](ilogger.md#debug)
- [error](ilogger.md#error)
- [get](ilogger.md#get)
- [log](ilogger.md#log)
- [reportError](ilogger.md#reporterror)
- [save](ilogger.md#save)
- [setOptions](ilogger.md#setoptions)
- [warn](ilogger.md#warn)

## Methods

### clear

▸ **clear**(): `void`

#### Returns

`void`

#### Defined in

[interfaces/common.ts:54](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L54)

___

### debug

▸ **debug**(`...message`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...message` | `any` |

#### Returns

`void`

#### Defined in

[interfaces/common.ts:56](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L56)

___

### error

▸ **error**(`err`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `err` | `any` |

#### Returns

`void`

#### Defined in

[interfaces/common.ts:59](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L59)

___

### get

▸ **get**(): `any`[]

#### Returns

`any`[]

#### Defined in

[interfaces/common.ts:55](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L55)

___

### log

▸ **log**(`...message`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...message` | `any` |

#### Returns

`void`

#### Defined in

[interfaces/common.ts:58](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L58)

___

### reportError

▸ **reportError**(`err`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `err` | `any` |

#### Returns

`void`

#### Defined in

[interfaces/common.ts:60](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L60)

___

### save

▸ **save**(`filename`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `filename` | `any` |

#### Returns

`Promise`\<`void`\>

#### Defined in

[interfaces/common.ts:61](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L61)

___

### setOptions

▸ **setOptions**(`«destructured»`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `«destructured»` | `Object` |
| › `callback` | `any` |
| › `toConsole` | `any` |
| › `toFile` | `any` |

#### Returns

`void`

#### Defined in

[interfaces/common.ts:49](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L49)

___

### warn

▸ **warn**(`...message`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...message` | `any` |

#### Returns

`void`

#### Defined in

[interfaces/common.ts:57](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L57)
