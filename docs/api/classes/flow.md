[bpmn-server](../README.md) / Flow

# Class: Flow

## Hierarchy

- [`Element`](element.md)

  ↳ **`Flow`**

  ↳↳ [`MessageFlow`](messageflow.md)

## Implements

- [`IFlow`](../interfaces/iflow.md)

## Table of contents

### Constructors

- [constructor](flow.md#constructor)

### Properties

- [behaviours](flow.md#behaviours)
- [def](flow.md#def)
- [from](flow.md#from)
- [id](flow.md#id)
- [isFlow](flow.md#isflow)
- [isMessageFlow](flow.md#ismessageflow)
- [lane](flow.md#lane)
- [name](flow.md#name)
- [subType](flow.md#subtype)
- [to](flow.md#to)
- [type](flow.md#type)

### Methods

- [addBehaviour](flow.md#addbehaviour)
- [continue](flow.md#continue)
- [describe](flow.md#describe)
- [evaluateCondition](flow.md#evaluatecondition)
- [execute](flow.md#execute)
- [getBehaviour](flow.md#getbehaviour)
- [hasBehaviour](flow.md#hasbehaviour)
- [restored](flow.md#restored)
- [resume](flow.md#resume)
- [run](flow.md#run)

## Constructors

### constructor

• **new Flow**(`id`, `type`, `from`, `to`, `def`): [`Flow`](flow.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `any` |
| `type` | `any` |
| `from` | `any` |
| `to` | `any` |
| `def` | `any` |

#### Returns

[`Flow`](flow.md)

#### Overrides

[Element](element.md).[constructor](element.md#constructor)

#### Defined in

[elements/Flow.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L16)

## Properties

### behaviours

• **behaviours**: `Map`\<`any`, `any`\>

#### Implementation of

[IFlow](../interfaces/iflow.md).[behaviours](../interfaces/iflow.md#behaviours)

#### Inherited from

[Element](element.md).[behaviours](element.md#behaviours)

#### Defined in

[elements/Element.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L17)

___

### def

• **def**: `any`

#### Defined in

[elements/Flow.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L14)

___

### from

• **from**: [`Node`](node.md)

#### Defined in

[elements/Flow.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L12)

___

### id

• **id**: `any`

#### Implementation of

[IFlow](../interfaces/iflow.md).[id](../interfaces/iflow.md#id)

#### Inherited from

[Element](element.md).[id](element.md#id)

#### Defined in

[elements/Element.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L13)

___

### isFlow

• **isFlow**: `boolean` = `false`

#### Inherited from

[Element](element.md).[isFlow](element.md#isflow)

#### Defined in

[elements/Element.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L18)

___

### isMessageFlow

• **isMessageFlow**: `boolean` = `false`

#### Defined in

[elements/Flow.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L15)

___

### lane

• **lane**: `any`

#### Implementation of

[IFlow](../interfaces/iflow.md).[lane](../interfaces/iflow.md#lane)

#### Inherited from

[Element](element.md).[lane](element.md#lane)

#### Defined in

[elements/Element.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L19)

___

### name

• **name**: `any`

#### Implementation of

[IFlow](../interfaces/iflow.md).[name](../interfaces/iflow.md#name)

#### Inherited from

[Element](element.md).[name](element.md#name)

#### Defined in

[elements/Element.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L16)

___

### subType

• **subType**: `any`

#### Inherited from

[Element](element.md).[subType](element.md#subtype)

#### Defined in

[elements/Element.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L15)

___

### to

• **to**: [`Node`](node.md)

#### Defined in

[elements/Flow.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L13)

___

### type

• **type**: `any`

#### Implementation of

[IFlow](../interfaces/iflow.md).[type](../interfaces/iflow.md#type)

#### Inherited from

[Element](element.md).[type](element.md#type)

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

#### Implementation of

[IFlow](../interfaces/iflow.md).[addBehaviour](../interfaces/iflow.md#addbehaviour)

#### Inherited from

[Element](element.md).[addBehaviour](element.md#addbehaviour)

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

#### Implementation of

[IFlow](../interfaces/iflow.md).[continue](../interfaces/iflow.md#continue)

#### Inherited from

[Element](element.md).[continue](element.md#continue)

#### Defined in

[elements/Element.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L20)

___

### describe

▸ **describe**(): `any`[][]

#### Returns

`any`[][]

#### Implementation of

[IFlow](../interfaces/iflow.md).[describe](../interfaces/iflow.md#describe)

#### Overrides

[Element](element.md).[describe](element.md#describe)

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

#### Defined in

[elements/Flow.ts:53](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L53)

___

### execute

▸ **execute**(`item`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |

#### Returns

`Promise`\<`void`\>

#### Defined in

[elements/Flow.ts:66](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L66)

___

### getBehaviour

▸ **getBehaviour**(`name`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `any` |

#### Returns

`any`

#### Implementation of

[IFlow](../interfaces/iflow.md).[getBehaviour](../interfaces/iflow.md#getbehaviour)

#### Inherited from

[Element](element.md).[getBehaviour](element.md#getbehaviour)

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

#### Implementation of

[IFlow](../interfaces/iflow.md).[hasBehaviour](../interfaces/iflow.md#hasbehaviour)

#### Inherited from

[Element](element.md).[hasBehaviour](element.md#hasbehaviour)

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

#### Implementation of

[IFlow](../interfaces/iflow.md).[restored](../interfaces/iflow.md#restored)

#### Inherited from

[Element](element.md).[restored](element.md#restored)

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

#### Implementation of

[IFlow](../interfaces/iflow.md).[resume](../interfaces/iflow.md#resume)

#### Inherited from

[Element](element.md).[resume](element.md#resume)

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

#### Defined in

[elements/Flow.ts:43](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Flow.ts#L43)
