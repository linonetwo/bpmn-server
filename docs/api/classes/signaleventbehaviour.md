[bpmn-server](../README.md) / SignalEventBehaviour

# Class: SignalEventBehaviour

Behaviour
     ioSpecification
     timer 
     message
     signal

  each behaviour is a class
     it scans def and insert itself to perform actions as required

## Hierarchy

- [`Behaviour`](behaviour.md)

  ↳ **`SignalEventBehaviour`**

## Table of contents

### Constructors

- [constructor](SignalEventbehaviour.md#constructor)

### Properties

- [definition](SignalEventbehaviour.md#definition)
- [node](SignalEventbehaviour.md#node)

### Accessors

- [signalId](SignalEventbehaviour.md#signalid)

### Methods

- [describe](SignalEventbehaviour.md#describe)
- [end](SignalEventbehaviour.md#end)
- [enter](SignalEventbehaviour.md#enter)
- [exit](SignalEventbehaviour.md#exit)
- [getItemAttributes](SignalEventbehaviour.md#getitemattributes)
- [getNodeAttributes](SignalEventbehaviour.md#getnodeattributes)
- [init](SignalEventbehaviour.md#init)
- [restored](SignalEventbehaviour.md#restored)
- [resume](SignalEventbehaviour.md#resume)
- [run](SignalEventbehaviour.md#run)
- [start](SignalEventbehaviour.md#start)

## Constructors

### constructor

• **new SignalEventBehaviour**(`node`, `definition`): [`SignalEventBehaviour`](SignalEventbehaviour.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](Node.md) |
| `definition` | `any` |

#### Returns

[`SignalEventBehaviour`](SignalEventbehaviour.md)

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

## Accessors

### signalId

• `get` **signalId**(): `any`

#### Returns

`any`

#### Defined in

[elements/behaviours/MessageSignal.ts:76](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/MessageSignal.ts#L76)

## Methods

### describe

▸ **describe**(): `string`[]

#### Returns

`string`[]

#### Overrides

[Behaviour](behaviour.md).[describe](behaviour.md#describe)

#### Defined in

[elements/behaviours/MessageSignal.ts:70](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/MessageSignal.ts#L70)

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

[elements/behaviours/MessageSignal.ts:68](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/MessageSignal.ts#L68)

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

#### Overrides

[Behaviour](behaviour.md).[init](behaviour.md#init)

#### Defined in

[elements/behaviours/MessageSignal.ts:50](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/MessageSignal.ts#L50)

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

▸ **start**(`item`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](Item.md) |

#### Returns

`Promise`\<`void`\>

#### Overrides

[Behaviour](behaviour.md).[start](behaviour.md#start)

#### Defined in

[elements/behaviours/MessageSignal.ts:54](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/MessageSignal.ts#L54)
