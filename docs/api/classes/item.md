[bpmn-server](../README.md) / Item

# Class: Item

## Implements

- [`IItem`](../interfaces/iitem.md)

## Table of contents

### Constructors

- [constructor](item.md#constructor)

### Properties

- [assignee](item.md#assignee)
- [candidateGroups](item.md#candidategroups)
- [candidateUsers](item.md#candidateusers)
- [dueDate](item.md#duedate)
- [element](item.md#element)
- [endedAt](item.md#endedat)
- [followUpDate](item.md#followupdate)
- [id](item.md#id)
- [input](item.md#input)
- [instanceId](item.md#instanceid)
- [itemKey](item.md#itemkey)
- [messageId](item.md#messageid)
- [output](item.md#output)
- [priority](item.md#priority)
- [seq](item.md#seq)
- [signalId](item.md#signalid)
- [startedAt](item.md#startedat)
- [status](item.md#status)
- [timeDue](item.md#timedue)
- [timerCount](item.md#timercount)
- [token](item.md#token)
- [userName](item.md#username)
- [vars](item.md#vars)

### Accessors

- [context](item.md#context)
- [data](item.md#data)
- [elementId](item.md#elementid)
- [name](item.md#name)
- [node](item.md#node)
- [options](item.md#options)
- [tokenId](item.md#tokenid)
- [type](item.md#type)

### Methods

- [log](item.md#log)
- [save](item.md#save)
- [setData](item.md#setdata)
- [load](item.md#load)

## Constructors

### constructor

• **new Item**(`element`, `token`, `status?`): [`Item`](item.md)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `element` | `any` | `undefined` |
| `token` | `any` | `undefined` |
| `status` | [`ITEM_STATUS`](../enums/item_status.md) | `ITEM_STATUS.start` |

#### Returns

[`Item`](item.md)

#### Defined in

[engine/Item.ts:55](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L55)

## Properties

### assignee

• **assignee**: `any`

#### Implementation of

[IItem](../interfaces/iitem.md).[assignee](../interfaces/iitem.md#assignee)

#### Defined in

[engine/Item.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L20)

___

### candidateGroups

• **candidateGroups**: `any`

#### Implementation of

[IItem](../interfaces/iitem.md).[candidateGroups](../interfaces/iitem.md#candidategroups)

#### Defined in

[engine/Item.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L21)

___

### candidateUsers

• **candidateUsers**: `any`

#### Implementation of

[IItem](../interfaces/iitem.md).[candidateUsers](../interfaces/iitem.md#candidateusers)

#### Defined in

[engine/Item.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L22)

___

### dueDate

• **dueDate**: `any`

#### Implementation of

[IItem](../interfaces/iitem.md).[dueDate](../interfaces/iitem.md#duedate)

#### Defined in

[engine/Item.ts:23](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L23)

___

### element

• **element**: [`Element`](element.md)

#### Implementation of

[IItem](../interfaces/iitem.md).[element](../interfaces/iitem.md#element)

#### Defined in

[engine/Item.ts:10](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L10)

___

### endedAt

• **endedAt**: `any` = `null`

#### Implementation of

[IItem](../interfaces/iitem.md).[endedAt](../interfaces/iitem.md#endedat)

#### Defined in

[engine/Item.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L15)

___

### followUpDate

• **followUpDate**: `any`

#### Implementation of

[IItem](../interfaces/iitem.md).[followUpDate](../interfaces/iitem.md#followupdate)

#### Defined in

[engine/Item.ts:24](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L24)

___

### id

• **id**: `any`

#### Implementation of

[IItem](../interfaces/iitem.md).[id](../interfaces/iitem.md#id)

#### Defined in

[engine/Item.ts:8](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L8)

___

### input

• **input**: `Object` = `{}`

#### Defined in

[engine/Item.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L17)

___

### instanceId

• **instanceId**: `any`

#### Implementation of

[IItem](../interfaces/iitem.md).[instanceId](../interfaces/iitem.md#instanceid)

#### Defined in

[engine/Item.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L16)

___

### itemKey

• **itemKey**: `string`

#### Implementation of

[IItem](../interfaces/iitem.md).[itemKey](../interfaces/iitem.md#itemkey)

#### Defined in

[engine/Item.ts:9](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L9)

___

### messageId

• **messageId**: `any`

#### Implementation of

[IItem](../interfaces/iitem.md).[messageId](../interfaces/iitem.md#messageid)

#### Defined in

[engine/Item.ts:52](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L52)

___

### output

• **output**: `Object` = `{}`

#### Defined in

[engine/Item.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L18)

___

### priority

• **priority**: `any`

#### Implementation of

[IItem](../interfaces/iitem.md).[priority](../interfaces/iitem.md#priority)

#### Defined in

[engine/Item.ts:25](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L25)

___

### seq

• **seq**: `any`

#### Implementation of

[IItem](../interfaces/iitem.md).[seq](../interfaces/iitem.md#seq)

#### Defined in

[engine/Item.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L12)

___

### signalId

• **signalId**: `any`

#### Implementation of

[IItem](../interfaces/iitem.md).[signalId](../interfaces/iitem.md#signalid)

#### Defined in

[engine/Item.ts:53](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L53)

___

### startedAt

• **startedAt**: `any`

#### Implementation of

[IItem](../interfaces/iitem.md).[startedAt](../interfaces/iitem.md#startedat)

#### Defined in

[engine/Item.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L14)

___

### status

• **status**: [`ITEM_STATUS`](../enums/item_status.md)

#### Implementation of

[IItem](../interfaces/iitem.md).[status](../interfaces/iitem.md#status)

#### Defined in

[engine/Item.ts:28](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L28)

___

### timeDue

• **timeDue**: `Date`

#### Implementation of

[IItem](../interfaces/iitem.md).[timeDue](../interfaces/iitem.md#timedue)

#### Defined in

[engine/Item.ts:49](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L49)

___

### timerCount

• **timerCount**: `any`

#### Defined in

[engine/Item.ts:50](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L50)

___

### token

• **token**: [`Token`](token.md)

#### Implementation of

[IItem](../interfaces/iitem.md).[token](../interfaces/iitem.md#token)

#### Defined in

[engine/Item.ts:11](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L11)

___

### userName

• **userName**: `any`

#### Implementation of

[IItem](../interfaces/iitem.md).[userName](../interfaces/iitem.md#username)

#### Defined in

[engine/Item.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L13)

___

### vars

• **vars**: `Object` = `{}`

#### Implementation of

[IItem](../interfaces/iitem.md).[vars](../interfaces/iitem.md#vars)

#### Defined in

[engine/Item.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L19)

## Accessors

### context

• `get` **context**(): [`IExecution`](../interfaces/iexecution.md)

#### Returns

[`IExecution`](../interfaces/iexecution.md)

#### Implementation of

[IItem](../interfaces/iitem.md).[context](../interfaces/iitem.md#context)

#### Defined in

[engine/Item.ts:34](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L34)

___

### data

• `get` **data**(): `any`

#### Returns

`any`

#### Defined in

[engine/Item.ts:30](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L30)

• `set` **data**(`val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `any` |

#### Returns

`void`

#### Defined in

[engine/Item.ts:31](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L31)

___

### elementId

• `get` **elementId**(): `any`

#### Returns

`any`

#### Implementation of

[IItem](../interfaces/iitem.md).[elementId](../interfaces/iitem.md#elementid)

#### Defined in

[engine/Item.ts:35](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L35)

___

### name

• `get` **name**(): `any`

#### Returns

`any`

#### Implementation of

[IItem](../interfaces/iitem.md).[name](../interfaces/iitem.md#name)

#### Defined in

[engine/Item.ts:36](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L36)

___

### node

• `get` **node**(): [`Node`](node.md)

#### Returns

[`Node`](node.md)

#### Implementation of

[IItem](../interfaces/iitem.md).[node](../interfaces/iitem.md#node)

#### Defined in

[engine/Item.ts:45](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L45)

___

### options

• `get` **options**(): `any`

#### Returns

`any`

#### Defined in

[engine/Item.ts:33](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L33)

___

### tokenId

• `get` **tokenId**(): `any`

#### Returns

`any`

#### Implementation of

[IItem](../interfaces/iitem.md).[tokenId](../interfaces/iitem.md#tokenid)

#### Defined in

[engine/Item.ts:39](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L39)

___

### type

• `get` **type**(): `any`

#### Returns

`any`

#### Implementation of

[IItem](../interfaces/iitem.md).[type](../interfaces/iitem.md#type)

#### Defined in

[engine/Item.ts:42](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L42)

## Methods

### log

▸ **log**(`msg`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `msg` | `any` |

#### Returns

`void`

#### Defined in

[engine/Item.ts:29](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L29)

___

### save

▸ **save**(): [`IItemData`](../interfaces/iitemdata.md)

#### Returns

[`IItemData`](../interfaces/iitemdata.md)

#### Defined in

[engine/Item.ts:64](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L64)

___

### setData

▸ **setData**(`val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `any` |

#### Returns

`void`

#### Defined in

[engine/Item.ts:32](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L32)

___

### load

▸ **load**(`execution`, `dataObject`, `token`): [`Item`](item.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `execution` | [`Execution`](execution.md) |
| `dataObject` | [`IItemData`](../interfaces/iitemdata.md) |
| `token` | `any` |

#### Returns

[`Item`](item.md)

#### Defined in

[engine/Item.ts:80](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Item.ts#L80)
