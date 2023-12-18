[bpmn-server](../README.md) / MessageFlow

# Class: MessageFlow

<Rule>MessageFlow: can only be sent to active node in waiting
 * or to a start event
</Rule>

## Hierarchy

- [`Flow`](Flow.md)

  ↳ **`MessageFlow`**

## Table of contents

### Constructors

- [constructor](MessageFlow.md#constructor)

### Properties

- [behaviours](MessageFlow.md#behaviours)
- [def](MessageFlow.md#def)
- [from](MessageFlow.md#from)
- [id](MessageFlow.md#id)
- [isFlow](MessageFlow.md#isflow)
- [isMessageFlow](MessageFlow.md#ismessageflow)
- [lane](MessageFlow.md#lane)
- [name](MessageFlow.md#name)
- [subType](MessageFlow.md#subtype)
- [to](MessageFlow.md#to)
- [type](MessageFlow.md#type)

### Methods

- [addBehaviour](MessageFlow.md#addbehaviour)
- [continue](MessageFlow.md#continue)
- [describe](MessageFlow.md#describe)
- [evaluateCondition](MessageFlow.md#evaluatecondition)
- [execute](MessageFlow.md#execute)
- [getBehaviour](MessageFlow.md#getbehaviour)
- [hasBehaviour](MessageFlow.md#hasbehaviour)
- [restored](MessageFlow.md#restored)
- [resume](MessageFlow.md#resume)
- [run](MessageFlow.md#run)

## Constructors

### constructor

• **new MessageFlow**(`id`, `type`, `from`, `to`, `def`): [`MessageFlow`](MessageFlow.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `any` |
| `type` | `any` |
| `from` | `any` |
| `to` | `any` |
| `def` | `any` |

#### Returns

[`MessageFlow`](MessageFlow.md)

#### Inherited from

[Flow](Flow.md).[constructor](Flow.md#constructor)

#### Defined in

[elements/Flow.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L16)

## Properties

### behaviours

• **behaviours**: `Map`\<`any`, `any`\>

#### Inherited from

[Flow](Flow.md).[behaviours](Flow.md#behaviours)

#### Defined in

[elements/Element.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L17)

___

### def

• **def**: `any`

#### Inherited from

[Flow](Flow.md).[def](Flow.md#def)

#### Defined in

[elements/Flow.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L14)

___

### from

• **from**: [`Node`](Node.md)

#### Inherited from

[Flow](Flow.md).[from](Flow.md#from)

#### Defined in

[elements/Flow.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L12)

___

### id

• **id**: `any`

#### Inherited from

[Flow](Flow.md).[id](Flow.md#id)

#### Defined in

[elements/Element.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L13)

___

### isFlow

• **isFlow**: `boolean` = `false`

#### Inherited from

[Flow](Flow.md).[isFlow](Flow.md#isflow)

#### Defined in

[elements/Element.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L18)

___

### isMessageFlow

• **isMessageFlow**: `boolean` = `true`

#### Overrides

[Flow](Flow.md).[isMessageFlow](Flow.md#ismessageflow)

#### Defined in

[elements/Flow.ts:78](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L78)

___

### lane

• **lane**: `any`

#### Inherited from

[Flow](Flow.md).[lane](Flow.md#lane)

#### Defined in

[elements/Element.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L19)

___

### name

• **name**: `any`

#### Inherited from

[Flow](Flow.md).[name](Flow.md#name)

#### Defined in

[elements/Element.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L16)

___

### subType

• **subType**: `any`

#### Inherited from

[Flow](Flow.md).[subType](Flow.md#subtype)

#### Defined in

[elements/Element.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L15)

___

### to

• **to**: [`Node`](Node.md)

#### Inherited from

[Flow](Flow.md).[to](Flow.md#to)

#### Defined in

[elements/Flow.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L13)

___

### type

• **type**: `any`

#### Inherited from

[Flow](Flow.md).[type](Flow.md#type)

#### Defined in

[elements/Element.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L14)

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

[Flow](Flow.md).[addBehaviour](Flow.md#addbehaviour)

#### Defined in

[elements/Element.ts:39](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L39)

___

### continue

▸ **continue**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`void`

#### Inherited from

[Flow](Flow.md).[continue](Flow.md#continue)

#### Defined in

[elements/Element.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L20)

___

### describe

▸ **describe**(): `any`[][]

#### Returns

`any`[][]

#### Inherited from

[Flow](Flow.md).[describe](Flow.md#describe)

#### Defined in

[elements/Flow.ts:26](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L26)

___

### evaluateCondition

▸ **evaluateCondition**(`item`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |

#### Returns

`any`

#### Inherited from

[Flow](Flow.md).[evaluateCondition](Flow.md#evaluatecondition)

#### Defined in

[elements/Flow.ts:53](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L53)

___

### execute

▸ **execute**(`item`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`Promise`\<`void`\>

#### Overrides

[Flow](Flow.md).[execute](Flow.md#execute)

#### Defined in

[elements/Flow.ts:80](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L80)

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

[Flow](Flow.md).[getBehaviour](Flow.md#getbehaviour)

#### Defined in

[elements/Element.ts:36](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L36)

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

[Flow](Flow.md).[hasBehaviour](Flow.md#hasbehaviour)

#### Defined in

[elements/Element.ts:32](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L32)

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

[Flow](Flow.md).[restored](Flow.md#restored)

#### Defined in

[elements/Element.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L22)

___

### resume

▸ **resume**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`void`

#### Inherited from

[Flow](Flow.md).[resume](Flow.md#resume)

#### Defined in

[elements/Element.ts:25](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L25)

___

### run

▸ **run**(`item`): [`FLOW_ACTION`](../enums/flow_action.md)

<Rule> if flow has a condition, it must be evaluated and if result is true flow will continue
 otherwise, flow will be discarded.
</Rule>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

[`FLOW_ACTION`](../enums/flow_action.md)

#### Inherited from

[Flow](Flow.md).[run](Flow.md#run)

#### Defined in

[elements/Flow.ts:43](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L43)
