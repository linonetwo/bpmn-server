[bpmn-server](../README.md) / BusinessRuleTask

# Class: BusinessRuleTask

foo[method]();
     
     await this.token.appDelegate[serviceName](data);
     
     
     service signature:
             output= service (input,context)

## Hierarchy

- [`ServiceTask`](servicetask.md)

  ↳ **`BusinessRuleTask`**

## Table of contents

### Constructors

- [constructor](businessruletask.md#constructor)

### Properties

- [assignee](businessruletask.md#assignee)
- [attachedTo](businessruletask.md#attachedto)
- [attachments](businessruletask.md#attachments)
- [behaviours](businessruletask.md#behaviours)
- [def](businessruletask.md#def)
- [id](businessruletask.md#id)
- [inbounds](businessruletask.md#inbounds)
- [initiator](businessruletask.md#initiator)
- [isFlow](businessruletask.md#isflow)
- [lane](businessruletask.md#lane)
- [messageId](businessruletask.md#messageid)
- [name](businessruletask.md#name)
- [outbounds](businessruletask.md#outbounds)
- [process](businessruletask.md#process)
- [scripts](businessruletask.md#scripts)
- [signalId](businessruletask.md#signalid)
- [subType](businessruletask.md#subtype)
- [type](businessruletask.md#type)

### Accessors

- [canBeInvoked](businessruletask.md#canbeinvoked)
- [isCatching](businessruletask.md#iscatching)
- [processId](businessruletask.md#processid)
- [requiresWait](businessruletask.md#requireswait)
- [serviceName](businessruletask.md#servicename)

### Methods

- [addBehaviour](businessruletask.md#addbehaviour)
- [cancelBoundaryEvents](businessruletask.md#cancelboundaryevents)
- [cancelEBG](businessruletask.md#cancelebg)
- [continue](businessruletask.md#continue)
- [describe](businessruletask.md#describe)
- [doEvent](businessruletask.md#doevent)
- [end](businessruletask.md#end)
- [enter](businessruletask.md#enter)
- [execute](businessruletask.md#execute)
- [getBehaviour](businessruletask.md#getbehaviour)
- [getInput](businessruletask.md#getinput)
- [getOutbounds](businessruletask.md#getoutbounds)
- [getOutput](businessruletask.md#getoutput)
- [hasBehaviour](businessruletask.md#hasbehaviour)
- [init](businessruletask.md#init)
- [restored](businessruletask.md#restored)
- [resume](businessruletask.md#resume)
- [run](businessruletask.md#run)
- [setInput](businessruletask.md#setinput)
- [start](businessruletask.md#start)
- [startBoundaryEvents](businessruletask.md#startboundaryevents)
- [validate](businessruletask.md#validate)

## Constructors

### constructor

• **new BusinessRuleTask**(`id`, `process`, `type`, `def`): [`BusinessRuleTask`](businessruletask.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `any` |
| `process` | `any` |
| `type` | `any` |
| `def` | `any` |

#### Returns

[`BusinessRuleTask`](businessruletask.md)

#### Inherited from

[ServiceTask](servicetask.md).[constructor](servicetask.md#constructor)

#### Defined in

[elements/Node.ts:29](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L29)

## Properties

### assignee

• **assignee**: `any`

#### Inherited from

[ServiceTask](servicetask.md).[assignee](servicetask.md#assignee)

#### Defined in

[elements/Node.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L22)

___

### attachedTo

• **attachedTo**: [`Node`](node.md)

#### Inherited from

[ServiceTask](servicetask.md).[attachedTo](servicetask.md#attachedto)

#### Defined in

[elements/Node.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L18)

___

### attachments

• **attachments**: [`Node`](node.md)[]

#### Inherited from

[ServiceTask](servicetask.md).[attachments](servicetask.md#attachments)

#### Defined in

[elements/Node.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L17)

___

### behaviours

• **behaviours**: `Map`\<`any`, `any`\>

#### Inherited from

[ServiceTask](servicetask.md).[behaviours](servicetask.md#behaviours)

#### Defined in

[elements/Element.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L17)

___

### def

• **def**: `any`

#### Inherited from

[ServiceTask](servicetask.md).[def](servicetask.md#def)

#### Defined in

[elements/Node.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L14)

___

### id

• **id**: `any`

#### Inherited from

[ServiceTask](servicetask.md).[id](servicetask.md#id)

#### Defined in

[elements/Element.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L13)

___

### inbounds

• **inbounds**: [`Flow`](flow.md)[]

#### Inherited from

[ServiceTask](servicetask.md).[inbounds](servicetask.md#inbounds)

#### Defined in

[elements/Node.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L16)

___

### initiator

• **initiator**: `any`

#### Inherited from

[ServiceTask](servicetask.md).[initiator](servicetask.md#initiator)

#### Defined in

[elements/Node.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L21)

___

### isFlow

• **isFlow**: `boolean` = `false`

#### Inherited from

[ServiceTask](servicetask.md).[isFlow](servicetask.md#isflow)

#### Defined in

[elements/Element.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L18)

___

### lane

• **lane**: `any`

#### Inherited from

[ServiceTask](servicetask.md).[lane](servicetask.md#lane)

#### Defined in

[elements/Element.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L19)

___

### messageId

• **messageId**: `any`

#### Inherited from

[ServiceTask](servicetask.md).[messageId](servicetask.md#messageid)

#### Defined in

[elements/Node.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L19)

___

### name

• **name**: `any`

#### Inherited from

[ServiceTask](servicetask.md).[name](servicetask.md#name)

#### Defined in

[elements/Node.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L12)

___

### outbounds

• **outbounds**: [`Flow`](flow.md)[]

#### Inherited from

[ServiceTask](servicetask.md).[outbounds](servicetask.md#outbounds)

#### Defined in

[elements/Node.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L15)

___

### process

• **process**: `any`

#### Inherited from

[ServiceTask](servicetask.md).[process](servicetask.md#process)

#### Defined in

[elements/Node.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L13)

___

### scripts

• **scripts**: `Map`\<`any`, `any`\>

#### Inherited from

[ServiceTask](servicetask.md).[scripts](servicetask.md#scripts)

#### Defined in

[elements/Node.ts:23](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L23)

___

### signalId

• **signalId**: `any`

#### Inherited from

[ServiceTask](servicetask.md).[signalId](servicetask.md#signalid)

#### Defined in

[elements/Node.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L20)

___

### subType

• **subType**: `any`

#### Inherited from

[ServiceTask](servicetask.md).[subType](servicetask.md#subtype)

#### Defined in

[elements/Element.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L15)

___

### type

• **type**: `any`

#### Inherited from

[ServiceTask](servicetask.md).[type](servicetask.md#type)

#### Defined in

[elements/Element.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L14)

## Accessors

### canBeInvoked

• `get` **canBeInvoked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

ServiceTask.canBeInvoked

#### Defined in

[elements/Node.ts:123](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L123)

___

### isCatching

• `get` **isCatching**(): `boolean`

#### Returns

`boolean`

#### Inherited from

ServiceTask.isCatching

#### Defined in

[elements/Node.ts:125](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L125)

___

### processId

• `get` **processId**(): `any`

#### Returns

`any`

#### Inherited from

ServiceTask.processId

#### Defined in

[elements/Node.ts:24](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L24)

___

### requiresWait

• `get` **requiresWait**(): `boolean`

#### Returns

`boolean`

#### Inherited from

ServiceTask.requiresWait

#### Defined in

[elements/Node.ts:118](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L118)

___

### serviceName

• `get` **serviceName**(): `any`

#### Returns

`any`

#### Inherited from

ServiceTask.serviceName

#### Defined in

[elements/Tasks.ts:41](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Tasks.ts#L41)

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

[ServiceTask](servicetask.md).[addBehaviour](servicetask.md#addbehaviour)

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

[ServiceTask](servicetask.md).[cancelBoundaryEvents](servicetask.md#cancelboundaryevents)

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

[ServiceTask](servicetask.md).[cancelEBG](servicetask.md#cancelebg)

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

[ServiceTask](servicetask.md).[continue](servicetask.md#continue)

#### Defined in

[elements/Node.ts:208](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L208)

___

### describe

▸ **describe**(): `string`[][]

#### Returns

`string`[][]

#### Inherited from

[ServiceTask](servicetask.md).[describe](servicetask.md#describe)

#### Defined in

[elements/Tasks.ts:95](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Tasks.ts#L95)

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

[ServiceTask](servicetask.md).[doEvent](servicetask.md#doevent)

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

#### Inherited from

[ServiceTask](servicetask.md).[end](servicetask.md#end)

#### Defined in

[elements/Node.ts:268](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L268)

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

[ServiceTask](servicetask.md).[enter](servicetask.md#enter)

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

[ServiceTask](servicetask.md).[execute](servicetask.md#execute)

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

[ServiceTask](servicetask.md).[getBehaviour](servicetask.md#getbehaviour)

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

[ServiceTask](servicetask.md).[getInput](servicetask.md#getinput)

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

[ServiceTask](servicetask.md).[getOutbounds](servicetask.md#getoutbounds)

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

[ServiceTask](servicetask.md).[getOutput](servicetask.md#getoutput)

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

[ServiceTask](servicetask.md).[hasBehaviour](servicetask.md#hasbehaviour)

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

[ServiceTask](servicetask.md).[init](servicetask.md#init)

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

[ServiceTask](servicetask.md).[restored](servicetask.md#restored)

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

[ServiceTask](servicetask.md).[resume](servicetask.md#resume)

#### Defined in

[elements/Node.ts:303](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L303)

___

### run

▸ **run**(`item`): `Promise`\<[`NODE_ACTION`](../enums/node_action.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |

#### Returns

`Promise`\<[`NODE_ACTION`](../enums/node_action.md)\>

#### Overrides

[ServiceTask](servicetask.md).[run](servicetask.md#run)

#### Defined in

[elements/Tasks.ts:104](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Tasks.ts#L104)

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

[ServiceTask](servicetask.md).[setInput](servicetask.md#setinput)

#### Defined in

[elements/Node.ts:81](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L81)

___

### start

▸ **start**(`item`): `Promise`\<[`NODE_ACTION`](../enums/node_action.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`Promise`\<[`NODE_ACTION`](../enums/node_action.md)\>

#### Inherited from

[ServiceTask](servicetask.md).[start](servicetask.md#start)

#### Defined in

[elements/Node.ts:213](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L213)

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

[ServiceTask](servicetask.md).[startBoundaryEvents](servicetask.md#startboundaryevents)

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

[ServiceTask](servicetask.md).[validate](servicetask.md#validate)

#### Defined in

[elements/Node.ts:42](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L42)
