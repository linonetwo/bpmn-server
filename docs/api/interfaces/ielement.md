[bpmn-server](../README.md) / IElement

# Interface: IElement

## Hierarchy

- **`IElement`**

  ↳ [`INode`](inode.md)

  ↳ [`IFlow`](iflow.md)

## Implemented by

- [`Element`](../classes/element.md)

## Table of contents

### Properties

- [behaviours](ielement.md#behaviours)
- [id](ielement.md#id)
- [lane](ielement.md#lane)
- [name](ielement.md#name)
- [type](ielement.md#type)

### Methods

- [addBehaviour](ielement.md#addbehaviour)
- [continue](ielement.md#continue)
- [describe](ielement.md#describe)
- [getBehaviour](ielement.md#getbehaviour)
- [hasBehaviour](ielement.md#hasbehaviour)
- [restored](ielement.md#restored)
- [resume](ielement.md#resume)

## Properties

### behaviours

• **behaviours**: `Map`\<`any`, `any`\>

#### Defined in

[interfaces/elements.ts:25](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L25)

___

### id

• **id**: `any`

#### Defined in

[interfaces/elements.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L21)

___

### lane

• **lane**: `any`

#### Defined in

[interfaces/elements.ts:24](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L24)

___

### name

• **name**: `any`

#### Defined in

[interfaces/elements.ts:23](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L23)

___

### type

• **type**: `any`

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

#### Defined in

[interfaces/elements.ts:26](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L26)

___

### describe

▸ **describe**(): `string`[][]

#### Returns

`string`[][]

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

#### Defined in

[interfaces/elements.ts:29](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/elements.ts#L29)
