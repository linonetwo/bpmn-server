[bpmn-server](../README.md) / TerminateBehaviour

# Class: TerminateBehaviour

Behaviour
     ioSpecification
     timer 
     message
     signal

  each behaviour is a class
     it scans def and insert itself to perform actions as required

## Hierarchy

- [`Behaviour`](behaviour.md)

  ↳ **`TerminateBehaviour`**

## Table of contents

### Constructors

- [constructor](Terminatebehaviour.md#constructor)

### Properties

- [definition](Terminatebehaviour.md#definition)
- [node](Terminatebehaviour.md#node)

### Methods

- [describe](Terminatebehaviour.md#describe)
- [end](Terminatebehaviour.md#end)
- [enter](Terminatebehaviour.md#enter)
- [exit](Terminatebehaviour.md#exit)
- [getItemAttributes](Terminatebehaviour.md#getitemattributes)
- [getNodeAttributes](Terminatebehaviour.md#getnodeattributes)
- [init](Terminatebehaviour.md#init)
- [restored](Terminatebehaviour.md#restored)
- [resume](Terminatebehaviour.md#resume)
- [run](Terminatebehaviour.md#run)
- [start](Terminatebehaviour.md#start)

## Constructors

### constructor

• **new TerminateBehaviour**(`node`, `definition`): [`TerminateBehaviour`](Terminatebehaviour.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](Node.md) |
| `definition` | `any` |

#### Returns

[`TerminateBehaviour`](Terminatebehaviour.md)

#### Inherited from

[Behaviour](behaviour.md).[constructor](behaviour.md#constructor)

#### Defined in

[elements/behaviours/Behaviour.ts:40](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Behaviour.ts#L40)

## Properties

### definition

• **definition**: `any`

#### Inherited from

[Behaviour](behaviour.md).[definition](behaviour.md#definition)

#### Defined in

[elements/behaviours/Behaviour.ts:39](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Behaviour.ts#L39)

___

### node

• **node**: [`Node`](Node.md)

#### Inherited from

[Behaviour](behaviour.md).[node](behaviour.md#node)

#### Defined in

[elements/behaviours/Behaviour.ts:38](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Behaviour.ts#L38)

## Methods

### describe

▸ **describe**(): `string`[]

#### Returns

`string`[]

#### Overrides

[Behaviour](behaviour.md).[describe](behaviour.md#describe)

#### Defined in

[elements/behaviours/Terminate.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Terminate.ts#L18)

___

### end

▸ **end**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`void`

#### Overrides

[Behaviour](behaviour.md).[end](behaviour.md#end)

#### Defined in

[elements/behaviours/Terminate.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Terminate.ts#L12)

___

### enter

▸ **enter**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`void`

#### Inherited from

[Behaviour](behaviour.md).[enter](behaviour.md#enter)

#### Defined in

[elements/behaviours/Behaviour.ts:48](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Behaviour.ts#L48)

___

### exit

▸ **exit**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`void`

#### Inherited from

[Behaviour](behaviour.md).[exit](behaviour.md#exit)

#### Defined in

[elements/behaviours/Behaviour.ts:52](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Behaviour.ts#L52)

___

### getItemAttributes

▸ **getItemAttributes**(`item`, `attributes`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |
| `attributes` | `any`[] |

#### Returns

`void`

#### Inherited from

[Behaviour](behaviour.md).[getItemAttributes](behaviour.md#getitemattributes)

#### Defined in

[elements/behaviours/Behaviour.ts:55](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Behaviour.ts#L55)

___

### getNodeAttributes

▸ **getNodeAttributes**(`attributes`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `attributes` | `any`[] |

#### Returns

`void`

#### Inherited from

[Behaviour](behaviour.md).[getNodeAttributes](behaviour.md#getnodeattributes)

#### Defined in

[elements/behaviours/Behaviour.ts:54](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Behaviour.ts#L54)

___

### init

▸ **init**(): `void`

#### Returns

`void`

#### Inherited from

[Behaviour](behaviour.md).[init](behaviour.md#init)

#### Defined in

[elements/behaviours/Behaviour.ts:47](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Behaviour.ts#L47)

___

### restored

▸ **restored**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |

#### Returns

`void`

#### Inherited from

[Behaviour](behaviour.md).[restored](behaviour.md#restored)

#### Defined in

[elements/behaviours/Behaviour.ts:45](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Behaviour.ts#L45)

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

[Behaviour](behaviour.md).[resume](behaviour.md#resume)

#### Defined in

[elements/behaviours/Behaviour.ts:53](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Behaviour.ts#L53)

___

### run

▸ **run**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`void`

#### Inherited from

[Behaviour](behaviour.md).[run](behaviour.md#run)

#### Defined in

[elements/behaviours/Behaviour.ts:50](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Behaviour.ts#L50)

___

### start

▸ **start**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`void`

#### Overrides

[Behaviour](behaviour.md).[start](behaviour.md#start)

#### Defined in

[elements/behaviours/Terminate.ts:11](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Terminate.ts#L11)
