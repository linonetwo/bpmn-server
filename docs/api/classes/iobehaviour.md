[bpmn-server](../README.md) / IOBehaviour

# Class: IOBehaviour

Behaviour
     ioSpecification
     timer 
     message
     signal

  each behaviour is a class
     it scans def and insert itself to perform actions as required

## Hierarchy

- [`Behaviour`](behaviour.md)

  ↳ **`IOBehaviour`**

## Table of contents

### Constructors

- [constructor](iobehaviour.md#constructor)

### Properties

- [definition](iobehaviour.md#definition)
- [node](iobehaviour.md#node)
- [parameters](iobehaviour.md#parameters)

### Methods

- [describe](iobehaviour.md#describe)
- [end](iobehaviour.md#end)
- [enter](iobehaviour.md#enter)
- [exit](iobehaviour.md#exit)
- [getItemAttributes](iobehaviour.md#getitemattributes)
- [getNodeAttributes](iobehaviour.md#getnodeattributes)
- [init](iobehaviour.md#init)
- [process](iobehaviour.md#process)
- [restored](iobehaviour.md#restored)
- [resume](iobehaviour.md#resume)
- [run](iobehaviour.md#run)
- [start](iobehaviour.md#start)

## Constructors

### constructor

• **new IOBehaviour**(`node`, `definition`): [`IOBehaviour`](iobehaviour.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](node.md) |
| `definition` | `any` |

#### Returns

[`IOBehaviour`](iobehaviour.md)

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

• **node**: [`Node`](node.md)

#### Inherited from

[Behaviour](behaviour.md).[node](behaviour.md#node)

#### Defined in

[elements/behaviours/Behaviour.ts:38](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Behaviour.ts#L38)

___

### parameters

• **parameters**: `IOParameter`[]

#### Defined in

[elements/behaviours/IOBehaviour.ts:87](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/IOBehaviour.ts#L87)

## Methods

### describe

▸ **describe**(): `string`[][]

#### Returns

`string`[][]

#### Overrides

[Behaviour](behaviour.md).[describe](behaviour.md#describe)

#### Defined in

[elements/behaviours/IOBehaviour.ts:165](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/IOBehaviour.ts#L165)

___

### end

▸ **end**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`void`

#### Inherited from

[Behaviour](behaviour.md).[end](behaviour.md#end)

#### Defined in

[elements/behaviours/Behaviour.ts:51](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Behaviour.ts#L51)

___

### enter

▸ **enter**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`void`

#### Overrides

[Behaviour](behaviour.md).[enter](behaviour.md#enter)

#### Defined in

[elements/behaviours/IOBehaviour.ts:103](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/IOBehaviour.ts#L103)

___

### exit

▸ **exit**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`void`

#### Overrides

[Behaviour](behaviour.md).[exit](behaviour.md#exit)

#### Defined in

[elements/behaviours/IOBehaviour.ts:144](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/IOBehaviour.ts#L144)

___

### getItemAttributes

▸ **getItemAttributes**(`item`, `attributes`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |
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

#### Overrides

[Behaviour](behaviour.md).[init](behaviour.md#init)

#### Defined in

[elements/behaviours/IOBehaviour.ts:89](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/IOBehaviour.ts#L89)

___

### process

▸ **process**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`void`

#### Defined in

[elements/behaviours/IOBehaviour.ts:133](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/IOBehaviour.ts#L133)

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
| `item` | [`Item`](item.md) |

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
| `item` | [`Item`](item.md) |

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
| `item` | [`Item`](item.md) |

#### Returns

`void`

#### Inherited from

[Behaviour](behaviour.md).[start](behaviour.md#start)

#### Defined in

[elements/behaviours/Behaviour.ts:49](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Behaviour.ts#L49)
