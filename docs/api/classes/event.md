[bpmn-server](../README.md) / Event

# Class: Event

## Hierarchy

- [`Node`](node.md)

  ↳ **`Event`**

  ↳↳ [`StartEvent`](startevent.md)

  ↳↳ [`EndEvent`](endevent.md)

  ↳↳ [`CatchEvent`](catchevent.md)

  ↳↳ [`ThrowEvent`](throwevent.md)

  ↳↳ [`BoundaryEvent`](boundaryevent.md)

## Table of contents

### Constructors

- [constructor](event.md#constructor)

### Properties

- [assignee](event.md#assignee)
- [attachedTo](event.md#attachedto)
- [attachments](event.md#attachments)
- [behaviours](event.md#behaviours)
- [def](event.md#def)
- [id](event.md#id)
- [inbounds](event.md#inbounds)
- [initiator](event.md#initiator)
- [isFlow](event.md#isflow)
- [lane](event.md#lane)
- [messageId](event.md#messageid)
- [name](event.md#name)
- [outbounds](event.md#outbounds)
- [process](event.md#process)
- [scripts](event.md#scripts)
- [signalId](event.md#signalid)
- [subType](event.md#subtype)
- [type](event.md#type)

### Accessors

- [canBeInvoked](event.md#canbeinvoked)
- [isCatching](event.md#iscatching)
- [processId](event.md#processid)
- [requiresWait](event.md#requireswait)

### Methods

- [addBehaviour](event.md#addbehaviour)
- [cancelBoundaryEvents](event.md#cancelboundaryevents)
- [cancelEBG](event.md#cancelebg)
- [continue](event.md#continue)
- [describe](event.md#describe)
- [doEvent](event.md#doevent)
- [end](event.md#end)
- [enter](event.md#enter)
- [execute](event.md#execute)
- [getBehaviour](event.md#getbehaviour)
- [getInput](event.md#getinput)
- [getOutbounds](event.md#getoutbounds)
- [getOutput](event.md#getoutput)
- [hasBehaviour](event.md#hasbehaviour)
- [hasMessage](event.md#hasmessage)
- [hasSignal](event.md#hassignal)
- [hasTimer](event.md#hastimer)
- [init](event.md#init)
- [restored](event.md#restored)
- [resume](event.md#resume)
- [run](event.md#run)
- [setInput](event.md#setinput)
- [start](event.md#start)
- [startBoundaryEvents](event.md#startboundaryevents)
- [validate](event.md#validate)

## Constructors

### constructor

• **new Event**(`id`, `process`, `type`, `def`): [`Event`](event.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `any` |
| `process` | `any` |
| `type` | `any` |
| `def` | `any` |

#### Returns

[`Event`](event.md)

#### Inherited from

[Node](node.md).[constructor](node.md#constructor)

#### Defined in

[elements/Node.ts:29](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L29)

## Properties

### assignee

• **assignee**: `any`

#### Inherited from

[Node](node.md).[assignee](node.md#assignee)

#### Defined in

[elements/Node.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L22)

___

### attachedTo

• **attachedTo**: [`Node`](node.md)

#### Inherited from

[Node](node.md).[attachedTo](node.md#attachedto)

#### Defined in

[elements/Node.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L18)

___

### attachments

• **attachments**: [`Node`](node.md)[]

#### Inherited from

[Node](node.md).[attachments](node.md#attachments)

#### Defined in

[elements/Node.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L17)

___

### behaviours

• **behaviours**: `Map`\<`any`, `any`\>

#### Inherited from

[Node](node.md).[behaviours](node.md#behaviours)

#### Defined in

[elements/Element.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L17)

___

### def

• **def**: `any`

#### Inherited from

[Node](node.md).[def](node.md#def)

#### Defined in

[elements/Node.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L14)

___

### id

• **id**: `any`

#### Inherited from

[Node](node.md).[id](node.md#id)

#### Defined in

[elements/Element.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L13)

___

### inbounds

• **inbounds**: [`Flow`](flow.md)[]

#### Inherited from

[Node](node.md).[inbounds](node.md#inbounds)

#### Defined in

[elements/Node.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L16)

___

### initiator

• **initiator**: `any`

#### Inherited from

[Node](node.md).[initiator](node.md#initiator)

#### Defined in

[elements/Node.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L21)

___

### isFlow

• **isFlow**: `boolean` = `false`

#### Inherited from

[Node](node.md).[isFlow](node.md#isflow)

#### Defined in

[elements/Element.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L18)

___

### lane

• **lane**: `any`

#### Inherited from

[Node](node.md).[lane](node.md#lane)

#### Defined in

[elements/Element.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L19)

___

### messageId

• **messageId**: `any`

#### Inherited from

[Node](node.md).[messageId](node.md#messageid)

#### Defined in

[elements/Node.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L19)

___

### name

• **name**: `any`

#### Inherited from

[Node](node.md).[name](node.md#name)

#### Defined in

[elements/Node.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L12)

___

### outbounds

• **outbounds**: [`Flow`](flow.md)[]

#### Inherited from

[Node](node.md).[outbounds](node.md#outbounds)

#### Defined in

[elements/Node.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L15)

___

### process

• **process**: `any`

#### Inherited from

[Node](node.md).[process](node.md#process)

#### Defined in

[elements/Node.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L13)

___

### scripts

• **scripts**: `Map`\<`any`, `any`\>

#### Inherited from

[Node](node.md).[scripts](node.md#scripts)

#### Defined in

[elements/Node.ts:23](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L23)

___

### signalId

• **signalId**: `any`

#### Inherited from

[Node](node.md).[signalId](node.md#signalid)

#### Defined in

[elements/Node.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L20)

___

### subType

• **subType**: `any`

#### Inherited from

[Node](node.md).[subType](node.md#subtype)

#### Defined in

[elements/Element.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L15)

___

### type

• **type**: `any`

#### Inherited from

[Node](node.md).[type](node.md#type)

#### Defined in

[elements/Element.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L14)

## Accessors

### canBeInvoked

• `get` **canBeInvoked**(): `boolean`

#### Returns

`boolean`

#### Overrides

Node.canBeInvoked

#### Defined in

[elements/Events.ts:32](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Events.ts#L32)

___

### isCatching

• `get` **isCatching**(): `boolean`

#### Returns

`boolean`

#### Inherited from

Node.isCatching

#### Defined in

[elements/Node.ts:125](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L125)

___

### processId

• `get` **processId**(): `any`

#### Returns

`any`

#### Inherited from

Node.processId

#### Defined in

[elements/Node.ts:24](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L24)

___

### requiresWait

• `get` **requiresWait**(): `boolean`

#### Returns

`boolean`

#### Inherited from

Node.requiresWait

#### Defined in

[elements/Node.ts:118](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L118)

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

[Node](node.md).[addBehaviour](node.md#addbehaviour)

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

[Node](node.md).[cancelBoundaryEvents](node.md#cancelboundaryevents)

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

[Node](node.md).[cancelEBG](node.md#cancelebg)

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

[Node](node.md).[continue](node.md#continue)

#### Defined in

[elements/Node.ts:208](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L208)

___

### describe

▸ **describe**(): `string`[][]

#### Returns

`string`[][]

#### Inherited from

[Node](node.md).[describe](node.md#describe)

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

[Node](node.md).[doEvent](node.md#doevent)

#### Defined in

[elements/Node.ts:53](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L53)

___

### end

▸ **end**(`item`, `cancel?`): `Promise`\<`void`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `item` | [`Item`](item.md) | `undefined` |
| `cancel` | `Boolean` | `false` |

#### Returns

`Promise`\<`void`\>

#### Overrides

[Node](node.md).[end](node.md#end)

#### Defined in

[elements/Events.ts:28](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Events.ts#L28)

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

[Node](node.md).[enter](node.md#enter)

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

[Node](node.md).[execute](node.md#execute)

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

[Node](node.md).[getBehaviour](node.md#getbehaviour)

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

[Node](node.md).[getInput](node.md#getinput)

#### Defined in

[elements/Node.ts:91](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L91)

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

[Node](node.md).[getOutbounds](node.md#getoutbounds)

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

[Node](node.md).[getOutput](node.md#getoutput)

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

[Node](node.md).[hasBehaviour](node.md#hasbehaviour)

#### Defined in

[elements/Element.ts:32](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L32)

___

### hasMessage

▸ **hasMessage**(): `any`

#### Returns

`any`

#### Defined in

[elements/Events.ts:9](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Events.ts#L9)

___

### hasSignal

▸ **hasSignal**(): `any`

#### Returns

`any`

#### Defined in

[elements/Events.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Events.ts#L12)

___

### hasTimer

▸ **hasTimer**(): `any`

#### Returns

`any`

#### Defined in

[elements/Events.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Events.ts#L15)

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

[Node](node.md).[init](node.md#init)

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

[Node](node.md).[restored](node.md#restored)

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

[Node](node.md).[resume](node.md#resume)

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

[Node](node.md).[run](node.md#run)

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

[Node](node.md).[setInput](node.md#setinput)

#### Defined in

[elements/Node.ts:81](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L81)

___

### start

▸ **start**(`item`): `Promise`\<[`NODE_ACTION`](../enums/node_action.md)\>

using token: check if fromEventBasedGateway;	if yes cancel all other events

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`Promise`\<[`NODE_ACTION`](../enums/node_action.md)\>

#### Overrides

[Node](node.md).[start](node.md#start)

#### Defined in

[elements/Events.ts:24](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Events.ts#L24)

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

[Node](node.md).[startBoundaryEvents](node.md#startboundaryevents)

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

[Node](node.md).[validate](node.md#validate)

#### Defined in

[elements/Node.ts:42](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L42)
