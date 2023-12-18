[bpmn-server](../README.md) / XORGateway

# Class: XORGateway

ExclusiveGatway:
     outbounds:  only 1 
     inbound:    only 1 -

## Hierarchy

- [`Gateway`](gateway.md)

  ↳ **`XORGateway`**

## Table of contents

### Constructors

- [constructor](xorgateway.md#constructor)

### Properties

- [assignee](xorgateway.md#assignee)
- [attachedTo](xorgateway.md#attachedto)
- [attachments](xorgateway.md#attachments)
- [behaviours](xorgateway.md#behaviours)
- [def](xorgateway.md#def)
- [id](xorgateway.md#id)
- [inbounds](xorgateway.md#inbounds)
- [initiator](xorgateway.md#initiator)
- [isFlow](xorgateway.md#isflow)
- [lane](xorgateway.md#lane)
- [messageId](xorgateway.md#messageid)
- [name](xorgateway.md#name)
- [outbounds](xorgateway.md#outbounds)
- [process](xorgateway.md#process)
- [scripts](xorgateway.md#scripts)
- [signalId](xorgateway.md#signalid)
- [subType](xorgateway.md#subtype)
- [type](xorgateway.md#type)

### Accessors

- [canBeInvoked](xorgateway.md#canbeinvoked)
- [isCatching](xorgateway.md#iscatching)
- [processId](xorgateway.md#processid)
- [requiresWait](xorgateway.md#requireswait)

### Methods

- [addBehaviour](xorgateway.md#addbehaviour)
- [analyzeConvergingTokens](xorgateway.md#analyzeconvergingtokens)
- [canReach](xorgateway.md#canreach)
- [cancelBoundaryEvents](xorgateway.md#cancelboundaryevents)
- [cancelEBG](xorgateway.md#cancelebg)
- [continue](xorgateway.md#continue)
- [describe](xorgateway.md#describe)
- [doEvent](xorgateway.md#doevent)
- [end](xorgateway.md#end)
- [enter](xorgateway.md#enter)
- [execute](xorgateway.md#execute)
- [getBehaviour](xorgateway.md#getbehaviour)
- [getInput](xorgateway.md#getinput)
- [getOutbounds](xorgateway.md#getoutbounds)
- [getOutput](xorgateway.md#getoutput)
- [getPotentialPath](xorgateway.md#getpotentialpath)
- [getRelatedTokens](xorgateway.md#getrelatedtokens)
- [hasBehaviour](xorgateway.md#hasbehaviour)
- [init](xorgateway.md#init)
- [restored](xorgateway.md#restored)
- [resume](xorgateway.md#resume)
- [run](xorgateway.md#run)
- [setInput](xorgateway.md#setinput)
- [start](xorgateway.md#start)
- [startBoundaryEvents](xorgateway.md#startboundaryevents)
- [validate](xorgateway.md#validate)

## Constructors

### constructor

• **new XORGateway**(`id`, `process`, `type`, `def`): [`XORGateway`](xorgateway.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `any` |
| `process` | `any` |
| `type` | `any` |
| `def` | `any` |

#### Returns

[`XORGateway`](xorgateway.md)

#### Inherited from

[Gateway](gateway.md).[constructor](gateway.md#constructor)

#### Defined in

[elements/Node.ts:29](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L29)

## Properties

### assignee

• **assignee**: `any`

#### Inherited from

[Gateway](gateway.md).[assignee](gateway.md#assignee)

#### Defined in

[elements/Node.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L22)

___

### attachedTo

• **attachedTo**: [`Node`](node.md)

#### Inherited from

[Gateway](gateway.md).[attachedTo](gateway.md#attachedto)

#### Defined in

[elements/Node.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L18)

___

### attachments

• **attachments**: [`Node`](node.md)[]

#### Inherited from

[Gateway](gateway.md).[attachments](gateway.md#attachments)

#### Defined in

[elements/Node.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L17)

___

### behaviours

• **behaviours**: `Map`\<`any`, `any`\>

#### Inherited from

[Gateway](gateway.md).[behaviours](gateway.md#behaviours)

#### Defined in

[elements/Element.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L17)

___

### def

• **def**: `any`

#### Inherited from

[Gateway](gateway.md).[def](gateway.md#def)

#### Defined in

[elements/Node.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L14)

___

### id

• **id**: `any`

#### Inherited from

[Gateway](gateway.md).[id](gateway.md#id)

#### Defined in

[elements/Element.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L13)

___

### inbounds

• **inbounds**: [`Flow`](flow.md)[]

#### Inherited from

[Gateway](gateway.md).[inbounds](gateway.md#inbounds)

#### Defined in

[elements/Node.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L16)

___

### initiator

• **initiator**: `any`

#### Inherited from

[Gateway](gateway.md).[initiator](gateway.md#initiator)

#### Defined in

[elements/Node.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L21)

___

### isFlow

• **isFlow**: `boolean` = `false`

#### Inherited from

[Gateway](gateway.md).[isFlow](gateway.md#isflow)

#### Defined in

[elements/Element.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L18)

___

### lane

• **lane**: `any`

#### Inherited from

[Gateway](gateway.md).[lane](gateway.md#lane)

#### Defined in

[elements/Element.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L19)

___

### messageId

• **messageId**: `any`

#### Inherited from

[Gateway](gateway.md).[messageId](gateway.md#messageid)

#### Defined in

[elements/Node.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L19)

___

### name

• **name**: `any`

#### Inherited from

[Gateway](gateway.md).[name](gateway.md#name)

#### Defined in

[elements/Node.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L12)

___

### outbounds

• **outbounds**: [`Flow`](flow.md)[]

#### Inherited from

[Gateway](gateway.md).[outbounds](gateway.md#outbounds)

#### Defined in

[elements/Node.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L15)

___

### process

• **process**: `any`

#### Inherited from

[Gateway](gateway.md).[process](gateway.md#process)

#### Defined in

[elements/Node.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L13)

___

### scripts

• **scripts**: `Map`\<`any`, `any`\>

#### Inherited from

[Gateway](gateway.md).[scripts](gateway.md#scripts)

#### Defined in

[elements/Node.ts:23](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L23)

___

### signalId

• **signalId**: `any`

#### Inherited from

[Gateway](gateway.md).[signalId](gateway.md#signalid)

#### Defined in

[elements/Node.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L20)

___

### subType

• **subType**: `any`

#### Inherited from

[Gateway](gateway.md).[subType](gateway.md#subtype)

#### Defined in

[elements/Element.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L15)

___

### type

• **type**: `any`

#### Inherited from

[Gateway](gateway.md).[type](gateway.md#type)

#### Defined in

[elements/Element.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L14)

## Accessors

### canBeInvoked

• `get` **canBeInvoked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

Gateway.canBeInvoked

#### Defined in

[elements/Node.ts:123](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L123)

___

### isCatching

• `get` **isCatching**(): `boolean`

#### Returns

`boolean`

#### Inherited from

Gateway.isCatching

#### Defined in

[elements/Node.ts:125](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L125)

___

### processId

• `get` **processId**(): `any`

#### Returns

`any`

#### Inherited from

Gateway.processId

#### Defined in

[elements/Node.ts:24](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L24)

___

### requiresWait

• `get` **requiresWait**(): `boolean`

#### Returns

`boolean`

#### Inherited from

Gateway.requiresWait

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

[Gateway](gateway.md).[addBehaviour](gateway.md#addbehaviour)

#### Defined in

[elements/Element.ts:39](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L39)

___

### analyzeConvergingTokens

▸ **analyzeConvergingTokens**(`item`): `Object`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `pendingTokens` | [`Token`](token.md)[] |
| `waitingTokens` | [`Token`](token.md)[] |

#### Inherited from

[Gateway](gateway.md).[analyzeConvergingTokens](gateway.md#analyzeconvergingtokens)

#### Defined in

[elements/Gateway.ts:120](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Gateway.ts#L120)

___

### canReach

▸ **canReach**(`node`, `target`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | `any` |
| `target` | `any` |

#### Returns

`any`

#### Inherited from

[Gateway](gateway.md).[canReach](gateway.md#canreach)

#### Defined in

[elements/Gateway.ts:78](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Gateway.ts#L78)

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

[Gateway](gateway.md).[cancelBoundaryEvents](gateway.md#cancelboundaryevents)

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

[Gateway](gateway.md).[cancelEBG](gateway.md#cancelebg)

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

[Gateway](gateway.md).[continue](gateway.md#continue)

#### Defined in

[elements/Node.ts:208](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L208)

___

### describe

▸ **describe**(): `string`[][]

#### Returns

`string`[][]

#### Inherited from

[Gateway](gateway.md).[describe](gateway.md#describe)

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

[Gateway](gateway.md).[doEvent](gateway.md#doevent)

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

[Gateway](gateway.md).[end](gateway.md#end)

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

[Gateway](gateway.md).[enter](gateway.md#enter)

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

[Gateway](gateway.md).[execute](gateway.md#execute)

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

[Gateway](gateway.md).[getBehaviour](gateway.md#getbehaviour)

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

[Gateway](gateway.md).[getInput](gateway.md#getinput)

#### Defined in

[elements/Node.ts:91](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L91)

___

### getOutbounds

▸ **getOutbounds**(`item`): [`Item`](item.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |

#### Returns

[`Item`](item.md)[]

#### Overrides

[Gateway](gateway.md).[getOutbounds](gateway.md#getoutbounds)

#### Defined in

[elements/Gateway.ts:245](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Gateway.ts#L245)

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

[Gateway](gateway.md).[getOutput](gateway.md#getoutput)

#### Defined in

[elements/Node.ts:105](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L105)

___

### getPotentialPath

▸ **getPotentialPath**(`node`, `path?`): `any`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `node` | `any` | `undefined` |
| `path` | `any` | `null` |

#### Returns

`any`

#### Inherited from

[Gateway](gateway.md).[getPotentialPath](gateway.md#getpotentialpath)

#### Defined in

[elements/Gateway.ts:64](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Gateway.ts#L64)

___

### getRelatedTokens

▸ **getRelatedTokens**(`item`): `any`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`any`[]

#### Inherited from

[Gateway](gateway.md).[getRelatedTokens](gateway.md#getrelatedtokens)

#### Defined in

[elements/Gateway.ts:88](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Gateway.ts#L88)

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

[Gateway](gateway.md).[hasBehaviour](gateway.md#hasbehaviour)

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

[Gateway](gateway.md).[init](gateway.md#init)

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

[Gateway](gateway.md).[restored](gateway.md#restored)

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

[Gateway](gateway.md).[resume](gateway.md#resume)

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

[Gateway](gateway.md).[run](gateway.md#run)

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

[Gateway](gateway.md).[setInput](gateway.md#setinput)

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

[Gateway](gateway.md).[start](gateway.md#start)

#### Defined in

[elements/Gateway.ts:149](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Gateway.ts#L149)

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

[Gateway](gateway.md).[startBoundaryEvents](gateway.md#startboundaryevents)

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

[Gateway](gateway.md).[validate](gateway.md#validate)

#### Defined in

[elements/Node.ts:42](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Node.ts#L42)
