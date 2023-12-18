[bpmn-server](../README.md) / INode

# Interface: INode

## Hierarchy

- [`IElement`](IElement.md)

  ↳ **`INode`**

## Table of contents

### Properties

- [behaviours](INode.md#behaviours)
- [def](INode.md#def)
- [id](INode.md#id)
- [inbounds](INode.md#inbounds)
- [lane](INode.md#lane)
- [name](INode.md#name)
- [outbounds](INode.md#outbounds)
- [processId](INode.md#processid)
- [type](INode.md#type)

### Methods

- [addBehaviour](INode.md#addbehaviour)
- [canBeInvoked](INode.md#canbeinvoked)
- [continue](INode.md#continue)
- [describe](INode.md#describe)
- [doEvent](INode.md#doevent)
- [end](INode.md#end)
- [enter](INode.md#enter)
- [execute](INode.md#execute)
- [getBehaviour](INode.md#getbehaviour)
- [getOutbounds](INode.md#getoutbounds)
- [hasBehaviour](INode.md#hasbehaviour)
- [init](INode.md#init)
- [requiresWait](INode.md#requireswait)
- [restored](INode.md#restored)
- [resume](INode.md#resume)
- [run](INode.md#run)
- [start](INode.md#start)

## Properties

### behaviours

• **behaviours**: `Map`\<`any`, `any`\>

#### Inherited from

[IElement](IElement.md).[behaviours](IElement.md#behaviours)

#### Defined in

[interfaces/elements.ts:25](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L25)

___

### def

• **def**: `any`

#### Defined in

[interfaces/elements.ts:44](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L44)

___

### id

• **id**: `any`

#### Inherited from

[IElement](IElement.md).[id](IElement.md#id)

#### Defined in

[interfaces/elements.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L21)

___

### inbounds

• **inbounds**: `any`[]

#### Defined in

[interfaces/elements.ts:46](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L46)

___

### lane

• **lane**: `any`

#### Inherited from

[IElement](IElement.md).[lane](IElement.md#lane)

#### Defined in

[interfaces/elements.ts:24](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L24)

___

### name

• **name**: `any`

#### Overrides

[IElement](IElement.md).[name](IElement.md#name)

#### Defined in

[interfaces/elements.ts:42](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L42)

___

### outbounds

• **outbounds**: `any`[]

#### Defined in

[interfaces/elements.ts:45](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L45)

___

### processId

• **processId**: `any`

#### Defined in

[interfaces/elements.ts:43](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L43)

___

### type

• **type**: `any`

#### Inherited from

[IElement](IElement.md).[type](IElement.md#type)

#### Defined in

[interfaces/elements.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L22)

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

[IElement](IElement.md).[addBehaviour](IElement.md#addbehaviour)

#### Defined in

[interfaces/elements.ts:36](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L36)

___

### canBeInvoked

▸ **canBeInvoked**(): `boolean`

#### Returns

`boolean`

#### Defined in

[interfaces/elements.ts:50](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L50)

___

### continue

▸ **continue**(`item`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`IItem`](IItem.md) |

#### Returns

`Promise`\<`void`\>

#### Overrides

[IElement](IElement.md).[continue](IElement.md#continue)

#### Defined in

[interfaces/elements.ts:61](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L61)

___

### describe

▸ **describe**(): `string`[][]

#### Returns

`string`[][]

#### Inherited from

[IElement](IElement.md).[describe](IElement.md#describe)

#### Defined in

[interfaces/elements.ts:27](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L27)

___

### doEvent

▸ **doEvent**(`item`, `event`, `newStatus`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`IItem`](IItem.md) |
| `event` | [`EXECUTION_EVENT`](../enums/execution_event.md) |
| `newStatus` | [`ITEM_STATUS`](../enums/item_status.md) |

#### Returns

`Promise`\<`void`\>

#### Defined in

[interfaces/elements.ts:47](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L47)

___

### end

▸ **end**(`item`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`IItem`](IItem.md) |

#### Returns

`Promise`\<`void`\>

#### Defined in

[interfaces/elements.ts:64](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L64)

___

### enter

▸ **enter**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`IItem`](IItem.md) |

#### Returns

`void`

#### Defined in

[interfaces/elements.ts:48](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L48)

___

### execute

▸ **execute**(`item`): `Promise`\<`void` \| [`wait`](../enums/node_action.md#wait) \| [`error`](../enums/node_action.md#error) \| [`abort`](../enums/node_action.md#abort)\>

this is the primary exectuion method for a node

considerations: the following are handled by Token
     1.  Loops we are inside a loop already (if any)
     2.  Gatways
     3.  Subprocess the parent node is fired as normal
             run method will fire the subprocess invoking a new token and will go into wait

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`IItem`](IItem.md) |

#### Returns

`Promise`\<`void` \| [`wait`](../enums/node_action.md#wait) \| [`error`](../enums/node_action.md#error) \| [`abort`](../enums/node_action.md#abort)\>

#### Defined in

[interfaces/elements.ts:60](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L60)

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

[IElement](IElement.md).[getBehaviour](IElement.md#getbehaviour)

#### Defined in

[interfaces/elements.ts:35](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L35)

___

### getOutbounds

▸ **getOutbounds**(`item`): [`IItem`](IItem.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`IItem`](IItem.md) |

#### Returns

[`IItem`](IItem.md)[]

#### Defined in

[interfaces/elements.ts:72](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L72)

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

[IElement](IElement.md).[hasBehaviour](IElement.md#hasbehaviour)

#### Defined in

[interfaces/elements.ts:34](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L34)

___

### init

▸ **init**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`IItem`](IItem.md) |

#### Returns

`void`

#### Defined in

[interfaces/elements.ts:71](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L71)

___

### requiresWait

▸ **requiresWait**(): `boolean`

#### Returns

`boolean`

#### Defined in

[interfaces/elements.ts:49](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L49)

___

### restored

▸ **restored**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`IItem`](IItem.md) |

#### Returns

`void`

#### Inherited from

[IElement](IElement.md).[restored](IElement.md#restored)

#### Defined in

[interfaces/elements.ts:28](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L28)

___

### resume

▸ **resume**(`item`): `void`

is called by the token after an execution resume for every active (in wait) item
different than init, which is called for all items

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`IItem`](IItem.md) |

#### Returns

`void`

#### Overrides

[IElement](IElement.md).[resume](IElement.md#resume)

#### Defined in

[interfaces/elements.ts:70](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L70)

___

### run

▸ **run**(`item`): `Promise`\<[`NODE_ACTION`](../enums/node_action.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`IItem`](IItem.md) |

#### Returns

`Promise`\<[`NODE_ACTION`](../enums/node_action.md)\>

#### Defined in

[interfaces/elements.ts:63](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L63)

___

### start

▸ **start**(`item`): `Promise`\<[`NODE_ACTION`](../enums/node_action.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`IItem`](IItem.md) |

#### Returns

`Promise`\<[`NODE_ACTION`](../enums/node_action.md)\>

#### Defined in

[interfaces/elements.ts:62](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L62)
