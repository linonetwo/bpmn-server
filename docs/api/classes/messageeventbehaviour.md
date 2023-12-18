[bpmn-server](../README.md) / MessageEventBehaviour

# Class: MessageEventBehaviour

it is part of the following:

 events
 sendTask
 receiveTask

## Hierarchy

- [`Behaviour`](behaviour.md)

  ↳ **`MessageEventBehaviour`**

## Table of contents

### Constructors

- [constructor](MessageEventbehaviour.md#constructor)

### Properties

- [definition](MessageEventbehaviour.md#definition)
- [node](MessageEventbehaviour.md#node)

### Accessors

- [messageId](MessageEventbehaviour.md#messageid)

### Methods

- [describe](MessageEventbehaviour.md#describe)
- [end](MessageEventbehaviour.md#end)
- [enter](MessageEventbehaviour.md#enter)
- [exit](MessageEventbehaviour.md#exit)
- [getItemAttributes](MessageEventbehaviour.md#getitemattributes)
- [getNodeAttributes](MessageEventbehaviour.md#getnodeattributes)
- [init](MessageEventbehaviour.md#init)
- [restored](MessageEventbehaviour.md#restored)
- [resume](MessageEventbehaviour.md#resume)
- [run](MessageEventbehaviour.md#run)
- [start](MessageEventbehaviour.md#start)

## Constructors

### constructor

• **new MessageEventBehaviour**(`node`, `definition`): [`MessageEventBehaviour`](MessageEventbehaviour.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](Node.md) |
| `definition` | `any` |

#### Returns

[`MessageEventBehaviour`](MessageEventbehaviour.md)

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

### messageId

• `get` **messageId**(): `any`

#### Returns

`any`

#### Defined in

[elements/behaviours/MessageSignal.ts:38](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/MessageSignal.ts#L38)

## Methods

### describe

▸ **describe**(): `string`[]

#### Returns

`string`[]

#### Overrides

[Behaviour](behaviour.md).[describe](behaviour.md#describe)

#### Defined in

[elements/behaviours/MessageSignal.ts:42](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/MessageSignal.ts#L42)

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

[elements/behaviours/MessageSignal.ts:35](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/MessageSignal.ts#L35)

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

[elements/behaviours/MessageSignal.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/MessageSignal.ts#L17)

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

[elements/behaviours/MessageSignal.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/MessageSignal.ts#L22)
