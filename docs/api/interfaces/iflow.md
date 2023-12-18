[bpmn-server](../README.md) / IFlow

# Interface: IFlow

## Hierarchy

- [`IElement`](ielement.md)

  ↳ **`IFlow`**

## Implemented by

- [`Flow`](../classes/flow.md)

## Table of contents

### Properties

- [behaviours](iflow.md#behaviours)
- [id](iflow.md#id)
- [lane](iflow.md#lane)
- [name](iflow.md#name)
- [type](iflow.md#type)

### Methods

- [addBehaviour](iflow.md#addbehaviour)
- [continue](iflow.md#continue)
- [describe](iflow.md#describe)
- [getBehaviour](iflow.md#getbehaviour)
- [hasBehaviour](iflow.md#hasbehaviour)
- [restored](iflow.md#restored)
- [resume](iflow.md#resume)

## Properties

### behaviours

• **behaviours**: `Map`\<`any`, `any`\>

#### Inherited from

[IElement](ielement.md).[behaviours](ielement.md#behaviours)

#### Defined in

[interfaces/elements.ts:25](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L25)

___

### id

• **id**: `any`

#### Inherited from

[IElement](ielement.md).[id](ielement.md#id)

#### Defined in

[interfaces/elements.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L21)

___

### lane

• **lane**: `any`

#### Inherited from

[IElement](ielement.md).[lane](ielement.md#lane)

#### Defined in

[interfaces/elements.ts:24](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L24)

___

### name

• **name**: `any`

#### Inherited from

[IElement](ielement.md).[name](ielement.md#name)

#### Defined in

[interfaces/elements.ts:23](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L23)

___

### type

• **type**: `any`

#### Inherited from

[IElement](ielement.md).[type](ielement.md#type)

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

[IElement](ielement.md).[addBehaviour](ielement.md#addbehaviour)

#### Defined in

[interfaces/elements.ts:36](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L36)

___

### continue

▸ **continue**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`IItem`](iitem.md) |

#### Returns

`void`

#### Inherited from

[IElement](ielement.md).[continue](ielement.md#continue)

#### Defined in

[interfaces/elements.ts:26](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L26)

___

### describe

▸ **describe**(): `string`[][]

#### Returns

`string`[][]

#### Inherited from

[IElement](ielement.md).[describe](ielement.md#describe)

#### Defined in

[interfaces/elements.ts:27](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L27)

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

[IElement](ielement.md).[getBehaviour](ielement.md#getbehaviour)

#### Defined in

[interfaces/elements.ts:35](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L35)

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

[IElement](ielement.md).[hasBehaviour](ielement.md#hasbehaviour)

#### Defined in

[interfaces/elements.ts:34](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L34)

___

### restored

▸ **restored**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`IItem`](iitem.md) |

#### Returns

`void`

#### Inherited from

[IElement](ielement.md).[restored](ielement.md#restored)

#### Defined in

[interfaces/elements.ts:28](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L28)

___

### resume

▸ **resume**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`IItem`](iitem.md) |

#### Returns

`void`

#### Inherited from

[IElement](ielement.md).[resume](ielement.md#resume)

#### Defined in

[interfaces/elements.ts:29](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L29)
