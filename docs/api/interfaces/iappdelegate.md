[bpmn-server](../README.md) / IAppDelegate

# Interface: IAppDelegate

Application Delegate Object to respond to various events and services:
 
 1.  receive all events from workflow
 2.  receive service calls
 3.  receive message and signal calls 
 4.  execute scripts

## Implemented by

- [`DefaultAppDelegate`](../classes/defaultappdelegate.md)

## Table of contents

### Properties

- [moddleOptions](iappdelegate.md#moddleoptions)

### Methods

- [executionStarted](iappdelegate.md#executionstarted)
- [getServicesProvider](iappdelegate.md#getservicesprovider)
- [issueMessage](iappdelegate.md#issuemessage)
- [issueSignal](iappdelegate.md#issuesignal)
- [messageThrown](iappdelegate.md#messagethrown)
- [sendEmail](iappdelegate.md#sendemail)
- [serviceCalled](iappdelegate.md#servicecalled)
- [signalThrown](iappdelegate.md#signalthrown)
- [startUp](iappdelegate.md#startup)

## Properties

### moddleOptions

• **moddleOptions**: `any`

#### Defined in

[interfaces/common.ts:73](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L73)

## Methods

### executionStarted

▸ **executionStarted**(`execution`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `execution` | `any` |

#### Returns

`any`

#### Defined in

[interfaces/common.ts:76](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L76)

___

### getServicesProvider

▸ **getServicesProvider**(`IExecution`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `IExecution` | `any` |

#### Returns

`any`

#### Defined in

[interfaces/common.ts:74](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L74)

___

### issueMessage

▸ **issueMessage**(`messageId`, `data`): `any`

is called when an event throws a message that can not be answered by another process

#### Parameters

| Name | Type |
| :------ | :------ |
| `messageId` | `any` |
| `data` | `any` |

#### Returns

`any`

#### Defined in

[interfaces/common.ts:87](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L87)

___

### issueSignal

▸ **issueSignal**(`messageId`, `data`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `messageId` | `any` |
| `data` | `any` |

#### Returns

`any`

#### Defined in

[interfaces/common.ts:88](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L88)

___

### messageThrown

▸ **messageThrown**(`signalId`, `data`, `messageMatchingKey`, `item`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `signalId` | `any` |
| `data` | `any` |
| `messageMatchingKey` | `any` |
| `item` | [`IItem`](iitem.md) |

#### Returns

`any`

#### Defined in

[interfaces/common.ts:78](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L78)

___

### sendEmail

▸ **sendEmail**(`to`, `msg`, `body`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `to` | `any` |
| `msg` | `any` |
| `body` | `any` |

#### Returns

`any`

#### Defined in

[interfaces/common.ts:75](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L75)

___

### serviceCalled

▸ **serviceCalled**(`serviceName`, `data`, `item`): `any`

is called only if the serviceTask has no implementation; otherwise the specified implementation will be called.

#### Parameters

| Name | Type |
| :------ | :------ |
| `serviceName` | `any` |
| `data` | `any` |
| `item` | [`IItem`](iitem.md) |

#### Returns

`any`

#### Defined in

[interfaces/common.ts:94](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L94)

___

### signalThrown

▸ **signalThrown**(`signalId`, `data`, `messageMatchingKey`, `item`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `signalId` | `any` |
| `data` | `any` |
| `messageMatchingKey` | `any` |
| `item` | [`IItem`](iitem.md) |

#### Returns

`any`

#### Defined in

[interfaces/common.ts:79](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L79)

___

### startUp

▸ **startUp**(`options`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | `any` |

#### Returns

`any`

#### Defined in

[interfaces/common.ts:77](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L77)
