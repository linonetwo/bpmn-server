[bpmn-server](../README.md) / MessageFlow

# Class: MessageFlow

<Rule>MessageFlow: can only be sent to active node in waiting
 * or to a start event
</Rule>

## Hierarchy

- [`Flow`](flow.md)

  ↳ **`MessageFlow`**

## Table of contents

### Constructors

- [constructor](messageflow.md#constructor)

### Properties

- [behaviours](messageflow.md#behaviours)
- [def](messageflow.md#def)
- [from](messageflow.md#from)
- [id](messageflow.md#id)
- [isFlow](messageflow.md#isflow)
- [isMessageFlow](messageflow.md#ismessageflow)
- [lane](messageflow.md#lane)
- [name](messageflow.md#name)
- [subType](messageflow.md#subtype)
- [to](messageflow.md#to)
- [type](messageflow.md#type)

### Methods

- [addBehaviour](messageflow.md#addbehaviour)
- [continue](messageflow.md#continue)
- [describe](messageflow.md#describe)
- [evaluateCondition](messageflow.md#evaluatecondition)
- [execute](messageflow.md#execute)
- [getBehaviour](messageflow.md#getbehaviour)
- [hasBehaviour](messageflow.md#hasbehaviour)
- [restored](messageflow.md#restored)
- [resume](messageflow.md#resume)
- [run](messageflow.md#run)

## Constructors

### constructor

• **new MessageFlow**(`id`, `type`, `from`, `to`, `def`): [`MessageFlow`](messageflow.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `any` |
| `type` | `any` |
| `from` | `any` |
| `to` | `any` |
| `def` | `any` |

#### Returns

[`MessageFlow`](messageflow.md)

#### Inherited from

[Flow](flow.md).[constructor](flow.md#constructor)

#### Defined in

[elements/Flow.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L16)

## Properties

### behaviours

• **behaviours**: `Map`\<`any`, `any`\>

#### Inherited from

[Flow](flow.md).[behaviours](flow.md#behaviours)

#### Defined in

[elements/Element.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L17)

___

### def

• **def**: `any`

#### Inherited from

[Flow](flow.md).[def](flow.md#def)

#### Defined in

[elements/Flow.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L14)

___

### from

• **from**: [`Node`](node.md)

#### Inherited from

[Flow](flow.md).[from](flow.md#from)

#### Defined in

[elements/Flow.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L12)

___

### id

• **id**: `any`

#### Inherited from

[Flow](flow.md).[id](flow.md#id)

#### Defined in

[elements/Element.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L13)

___

### isFlow

• **isFlow**: `boolean` = `false`

#### Inherited from

[Flow](flow.md).[isFlow](flow.md#isflow)

#### Defined in

[elements/Element.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L18)

___

### isMessageFlow

• **isMessageFlow**: `boolean` = `true`

#### Overrides

[Flow](flow.md).[isMessageFlow](flow.md#ismessageflow)

#### Defined in

[elements/Flow.ts:78](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L78)

___

### lane

• **lane**: `any`

#### Inherited from

[Flow](flow.md).[lane](flow.md#lane)

#### Defined in

[elements/Element.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L19)

___

### name

• **name**: `any`

#### Inherited from

[Flow](flow.md).[name](flow.md#name)

#### Defined in

[elements/Element.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L16)

___

### subType

• **subType**: `any`

#### Inherited from

[Flow](flow.md).[subType](flow.md#subtype)

#### Defined in

[elements/Element.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L15)

___

### to

• **to**: [`Node`](node.md)

#### Inherited from

[Flow](flow.md).[to](flow.md#to)

#### Defined in

[elements/Flow.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L13)

___

### type

• **type**: `any`

#### Inherited from

[Flow](flow.md).[type](flow.md#type)

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

[Flow](flow.md).[addBehaviour](flow.md#addbehaviour)

#### Defined in

[elements/Element.ts:39](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L39)

___

### continue

▸ **continue**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`void`

#### Inherited from

[Flow](flow.md).[continue](flow.md#continue)

#### Defined in

[elements/Element.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L20)

___

### describe

▸ **describe**(): `any`[][]

#### Returns

`any`[][]

#### Inherited from

[Flow](flow.md).[describe](flow.md#describe)

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

[Flow](flow.md).[evaluateCondition](flow.md#evaluatecondition)

#### Defined in

[elements/Flow.ts:53](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L53)

___

### execute

▸ **execute**(`item`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`Promise`\<`void`\>

#### Overrides

[Flow](flow.md).[execute](flow.md#execute)

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

[Flow](flow.md).[getBehaviour](flow.md#getbehaviour)

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

[Flow](flow.md).[hasBehaviour](flow.md#hasbehaviour)

#### Defined in

[elements/Element.ts:32](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L32)

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

[Flow](flow.md).[restored](flow.md#restored)

#### Defined in

[elements/Element.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L22)

___

### resume

▸ **resume**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`void`

#### Inherited from

[Flow](flow.md).[resume](flow.md#resume)

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
| `item` | [`Item`](item.md) |

#### Returns

[`FLOW_ACTION`](../enums/flow_action.md)

#### Inherited from

[Flow](flow.md).[run](flow.md#run)

#### Defined in

[elements/Flow.ts:43](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L43)
