[bpmn-server](../README.md) / Logger

# Class: Logger

A logging tool to take various message for monitoring and debugging

it can also keep the message in memory till saved later through saveToFile
msgs can be cleared by the clean method

## Implements

- [`ILogger`](../interfaces/ilogger.md)

## Table of contents

### Constructors

- [constructor](logger.md#constructor)

### Properties

- [callback](logger.md#callback)
- [debugMsgs](logger.md#debugmsgs)
- [toConsole](logger.md#toconsole)
- [toFile](logger.md#tofile)

### Methods

- [clear](logger.md#clear)
- [debug](logger.md#debug)
- [error](logger.md#error)
- [get](logger.md#get)
- [log](logger.md#log)
- [msg](logger.md#msg)
- [reportError](logger.md#reporterror)
- [save](logger.md#save)
- [setOptions](logger.md#setoptions)
- [toString](logger.md#tostring)
- [warn](logger.md#warn)

## Constructors

### constructor

• **new Logger**(`«destructured»`): [`Logger`](logger.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `«destructured»` | `Object` |
| › `callback` | `any` |
| › `toConsole` | `boolean` |
| › `toFile` | `string` |

#### Returns

[`Logger`](logger.md)

#### Defined in

[common/Logger.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/Logger.ts#L14)

## Properties

### callback

• **callback**: `any` = `null`

#### Defined in

[common/Logger.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/Logger.ts#L12)

___

### debugMsgs

• **debugMsgs**: `any`[] = `[]`

#### Defined in

[common/Logger.ts:9](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/Logger.ts#L9)

___

### toConsole

• **toConsole**: `boolean` = `true`

#### Defined in

[common/Logger.ts:10](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/Logger.ts#L10)

___

### toFile

• **toFile**: `any` = `null`

#### Defined in

[common/Logger.ts:11](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/Logger.ts#L11)

## Methods

### clear

▸ **clear**(): `void`

#### Returns

`void`

#### Implementation of

[ILogger](../interfaces/ilogger.md).[clear](../interfaces/ilogger.md#clear)

#### Defined in

[common/Logger.ts:36](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/Logger.ts#L36)

___

### debug

▸ **debug**(`...message`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...message` | `any`[] |

#### Returns

`void`

#### Implementation of

[ILogger](../interfaces/ilogger.md).[debug](../interfaces/ilogger.md#debug)

#### Defined in

[common/Logger.ts:44](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/Logger.ts#L44)

___

### error

▸ **error**(`err`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `err` | `any` |

#### Returns

`void`

#### Implementation of

[ILogger](../interfaces/ilogger.md).[error](../interfaces/ilogger.md#error)

#### Defined in

[common/Logger.ts:91](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/Logger.ts#L91)

___

### get

▸ **get**(): `any`[]

#### Returns

`any`[]

#### Implementation of

[ILogger](../interfaces/ilogger.md).[get](../interfaces/ilogger.md#get)

#### Defined in

[common/Logger.ts:40](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/Logger.ts#L40)

___

### log

▸ **log**(`...message`): `Object`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...message` | `any`[] |

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `date` | `Date` |
| `message` | `any` |

#### Implementation of

[ILogger](../interfaces/ilogger.md).[log](../interfaces/ilogger.md#log)

#### Defined in

[common/Logger.ts:51](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/Logger.ts#L51)

___

### msg

▸ **msg**(`message`, `type?`): `Object`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `message` | `any` | `undefined` |
| `type` | `string` | `'log'` |

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `date` | `Date` |
| `message` | `any` |

#### Defined in

[common/Logger.ts:23](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/Logger.ts#L23)

___

### reportError

▸ **reportError**(`err`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `err` | `any` |

#### Returns

`void`

#### Implementation of

[ILogger](../interfaces/ilogger.md).[reportError](../interfaces/ilogger.md#reporterror)

#### Defined in

[common/Logger.ts:74](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/Logger.ts#L74)

___

### save

▸ **save**(`filename`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `filename` | `any` |

#### Returns

`Promise`\<`void`\>

#### Implementation of

[ILogger](../interfaces/ilogger.md).[save](../interfaces/ilogger.md#save)

#### Defined in

[common/Logger.ts:94](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/Logger.ts#L94)

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

#### Implementation of

[ILogger](../interfaces/ilogger.md).[setOptions](../interfaces/ilogger.md#setoptions)

#### Defined in

[common/Logger.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/Logger.ts#L17)

___

### toString

▸ **toString**(`...args`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `any`[] |

#### Returns

`string`

#### Defined in

[common/Logger.ts:54](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/Logger.ts#L54)

___

### warn

▸ **warn**(`...message`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...message` | `any`[] |

#### Returns

`void`

#### Implementation of

[ILogger](../interfaces/ilogger.md).[warn](../interfaces/ilogger.md#warn)

#### Defined in

[common/Logger.ts:48](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/Logger.ts#L48)
