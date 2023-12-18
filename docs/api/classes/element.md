[bpmn-server](../README.md) / Element

# Class: Element

## Hierarchy

- **`Element`**

  ↳ [`Node`](node.md)

  ↳ [`Flow`](flow.md)

## Implements

- [`IElement`](../interfaces/ielement.md)

## Table of contents

### Constructors

- [constructor](element.md#constructor)

### Properties

- [behaviours](element.md#behaviours)
- [id](element.md#id)
- [isFlow](element.md#isflow)
- [lane](element.md#lane)
- [name](element.md#name)
- [subType](element.md#subtype)
- [type](element.md#type)

### Methods

- [addBehaviour](element.md#addbehaviour)
- [continue](element.md#continue)
- [describe](element.md#describe)
- [getBehaviour](element.md#getbehaviour)
- [hasBehaviour](element.md#hasbehaviour)
- [restored](element.md#restored)
- [resume](element.md#resume)

## Constructors

### constructor

• **new Element**(): [`Element`](element.md)

#### Returns

[`Element`](element.md)

## Properties

### behaviours

• **behaviours**: `Map`\<`any`, `any`\>

#### Implementation of

[IElement](../interfaces/ielement.md).[behaviours](../interfaces/ielement.md#behaviours)

#### Defined in

[elements/Element.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L17)

___

### id

• **id**: `any`

#### Implementation of

[IElement](../interfaces/ielement.md).[id](../interfaces/ielement.md#id)

#### Defined in

[elements/Element.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L13)

___

### isFlow

• **isFlow**: `boolean` = `false`

#### Defined in

[elements/Element.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L18)

___

### lane

• **lane**: `any`

#### Implementation of

[IElement](../interfaces/ielement.md).[lane](../interfaces/ielement.md#lane)

#### Defined in

[elements/Element.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L19)

___

### name

• **name**: `any`

#### Implementation of

[IElement](../interfaces/ielement.md).[name](../interfaces/ielement.md#name)

#### Defined in

[elements/Element.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L16)

___

### subType

• **subType**: `any`

#### Defined in

[elements/Element.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L15)

___

### type

• **type**: `any`

#### Implementation of

[IElement](../interfaces/ielement.md).[type](../interfaces/ielement.md#type)

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

[IElement](../interfaces/ielement.md).[addBehaviour](../interfaces/ielement.md#addbehaviour)

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

[IElement](../interfaces/ielement.md).[continue](../interfaces/ielement.md#continue)

#### Defined in

[elements/Element.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L20)

___

### describe

▸ **describe**(): `string`[][]

#### Returns

`string`[][]

#### Implementation of

[IElement](../interfaces/ielement.md).[describe](../interfaces/ielement.md#describe)

#### Defined in

[elements/Element.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L21)

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

[IElement](../interfaces/ielement.md).[getBehaviour](../interfaces/ielement.md#getbehaviour)

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

[IElement](../interfaces/ielement.md).[hasBehaviour](../interfaces/ielement.md#hasbehaviour)

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

[IElement](../interfaces/ielement.md).[restored](../interfaces/ielement.md#restored)

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

[IElement](../interfaces/ielement.md).[resume](../interfaces/ielement.md#resume)

#### Defined in

[elements/Element.ts:25](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Element.ts#L25)
