[bpmn-server](../README.md) / Transaction

# Class: Transaction

## Hierarchy

- [`SubProcess`](SubProcess.md)

  ↳ **`Transaction`**

## Table of contents

### Constructors

- [constructor](Transaction.md#constructor)

### Properties

- [assignee](Transaction.md#assignee)
- [attachedTo](Transaction.md#attachedto)
- [attachments](Transaction.md#attachments)
- [behaviours](Transaction.md#behaviours)
- [childProcess](Transaction.md#childprocess)
- [def](Transaction.md#def)
- [id](Transaction.md#id)
- [inbounds](Transaction.md#inbounds)
- [initiator](Transaction.md#initiator)
- [isFlow](Transaction.md#isflow)
- [lane](Transaction.md#lane)
- [messageId](Transaction.md#messageid)
- [name](Transaction.md#name)
- [outbounds](Transaction.md#outbounds)
- [process](Transaction.md#process)
- [scripts](Transaction.md#scripts)
- [signalId](Transaction.md#signalid)
- [subType](Transaction.md#subtype)
- [type](Transaction.md#type)

### Accessors

- [canBeInvoked](Transaction.md#canbeinvoked)
- [isCatching](Transaction.md#iscatching)
- [processId](Transaction.md#processid)
- [requiresWait](Transaction.md#requireswait)

### Methods

- [addBehaviour](Transaction.md#addbehaviour)
- [cancelBoundaryEvents](Transaction.md#cancelboundaryevents)
- [cancelEBG](Transaction.md#cancelebg)
- [continue](Transaction.md#continue)
- [describe](Transaction.md#describe)
- [doEvent](Transaction.md#doevent)
- [end](Transaction.md#end)
- [enter](Transaction.md#enter)
- [execute](Transaction.md#execute)
- [getBehaviour](Transaction.md#getbehaviour)
- [getInput](Transaction.md#getinput)
- [getItems](Transaction.md#getitems)
- [getItemsForToken](Transaction.md#getitemsfortoken)
- [getNodes](Transaction.md#getnodes)
- [getOutbounds](Transaction.md#getoutbounds)
- [getOutput](Transaction.md#getoutput)
- [hasBehaviour](Transaction.md#hasbehaviour)
- [init](Transaction.md#init)
- [restored](Transaction.md#restored)
- [resume](Transaction.md#resume)
- [run](Transaction.md#run)
- [setInput](Transaction.md#setinput)
- [start](Transaction.md#start)
- [startBoundaryEvents](Transaction.md#startboundaryevents)
- [validate](Transaction.md#validate)
- [Cancel](Transaction.md#cancel)
- [Compensate](Transaction.md#compensate)

## Constructors

### constructor

• **new Transaction**(`id`, `process`, `type`, `def`): [`Transaction`](Transaction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `any` |
| `process` | `any` |
| `type` | `any` |
| `def` | `any` |

#### Returns

[`Transaction`](Transaction.md)

#### Inherited from

[SubProcess](SubProcess.md).[constructor](SubProcess.md#constructor)

#### Defined in

[elements/Node.ts:29](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L29)

## Properties

### assignee

• **assignee**: `any`

#### Inherited from

[SubProcess](SubProcess.md).[assignee](SubProcess.md#assignee)

#### Defined in

[elements/Node.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L22)

___

### attachedTo

• **attachedTo**: [`Node`](Node.md)

#### Inherited from

[SubProcess](SubProcess.md).[attachedTo](SubProcess.md#attachedto)

#### Defined in

[elements/Node.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L18)

___

### attachments

• **attachments**: [`Node`](Node.md)[]

#### Inherited from

[SubProcess](SubProcess.md).[attachments](SubProcess.md#attachments)

#### Defined in

[elements/Node.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L17)

___

### behaviours

• **behaviours**: `Map`\<`any`, `any`\>

#### Inherited from

[SubProcess](SubProcess.md).[behaviours](SubProcess.md#behaviours)

#### Defined in

[elements/Element.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L17)

___

### childProcess

• **childProcess**: [`Process`](Process.md)

#### Inherited from

[SubProcess](SubProcess.md).[childProcess](SubProcess.md#childprocess)

#### Defined in

[elements/Tasks.ts:207](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Tasks.ts#L207)

___

### def

• **def**: `any`

#### Inherited from

[SubProcess](SubProcess.md).[def](SubProcess.md#def)

#### Defined in

[elements/Node.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L14)

___

### id

• **id**: `any`

#### Inherited from

[SubProcess](SubProcess.md).[id](SubProcess.md#id)

#### Defined in

[elements/Element.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L13)

___

### inbounds

• **inbounds**: [`Flow`](Flow.md)[]

#### Inherited from

[SubProcess](SubProcess.md).[inbounds](SubProcess.md#inbounds)

#### Defined in

[elements/Node.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L16)

___

### initiator

• **initiator**: `any`

#### Inherited from

[SubProcess](SubProcess.md).[initiator](SubProcess.md#initiator)

#### Defined in

[elements/Node.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L21)

___

### isFlow

• **isFlow**: `boolean` = `false`

#### Inherited from

[SubProcess](SubProcess.md).[isFlow](SubProcess.md#isflow)

#### Defined in

[elements/Element.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L18)

___

### lane

• **lane**: `any`

#### Inherited from

[SubProcess](SubProcess.md).[lane](SubProcess.md#lane)

#### Defined in

[elements/Element.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L19)

___

### messageId

• **messageId**: `any`

#### Inherited from

[SubProcess](SubProcess.md).[messageId](SubProcess.md#messageid)

#### Defined in

[elements/Node.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L19)

___

### name

• **name**: `any`

#### Inherited from

[SubProcess](SubProcess.md).[name](SubProcess.md#name)

#### Defined in

[elements/Node.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L12)

___

### outbounds

• **outbounds**: [`Flow`](Flow.md)[]

#### Inherited from

[SubProcess](SubProcess.md).[outbounds](SubProcess.md#outbounds)

#### Defined in

[elements/Node.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L15)

___

### process

• **process**: `any`

#### Inherited from

[SubProcess](SubProcess.md).[process](SubProcess.md#process)

#### Defined in

[elements/Node.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L13)

___

### scripts

• **scripts**: `Map`\<`any`, `any`\>

#### Inherited from

[SubProcess](SubProcess.md).[scripts](SubProcess.md#scripts)

#### Defined in

[elements/Node.ts:23](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L23)

___

### signalId

• **signalId**: `any`

#### Inherited from

[SubProcess](SubProcess.md).[signalId](SubProcess.md#signalid)

#### Defined in

[elements/Node.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L20)

___

### subType

• **subType**: `any`

#### Inherited from

[SubProcess](SubProcess.md).[subType](SubProcess.md#subtype)

#### Defined in

[elements/Element.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L15)

___

### type

• **type**: `any`

#### Inherited from

[SubProcess](SubProcess.md).[type](SubProcess.md#type)

#### Defined in

[elements/Element.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L14)

## Accessors

### canBeInvoked

• `get` **canBeInvoked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

SubProcess.canBeInvoked

#### Defined in

[elements/Tasks.ts:209](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Tasks.ts#L209)

___

### isCatching

• `get` **isCatching**(): `boolean`

#### Returns

`boolean`

#### Inherited from

SubProcess.isCatching

#### Defined in

[elements/Node.ts:125](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L125)

___

### processId

• `get` **processId**(): `any`

#### Returns

`any`

#### Inherited from

SubProcess.processId

#### Defined in

[elements/Node.ts:24](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L24)

___

### requiresWait

• `get` **requiresWait**(): `boolean`

#### Returns

`boolean`

#### Overrides

SubProcess.requiresWait

#### Defined in

[elements/Transaction.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Transaction.ts#L15)

## Methods

### addBehaviour

▸ **addBehaviour**(`nane`, `behavriour`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `nane` | `any` |
| `behavriour` | `any` |

#### Returns

`void`

#### Inherited from

[SubProcess](SubProcess.md).[addBehaviour](SubProcess.md#addbehaviour)

#### Defined in

[elements/Element.ts:39](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L39)

___

### cancelBoundaryEvents

▸ **cancelBoundaryEvents**(`item`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |

#### Returns

`Promise`\<`void`\>

#### Inherited from

[SubProcess](SubProcess.md).[cancelBoundaryEvents](SubProcess.md#cancelboundaryevents)

#### Defined in

[elements/Node.ts:235](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L235)

___

### cancelEBG

▸ **cancelEBG**(`item`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |

#### Returns

`Promise`\<`void`\>

#### Inherited from

[SubProcess](SubProcess.md).[cancelEBG](SubProcess.md#cancelebg)

#### Defined in

[elements/Node.ts:227](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L227)

___

### continue

▸ **continue**(`item`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`Promise`\<`void`\>

#### Inherited from

[SubProcess](SubProcess.md).[continue](SubProcess.md#continue)

#### Defined in

[elements/Node.ts:208](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L208)

___

### describe

▸ **describe**(): `string`[][]

#### Returns

`string`[][]

#### Inherited from

[SubProcess](SubProcess.md).[describe](SubProcess.md#describe)

#### Defined in

[elements/Element.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L21)

___

### doEvent

▸ **doEvent**(`item`, `event`, `newStatus`): `Promise`\<`any`[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |
| `event` | [`EXECUTION_EVENT`](../enums/execution_event.md) |
| `newStatus` | [`ITEM_STATUS`](../enums/item_status.md) |

#### Returns

`Promise`\<`any`[]\>

#### Inherited from

[SubProcess](SubProcess.md).[doEvent](SubProcess.md#doevent)

#### Defined in

[elements/Node.ts:53](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L53)

___

### end

▸ **end**(`item`, `cancel?`): `Promise`\<`void`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `item` | `any` | `undefined` |
| `cancel` | `Boolean` | `false` |

#### Returns

`Promise`\<`void`\>

#### Overrides

[SubProcess](SubProcess.md).[end](SubProcess.md#end)

#### Defined in

[elements/Transaction.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Transaction.ts#L17)

___

### enter

▸ **enter**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`void`

#### Inherited from

[SubProcess](SubProcess.md).[enter](SubProcess.md#enter)

#### Defined in

[elements/Node.ts:109](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L109)

___

### execute

▸ **execute**(`item`): `Promise`\<`void` \| [`wait`](../enums/node_action.md#wait) \| [`end`](../enums/node_action.md#end) \| [`error`](../enums/node_action.md#error) \| [`abort`](../enums/node_action.md#abort)\>

this is the primary exectuion method for a node

considerations: the following are handled by Token
     1.  Loops we are inside a loop already (if any)
     2.  Gatways 
     3.  Subprocess the parent node is fired as normal
             run method will fire the subprocess invoking a new token and will go into wait

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`Promise`\<`void` \| [`wait`](../enums/node_action.md#wait) \| [`end`](../enums/node_action.md#end) \| [`error`](../enums/node_action.md#error) \| [`abort`](../enums/node_action.md#abort)\>

#### Inherited from

[SubProcess](SubProcess.md).[execute](SubProcess.md#execute)

#### Defined in

[elements/Node.ts:135](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L135)

___

### getBehaviour

▸ **getBehaviour**(`name`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `any` |

#### Returns

`any`

#### Inherited from

[SubProcess](SubProcess.md).[getBehaviour](SubProcess.md#getbehaviour)

#### Defined in

[elements/Element.ts:36](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L36)

___

### getInput

▸ **getInput**(`item`, `input`): `Promise`\<{}\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |
| `input` | `any` |

#### Returns

`Promise`\<{}\>

#### Inherited from

[SubProcess](SubProcess.md).[getInput](SubProcess.md#getinput)

#### Defined in

[elements/Node.ts:91](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L91)

___

### getItems

▸ **getItems**(`item`): `any`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |

#### Returns

`any`[]

#### Defined in

[elements/Transaction.ts:92](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Transaction.ts#L92)

___

### getItemsForToken

▸ **getItemsForToken**(`token`): `any`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `token` | `any` |

#### Returns

`any`[]

#### Defined in

[elements/Transaction.ts:78](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Transaction.ts#L78)

___

### getNodes

▸ **getNodes**(): [`Node`](Node.md)[]

#### Returns

[`Node`](Node.md)[]

#### Defined in

[elements/Transaction.ts:74](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Transaction.ts#L74)

___

### getOutbounds

▸ **getOutbounds**(`item`): [`Item`](Item.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

[`Item`](Item.md)[]

#### Inherited from

[SubProcess](SubProcess.md).[getOutbounds](SubProcess.md#getoutbounds)

#### Defined in

[elements/Node.ts:311](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L311)

___

### getOutput

▸ **getOutput**(`item`): `Promise`\<{}\>

transform data using output rules
todo

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`Promise`\<{}\>

#### Inherited from

[SubProcess](SubProcess.md).[getOutput](SubProcess.md#getoutput)

#### Defined in

[elements/Node.ts:105](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L105)

___

### hasBehaviour

▸ **hasBehaviour**(`name`): `boolean`

respond by providing behaviour attributes beyond item and node information
 ex: timer due , input/outupt , fields

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `any` |

#### Returns

`boolean`

#### Inherited from

[SubProcess](SubProcess.md).[hasBehaviour](SubProcess.md#hasbehaviour)

#### Defined in

[elements/Element.ts:32](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L32)

___

### init

▸ **init**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`void`

#### Inherited from

[SubProcess](SubProcess.md).[init](SubProcess.md#init)

#### Defined in

[elements/Node.ts:306](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L306)

___

### restored

▸ **restored**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`void`

#### Inherited from

[SubProcess](SubProcess.md).[restored](SubProcess.md#restored)

#### Defined in

[elements/Element.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L22)

___

### resume

▸ **resume**(`item`): `void`

is called by the token after an execution resume for every active (in wait) item
different than init, which is called for all items

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`void`

#### Inherited from

[SubProcess](SubProcess.md).[resume](SubProcess.md#resume)

#### Defined in

[elements/Node.ts:303](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L303)

___

### run

▸ **run**(`item`): `Promise`\<[`NODE_ACTION`](../enums/node_action.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`Promise`\<[`NODE_ACTION`](../enums/node_action.md)\>

#### Inherited from

[SubProcess](SubProcess.md).[run](SubProcess.md#run)

#### Defined in

[elements/Node.ts:223](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L223)

___

### setInput

▸ **setInput**(`item`, `input`): `Promise`\<`void`\>

is Called after execution 
transform data using input rules
todo

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |
| `input` | `any` |

#### Returns

`Promise`\<`void`\>

#### Inherited from

[SubProcess](SubProcess.md).[setInput](SubProcess.md#setinput)

#### Defined in

[elements/Node.ts:81](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L81)

___

### start

▸ **start**(`item`): `Promise`\<[`NODE_ACTION`](../enums/node_action.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |

#### Returns

`Promise`\<[`NODE_ACTION`](../enums/node_action.md)\>

#### Overrides

[SubProcess](SubProcess.md).[start](SubProcess.md#start)

#### Defined in

[elements/Transaction.ts:97](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Transaction.ts#L97)

___

### startBoundaryEvents

▸ **startBoundaryEvents**(`item`, `token`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |
| `token` | `any` |

#### Returns

`Promise`\<`void`\>

#### Inherited from

[SubProcess](SubProcess.md).[startBoundaryEvents](SubProcess.md#startboundaryevents)

#### Defined in

[elements/Node.ts:330](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L330)

___

### validate

▸ **validate**(`item`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`Promise`\<`void`\>

#### Inherited from

[SubProcess](SubProcess.md).[validate](SubProcess.md#validate)

#### Defined in

[elements/Node.ts:42](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L42)

___

### Cancel

▸ **Cancel**(`transaction`): `Promise`\<`void`\>

Cancel Transaction
 is called by Throw Cancel Event
 
 1.  Aborts any started items in the transaction
 2.  Compensate any completed items

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | `any` |

#### Returns

`Promise`\<`void`\>

#### Defined in

[elements/Transaction.ts:31](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Transaction.ts#L31)

___

### Compensate

▸ **Compensate**(`transItem`): `Promise`\<`void`\>

Compensate Transaction
 is called by Throw Compensate Event
 this is called outside of the transaction
 
 1.  Compensate any completed items

#### Parameters

| Name | Type |
| :------ | :------ |
| `transItem` | `any` |

#### Returns

`Promise`\<`void`\>

#### Defined in

[elements/Transaction.ts:43](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Transaction.ts#L43)
