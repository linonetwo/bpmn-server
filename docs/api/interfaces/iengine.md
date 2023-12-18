[bpmn-server](../README.md) / IEngine

# Interface: IEngine

## Implemented by

- [`Engine`](../classes/Engine.md)

## Table of contents

### Methods

- [assign](IEngine.md#assign)
- [get](IEngine.md#get)
- [invoke](IEngine.md#invoke)
- [start](IEngine.md#start)
- [startEvent](IEngine.md#startevent)
- [startRepeatTimerEvent](IEngine.md#startrepeattimerevent)
- [throwMessage](IEngine.md#throwmessage)
- [throwSignal](IEngine.md#throwsignal)

## Methods

### assign

▸ **assign**(`itemQuery`, `data`, `assignment`, `userName`, `options?`): `Promise`\<[`IExecution`](iexecution.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `itemQuery` | `any` |
| `data` | `Object` |
| `assignment` | `Object` |
| `userName` | `string` |
| `options?` | `Object` |

#### Returns

`Promise`\<[`IExecution`](iexecution.md)\>

#### Defined in

[interfaces/server.ts:69](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/server.ts#L69)

___

### get

▸ **get**(`instanceQuery`): `Promise`\<[`IExecution`](iexecution.md)\>

restores an instance into memeory or provides you access to a running instance

this will also resume execution

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `instanceQuery` | `any` | criteria to fetch the instance query example: { id: instanceId} { data: {caseId: 1005}} { items.id : 'abcc111322'} { items.itemKey : 'businesskey here'} |

#### Returns

`Promise`\<[`IExecution`](iexecution.md)\>

#### Defined in

[interfaces/server.ts:54](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/server.ts#L54)

___

### invoke

▸ **invoke**(`itemQuery`, `data`, `userName?`, `options?`): `Promise`\<[`IExecution`](iexecution.md)\>

Continue an existing item that is in a wait state

-------------------------------------------------
scenario:
		itemId			{itemId: value }
		itemKey			{itemKey: value}
		instance,task	{instanceId: instanceId, elementId: value }

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `itemQuery` | `any` | criteria to retrieve the item |
| `data` | `Object` |  |
| `userName?` | `string` | - |
| `options?` | `Object` | - |

#### Returns

`Promise`\<[`IExecution`](iexecution.md)\>

#### Defined in

[interfaces/server.ts:67](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/server.ts#L67)

___

### start

▸ **start**(`name`, `data?`, `startNodeId?`, `userName?`, `options?`): `Promise`\<[`IExecution`](iexecution.md)\>

loads a definitions  and start execution

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `name` | `any` | name of the process to start |
| `data?` | `any` | input data |
| `startNodeId?` | `string` | in process has multiple start node; you need to specify which one |
| `userName?` | `string` | - |
| `options?` | `any` | - |

#### Returns

`Promise`\<[`IExecution`](iexecution.md)\>

#### Defined in

[interfaces/server.ts:40](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/server.ts#L40)

___

### startEvent

▸ **startEvent**(`instanceId`, `elementId`, `data?`): `Promise`\<[`IExecution`](iexecution.md)\>

Invoking an event (usually start event of a secondary process) against an existing instance
or
Invoking a start event (of a secondary process) against an existing instance
----------------------------------------------------------------------------
	 instance,task
```
	{instanceId: instanceId, elementId: value }
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `instanceId` | `any` |
| `elementId` | `any` |
| `data?` | `Object` |

#### Returns

`Promise`\<[`IExecution`](iexecution.md)\>

#### Defined in

[interfaces/server.ts:90](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/server.ts#L90)

___

### startRepeatTimerEvent

▸ **startRepeatTimerEvent**(`instanceId`, `prevItem`, `data`, `options?`): `Promise`\<[`IExecution`](iexecution.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `instanceId` | `any` |
| `prevItem` | [`IItem`](IItem.md) |
| `data` | `Object` |
| `options?` | `Object` |

#### Returns

`Promise`\<[`IExecution`](iexecution.md)\>

#### Defined in

[interfaces/server.ts:72](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/server.ts#L72)

___

### throwMessage

▸ **throwMessage**(`messageId`, `data`, `matchingQuery`): `Promise`\<[`IExecution`](iexecution.md)\>

signal/message raise a signal or throw a message

will seach for a matching event/task given the signalId/messageId

that can be againt a running instance or it may start a new instance
----------------------------------------------------------------------------

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `messageId` | `any` | the id of the message or signal as per bpmn definition |
| `data` | `Object` | message data |
| `matchingQuery` | `Object` | - |

#### Returns

`Promise`\<[`IExecution`](iexecution.md)\>

#### Defined in

[interfaces/server.ts:104](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/server.ts#L104)

___

### throwSignal

▸ **throwSignal**(`signalId`, `data`, `matchingQuery`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `signalId` | `any` |
| `data` | `Object` |
| `matchingQuery` | `Object` |

#### Returns

`any`

#### Defined in

[interfaces/server.ts:105](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/server.ts#L105)
