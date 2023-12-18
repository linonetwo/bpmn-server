[bpmn-server](../README.md) / DefaultAppDelegate

# Class: DefaultAppDelegate

Application Delegate Object to respond to various events and services:
 
 1.  receive all events from workflow
 2.  receive service calls
 3.  receive message and signal calls 
 4.  execute scripts

## Implements

- [`IAppDelegate`](../interfaces/iappdelegate.md)

## Table of contents

### Constructors

- [constructor](defaultappdelegate.md#constructor)

### Properties

- [server](defaultappdelegate.md#server)

### Accessors

- [moddleOptions](defaultappdelegate.md#moddleoptions)

### Methods

- [executionEvent](defaultappdelegate.md#executionevent)
- [executionStarted](defaultappdelegate.md#executionstarted)
- [getServicesProvider](defaultappdelegate.md#getservicesprovider)
- [issueMessage](defaultappdelegate.md#issuemessage)
- [issueSignal](defaultappdelegate.md#issuesignal)
- [messageThrown](defaultappdelegate.md#messagethrown)
- [sendEmail](defaultappdelegate.md#sendemail)
- [serviceCalled](defaultappdelegate.md#servicecalled)
- [signalThrown](defaultappdelegate.md#signalthrown)
- [startUp](defaultappdelegate.md#startup)

## Constructors

### constructor

• **new DefaultAppDelegate**(`server`): [`DefaultAppDelegate`](defaultappdelegate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | `any` |

#### Returns

[`DefaultAppDelegate`](defaultappdelegate.md)

#### Defined in

[engine/DefaultAppDelegate.ts:11](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/DefaultAppDelegate.ts#L11)

## Properties

### server

• **server**: `any`

#### Defined in

[engine/DefaultAppDelegate.ts:8](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/DefaultAppDelegate.ts#L8)

## Accessors

### moddleOptions

• `get` **moddleOptions**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `prefix` | `string` |
| `types` | (\{ `extends`: `string`[] ; `isAbstract`: `boolean` = true; `name`: `string` = "Task"; `properties`: \{ `isAttr`: `boolean` = true; `name`: `string` = "result"; `type`: `string` = "String" }[] ; `superClass?`: `undefined`  } \| \{ `extends?`: `undefined` ; `isAbstract?`: `undefined` = true; `name`: `string` = "Output"; `properties?`: `undefined` ; `superClass`: `string`[]  })[] |
| `uri` | `string` |
| `xml` | \{ `tagAlias`: `string` = "lowerCase" } |
| `xml.tagAlias` | `string` |

#### Implementation of

[IAppDelegate](../interfaces/iappdelegate.md).[moddleOptions](../interfaces/iappdelegate.md#moddleoptions)

#### Defined in

[engine/DefaultAppDelegate.ts:29](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/DefaultAppDelegate.ts#L29)

## Methods

### executionEvent

▸ **executionEvent**(`context`, `event`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `context` | `any` |
| `event` | `any` |

#### Returns

`Promise`\<`void`\>

#### Defined in

[engine/DefaultAppDelegate.ts:35](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/DefaultAppDelegate.ts#L35)

___

### executionStarted

▸ **executionStarted**(`execution`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `execution` | [`IExecution`](../interfaces/iexecution.md) |

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IAppDelegate](../interfaces/iappdelegate.md).[executionStarted](../interfaces/iappdelegate.md#executionstarted)

#### Defined in

[engine/DefaultAppDelegate.ts:32](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/DefaultAppDelegate.ts#L32)

___

### getServicesProvider

▸ **getServicesProvider**(`context`): `Promise`\<[`DefaultAppDelegate`](defaultappdelegate.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `context` | `any` |

#### Returns

`Promise`\<[`DefaultAppDelegate`](defaultappdelegate.md)\>

#### Implementation of

[IAppDelegate](../interfaces/iappdelegate.md).[getServicesProvider](../interfaces/iappdelegate.md#getservicesprovider)

#### Defined in

[engine/DefaultAppDelegate.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/DefaultAppDelegate.ts#L18)

___

### issueMessage

▸ **issueMessage**(`messageId`, `data`): `Promise`\<`void`\>

is called when an event throws a message that can not be answered by another process

#### Parameters

| Name | Type |
| :------ | :------ |
| `messageId` | `any` |
| `data` | `any` |

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IAppDelegate](../interfaces/iappdelegate.md).[issueMessage](../interfaces/iappdelegate.md#issuemessage)

#### Defined in

[engine/DefaultAppDelegate.ts:64](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/DefaultAppDelegate.ts#L64)

___

### issueSignal

▸ **issueSignal**(`signalId`, `data`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `signalId` | `any` |
| `data` | `any` |

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IAppDelegate](../interfaces/iappdelegate.md).[issueSignal](../interfaces/iappdelegate.md#issuesignal)

#### Defined in

[engine/DefaultAppDelegate.ts:67](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/DefaultAppDelegate.ts#L67)

___

### messageThrown

▸ **messageThrown**(`messageId`, `data`, `messageMatchingKey`, `item`): `Promise`\<`void`\>

is called when a event throws a message

#### Parameters

| Name | Type |
| :------ | :------ |
| `messageId` | `any` |
| `data` | `any` |
| `messageMatchingKey` | `any` |
| `item` | [`Item`](item.md) |

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IAppDelegate](../interfaces/iappdelegate.md).[messageThrown](../interfaces/iappdelegate.md#messagethrown)

#### Defined in

[engine/DefaultAppDelegate.ts:46](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/DefaultAppDelegate.ts#L46)

___

### sendEmail

▸ **sendEmail**(`to`, `msg`, `body`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `to` | `any` |
| `msg` | `any` |
| `body` | `any` |

#### Returns

`void`

#### Implementation of

[IAppDelegate](../interfaces/iappdelegate.md).[sendEmail](../interfaces/iappdelegate.md#sendemail)

#### Defined in

[engine/DefaultAppDelegate.ts:25](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/DefaultAppDelegate.ts#L25)

___

### serviceCalled

▸ **serviceCalled**(`serviceName`, `data`, `item`): `Promise`\<`void`\>

is called only if the serviceTask has no implementation; otherwise the specified implementation will be called.

#### Parameters

| Name | Type |
| :------ | :------ |
| `serviceName` | `any` |
| `data` | `any` |
| `item` | [`Item`](item.md) |

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IAppDelegate](../interfaces/iappdelegate.md).[serviceCalled](../interfaces/iappdelegate.md#servicecalled)

#### Defined in

[engine/DefaultAppDelegate.ts:82](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/DefaultAppDelegate.ts#L82)

___

### signalThrown

▸ **signalThrown**(`signalId`, `data`, `messageMatchingKey`, `item`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `signalId` | `any` |
| `data` | `any` |
| `messageMatchingKey` | `any` |
| `item` | [`Item`](item.md) |

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IAppDelegate](../interfaces/iappdelegate.md).[signalThrown](../interfaces/iappdelegate.md#signalthrown)

#### Defined in

[engine/DefaultAppDelegate.ts:70](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/DefaultAppDelegate.ts#L70)

___

### startUp

▸ **startUp**(`options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | `any` |

#### Returns

`void`

#### Implementation of

[IAppDelegate](../interfaces/iappdelegate.md).[startUp](../interfaces/iappdelegate.md#startup)

#### Defined in

[engine/DefaultAppDelegate.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/DefaultAppDelegate.ts#L22)
