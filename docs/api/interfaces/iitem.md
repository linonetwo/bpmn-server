[bpmn-server](../README.md) / IItem

# Interface: IItem

## Hierarchy

- [`IItemData`](iitemdata.md)

  ↳ **`IItem`**

## Implemented by

- [`Item`](../classes/item.md)

## Table of contents

### Properties

- [assignee](iitem.md#assignee)
- [candidateGroups](iitem.md#candidategroups)
- [candidateUsers](iitem.md#candidateusers)
- [context](iitem.md#context)
- [dueDate](iitem.md#duedate)
- [element](iitem.md#element)
- [elementId](iitem.md#elementid)
- [endedAt](iitem.md#endedat)
- [followUpDate](iitem.md#followupdate)
- [id](iitem.md#id)
- [instanceId](iitem.md#instanceid)
- [itemKey](iitem.md#itemkey)
- [messageId](iitem.md#messageid)
- [name](iitem.md#name)
- [node](iitem.md#node)
- [priority](iitem.md#priority)
- [processName](iitem.md#processname)
- [seq](iitem.md#seq)
- [signalId](iitem.md#signalid)
- [startedAt](iitem.md#startedat)
- [status](iitem.md#status)
- [timeDue](iitem.md#timedue)
- [token](iitem.md#token)
- [tokenId](iitem.md#tokenid)
- [type](iitem.md#type)
- [userName](iitem.md#username)
- [vars](iitem.md#vars)

## Properties

### assignee

• **assignee**: `any`

#### Inherited from

[IItemData](iitemdata.md).[assignee](iitemdata.md#assignee)

#### Defined in

[interfaces/DataObjects.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L22)

___

### candidateGroups

• **candidateGroups**: `any`

#### Inherited from

[IItemData](iitemdata.md).[candidateGroups](iitemdata.md#candidategroups)

#### Defined in

[interfaces/DataObjects.ts:23](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L23)

___

### candidateUsers

• **candidateUsers**: `any`

#### Inherited from

[IItemData](iitemdata.md).[candidateUsers](iitemdata.md#candidateusers)

#### Defined in

[interfaces/DataObjects.ts:24](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L24)

___

### context

• **context**: [`IExecution`](iexecution.md)

#### Defined in

[interfaces/engine.ts:136](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/engine.ts#L136)

___

### dueDate

• **dueDate**: `any`

#### Inherited from

[IItemData](iitemdata.md).[dueDate](iitemdata.md#duedate)

#### Defined in

[interfaces/DataObjects.ts:25](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L25)

___

### element

• **element**: [`Element`](../classes/element.md)

#### Defined in

[interfaces/engine.ts:134](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/engine.ts#L134)

___

### elementId

• **elementId**: `string`

#### Inherited from

[IItemData](iitemdata.md).[elementId](iitemdata.md#elementid)

#### Defined in

[interfaces/DataObjects.ts:6](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L6)

___

### endedAt

• **endedAt**: `any`

#### Inherited from

[IItemData](iitemdata.md).[endedAt](iitemdata.md#endedat)

#### Defined in

[interfaces/DataObjects.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L14)

___

### followUpDate

• **followUpDate**: `any`

#### Inherited from

[IItemData](iitemdata.md).[followUpDate](iitemdata.md#followupdate)

#### Defined in

[interfaces/DataObjects.ts:26](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L26)

___

### id

• **id**: `string`

#### Inherited from

[IItemData](iitemdata.md).[id](iitemdata.md#id)

#### Defined in

[interfaces/DataObjects.ts:4](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L4)

___

### instanceId

• **instanceId**: `string`

#### Inherited from

[IItemData](iitemdata.md).[instanceId](iitemdata.md#instanceid)

#### Defined in

[interfaces/DataObjects.ts:9](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L9)

___

### itemKey

• **itemKey**: `string`

#### Inherited from

[IItemData](iitemdata.md).[itemKey](iitemdata.md#itemkey)

#### Defined in

[interfaces/DataObjects.ts:5](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L5)

___

### messageId

• **messageId**: `any`

#### Inherited from

[IItemData](iitemdata.md).[messageId](iitemdata.md#messageid)

#### Defined in

[interfaces/DataObjects.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L19)

___

### name

• **name**: `string`

#### Inherited from

[IItemData](iitemdata.md).[name](iitemdata.md#name)

#### Defined in

[interfaces/DataObjects.ts:7](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L7)

___

### node

• **node**: [`Node`](../classes/node.md)

#### Defined in

[interfaces/engine.ts:137](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/engine.ts#L137)

___

### priority

• **priority**: `any`

#### Inherited from

[IItemData](iitemdata.md).[priority](iitemdata.md#priority)

#### Defined in

[interfaces/DataObjects.ts:27](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L27)

___

### processName

• `Optional` **processName**: `string`

#### Inherited from

[IItemData](iitemdata.md).[processName](iitemdata.md#processname)

#### Defined in

[interfaces/DataObjects.ts:10](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L10)

___

### seq

• **seq**: `any`

#### Inherited from

[IItemData](iitemdata.md).[seq](iitemdata.md#seq)

#### Defined in

[interfaces/DataObjects.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L15)

___

### signalId

• **signalId**: `any`

#### Inherited from

[IItemData](iitemdata.md).[signalId](iitemdata.md#signalid)

#### Defined in

[interfaces/DataObjects.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L20)

___

### startedAt

• **startedAt**: `any`

#### Inherited from

[IItemData](iitemdata.md).[startedAt](iitemdata.md#startedat)

#### Defined in

[interfaces/DataObjects.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L13)

___

### status

• **status**: [`ITEM_STATUS`](../enums/item_status.md)

#### Inherited from

[IItemData](iitemdata.md).[status](iitemdata.md#status)

#### Defined in

[interfaces/DataObjects.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L17)

___

### timeDue

• **timeDue**: `Date`

#### Inherited from

[IItemData](iitemdata.md).[timeDue](iitemdata.md#timedue)

#### Defined in

[interfaces/DataObjects.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L16)

___

### token

• **token**: [`Token`](../classes/token.md)

#### Defined in

[interfaces/engine.ts:135](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/engine.ts#L135)

___

### tokenId

• **tokenId**: `any`

#### Inherited from

[IItemData](iitemdata.md).[tokenId](iitemdata.md#tokenid)

#### Defined in

[interfaces/DataObjects.ts:11](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L11)

___

### type

• **type**: `string`

#### Inherited from

[IItemData](iitemdata.md).[type](iitemdata.md#type)

#### Defined in

[interfaces/DataObjects.ts:8](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L8)

___

### userName

• **userName**: `any`

#### Inherited from

[IItemData](iitemdata.md).[userName](iitemdata.md#username)

#### Defined in

[interfaces/DataObjects.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L12)

___

### vars

• **vars**: `any`

#### Inherited from

[IItemData](iitemdata.md).[vars](iitemdata.md#vars)

#### Defined in

[interfaces/DataObjects.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/DataObjects.ts#L21)
