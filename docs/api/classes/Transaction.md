[bpmn-server](../README.md) / Transaction

# Class: Transaction

## Hierarchy

- [`SubProcess`](subprocess.md)

  ↳ **`Transaction`**

## Table of contents

### Constructors

- [constructor](transaction.md#constructor)

### Properties

- [assignee](transaction.md#assignee)
- [attachedTo](transaction.md#attachedto)
- [attachments](transaction.md#attachments)
- [behaviours](transaction.md#behaviours)
- [childProcess](transaction.md#childprocess)
- [def](transaction.md#def)
- [id](transaction.md#id)
- [inbounds](transaction.md#inbounds)
- [initiator](transaction.md#initiator)
- [isFlow](transaction.md#isflow)
- [lane](transaction.md#lane)
- [messageId](transaction.md#messageid)
- [name](transaction.md#name)
- [outbounds](transaction.md#outbounds)
- [process](transaction.md#process)
- [scripts](transaction.md#scripts)
- [signalId](transaction.md#signalid)
- [subType](transaction.md#subtype)
- [type](transaction.md#type)

### Accessors

- [canBeInvoked](transaction.md#canbeinvoked)
- [isCatching](transaction.md#iscatching)
- [processId](transaction.md#processid)
- [requiresWait](transaction.md#requireswait)

### Methods

- [addBehaviour](transaction.md#addbehaviour)
- [cancelBoundaryEvents](transaction.md#cancelboundaryevents)
- [cancelEBG](transaction.md#cancelebg)
- [continue](transaction.md#continue)
- [describe](transaction.md#describe)
- [doEvent](transaction.md#doevent)
- [end](transaction.md#end)
- [enter](transaction.md#enter)
- [execute](transaction.md#execute)
- [getBehaviour](transaction.md#getbehaviour)
- [getInput](transaction.md#getinput)
- [getItems](transaction.md#getitems)
- [getItemsForToken](transaction.md#getitemsfortoken)
- [getNodes](transaction.md#getnodes)
- [getOutbounds](transaction.md#getoutbounds)
- [getOutput](transaction.md#getoutput)
- [hasBehaviour](transaction.md#hasbehaviour)
- [init](transaction.md#init)
- [restored](transaction.md#restored)
- [resume](transaction.md#resume)
- [run](transaction.md#run)
- [setInput](transaction.md#setinput)
- [start](transaction.md#start)
- [startBoundaryEvents](transaction.md#startboundaryevents)
- [validate](transaction.md#validate)
- [Cancel](transaction.md#cancel)
- [Compensate](transaction.md#compensate)

## Constructors

### constructor

• **new Transaction**(`id`, `process`, `type`, `def`): [`Transaction`](transaction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `any` |
| `process` | `any` |
| `type` | `any` |
| `def` | `any` |

#### Returns

[`Transaction`](transaction.md)

#### Inherited from

[SubProcess](subprocess.md).[constructor](subprocess.md#constructor)

#### Defined in

[elements/Node.ts:29](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L29)

## Properties

### assignee

• **assignee**: `any`

#### Inherited from

[SubProcess](subprocess.md).[assignee](subprocess.md#assignee)

#### Defined in

[elements/Node.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L22)

___

### attachedTo

• **attachedTo**: [`Node`](node.md)

#### Inherited from

[SubProcess](subprocess.md).[attachedTo](subprocess.md#attachedto)

#### Defined in

[elements/Node.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L18)

___

### attachments

• **attachments**: [`Node`](node.md)[]

#### Inherited from

[SubProcess](subprocess.md).[attachments](subprocess.md#attachments)

#### Defined in

[elements/Node.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L17)

___

### behaviours

• **behaviours**: `Map`\<`any`, `any`\>

#### Inherited from

[SubProcess](subprocess.md).[behaviours](subprocess.md#behaviours)

#### Defined in

[elements/Element.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L17)

___

### childProcess

• **childProcess**: [`Process`](process.md)

#### Inherited from

[SubProcess](subprocess.md).[childProcess](subprocess.md#childprocess)

#### Defined in

[elements/Tasks.ts:207](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Tasks.ts#L207)

___

### def

• **def**: `any`

#### Inherited from

[SubProcess](subprocess.md).[def](subprocess.md#def)

#### Defined in

[elements/Node.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L14)

___

### id

• **id**: `any`

#### Inherited from

[SubProcess](subprocess.md).[id](subprocess.md#id)

#### Defined in

[elements/Element.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L13)

___

### inbounds

• **inbounds**: [`Flow`](flow.md)[]

#### Inherited from

[SubProcess](subprocess.md).[inbounds](subprocess.md#inbounds)

#### Defined in

[elements/Node.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L16)

___

### initiator

• **initiator**: `any`

#### Inherited from

[SubProcess](subprocess.md).[initiator](subprocess.md#initiator)

#### Defined in

[elements/Node.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L21)

___

### isFlow

• **isFlow**: `boolean` = `false`

#### Inherited from

[SubProcess](subprocess.md).[isFlow](subprocess.md#isflow)

#### Defined in

[elements/Element.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L18)

___

### lane

• **lane**: `any`

#### Inherited from

[SubProcess](subprocess.md).[lane](subprocess.md#lane)

#### Defined in

[elements/Element.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L19)

___

### messageId

• **messageId**: `any`

#### Inherited from

[SubProcess](subprocess.md).[messageId](subprocess.md#messageid)

#### Defined in

[elements/Node.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L19)

___

### name

• **name**: `any`

#### Inherited from

[SubProcess](subprocess.md).[name](subprocess.md#name)

#### Defined in

[elements/Node.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L12)

___

### outbounds

• **outbounds**: [`Flow`](flow.md)[]

#### Inherited from

[SubProcess](subprocess.md).[outbounds](subprocess.md#outbounds)

#### Defined in

[elements/Node.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L15)

___

### process

• **process**: `any`

#### Inherited from

[SubProcess](subprocess.md).[process](subprocess.md#process)

#### Defined in

[elements/Node.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L13)

___

### scripts

• **scripts**: `Map`\<`any`, `any`\>

#### Inherited from

[SubProcess](subprocess.md).[scripts](subprocess.md#scripts)

#### Defined in

[elements/Node.ts:23](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L23)

___

### signalId

• **signalId**: `any`

#### Inherited from

[SubProcess](subprocess.md).[signalId](subprocess.md#signalid)

#### Defined in

[elements/Node.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L20)

___

### subType

• **subType**: `any`

#### Inherited from

[SubProcess](subprocess.md).[subType](subprocess.md#subtype)

#### Defined in

[elements/Element.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L15)

___

### type

• **type**: `any`

#### Inherited from

[SubProcess](subprocess.md).[type](subprocess.md#type)

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

[SubProcess](subprocess.md).[addBehaviour](subprocess.md#addbehaviour)

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

[SubProcess](subprocess.md).[cancelBoundaryEvents](subprocess.md#cancelboundaryevents)

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

[SubProcess](subprocess.md).[cancelEBG](subprocess.md#cancelebg)

#### Defined in

[elements/Node.ts:227](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L227)

___

### continue

▸ **continue**(`item`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`Promise`\<`void`\>

#### Inherited from

[SubProcess](subprocess.md).[continue](subprocess.md#continue)

#### Defined in

[elements/Node.ts:208](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L208)

___

### describe

▸ **describe**(): `string`[][]

#### Returns

`string`[][]

#### Inherited from

[SubProcess](subprocess.md).[describe](subprocess.md#describe)

#### Defined in

[elements/Element.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L21)

___

### doEvent

▸ **doEvent**(`item`, `event`, `newStatus`): `Promise`\<`any`[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |
| `event` | [`EXECUTION_EVENT`](../enums/execution_event.md) |
| `newStatus` | [`ITEM_STATUS`](../enums/item_status.md) |

#### Returns

`Promise`\<`any`[]\>

#### Inherited from

[SubProcess](subprocess.md).[doEvent](subprocess.md#doevent)

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

[SubProcess](subprocess.md).[end](subprocess.md#end)

#### Defined in

[elements/Transaction.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Transaction.ts#L17)

___

### enter

▸ **enter**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`void`

#### Inherited from

[SubProcess](subprocess.md).[enter](subprocess.md#enter)

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
| `item` | [`Item`](item.md) |

#### Returns

`Promise`\<`void` \| [`wait`](../enums/node_action.md#wait) \| [`end`](../enums/node_action.md#end) \| [`error`](../enums/node_action.md#error) \| [`abort`](../enums/node_action.md#abort)\>

#### Inherited from

[SubProcess](subprocess.md).[execute](subprocess.md#execute)

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

[SubProcess](subprocess.md).[getBehaviour](subprocess.md#getbehaviour)

#### Defined in

[elements/Element.ts:36](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L36)

___

### getInput

▸ **getInput**(`item`, `input`): `Promise`\<{}\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |
| `input` | `any` |

#### Returns

`Promise`\<{}\>

#### Inherited from

[SubProcess](subprocess.md).[getInput](subprocess.md#getinput)

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

▸ **getNodes**(): [`Node`](node.md)[]

#### Returns

[`Node`](node.md)[]

#### Defined in

[elements/Transaction.ts:74](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Transaction.ts#L74)

___

### getOutbounds

▸ **getOutbounds**(`item`): [`Item`](item.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

[`Item`](item.md)[]

#### Inherited from

[SubProcess](subprocess.md).[getOutbounds](subprocess.md#getoutbounds)

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
| `item` | [`Item`](item.md) |

#### Returns

`Promise`\<{}\>

#### Inherited from

[SubProcess](subprocess.md).[getOutput](subprocess.md#getoutput)

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

[SubProcess](subprocess.md).[hasBehaviour](subprocess.md#hasbehaviour)

#### Defined in

[elements/Element.ts:32](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L32)

___

### init

▸ **init**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`void`

#### Inherited from

[SubProcess](subprocess.md).[init](subprocess.md#init)

#### Defined in

[elements/Node.ts:306](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L306)

___

### restored

▸ **restored**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`void`

#### Inherited from

[SubProcess](subprocess.md).[restored](subprocess.md#restored)

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
| `item` | [`Item`](item.md) |

#### Returns

`void`

#### Inherited from

[SubProcess](subprocess.md).[resume](subprocess.md#resume)

#### Defined in

[elements/Node.ts:303](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L303)

___

### run

▸ **run**(`item`): `Promise`\<[`NODE_ACTION`](../enums/node_action.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`Promise`\<[`NODE_ACTION`](../enums/node_action.md)\>

#### Inherited from

[SubProcess](subprocess.md).[run](subprocess.md#run)

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
| `item` | [`Item`](item.md) |
| `input` | `any` |

#### Returns

`Promise`\<`void`\>

#### Inherited from

[SubProcess](subprocess.md).[setInput](subprocess.md#setinput)

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

[SubProcess](subprocess.md).[start](subprocess.md#start)

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

[SubProcess](subprocess.md).[startBoundaryEvents](subprocess.md#startboundaryevents)

#### Defined in

[elements/Node.ts:330](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L330)

___

### validate

▸ **validate**(`item`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`Promise`\<`void`\>

#### Inherited from

[SubProcess](subprocess.md).[validate](subprocess.md#validate)

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
