[bpmn-server](../README.md) / TimerBehaviour

# Class: TimerBehaviour

Behaviour
     ioSpecification
     timer 
     message
     signal

  each behaviour is a class
     it scans def and insert itself to perform actions as required

## Hierarchy

- [`Behaviour`](behaviour.md)

  ↳ **`TimerBehaviour`**

## Table of contents

### Constructors

- [constructor](timerbehaviour.md#constructor)

### Properties

- [definition](timerbehaviour.md#definition)
- [duration](timerbehaviour.md#duration)
- [node](timerbehaviour.md#node)
- [repeat](timerbehaviour.md#repeat)
- [timeCycle](timerbehaviour.md#timecycle)
- [timeDate](timerbehaviour.md#timedate)

### Methods

- [describe](timerbehaviour.md#describe)
- [end](timerbehaviour.md#end)
- [enter](timerbehaviour.md#enter)
- [exit](timerbehaviour.md#exit)
- [expires](timerbehaviour.md#expires)
- [getItemAttributes](timerbehaviour.md#getitemattributes)
- [getNodeAttributes](timerbehaviour.md#getnodeattributes)
- [getRepeat](timerbehaviour.md#getrepeat)
- [init](timerbehaviour.md#init)
- [restored](timerbehaviour.md#restored)
- [resume](timerbehaviour.md#resume)
- [run](timerbehaviour.md#run)
- [start](timerbehaviour.md#start)
- [startTimer](timerbehaviour.md#starttimer)
- [timeDue](timerbehaviour.md#timedue)

## Constructors

### constructor

• **new TimerBehaviour**(`node`, `definition`): [`TimerBehaviour`](timerbehaviour.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](node.md) |
| `definition` | `any` |

#### Returns

[`TimerBehaviour`](timerbehaviour.md)

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

### duration

• **duration**: `any`

#### Defined in

[elements/behaviours/Timer.ts:55](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Timer.ts#L55)

___

### node

• **node**: [`Node`](node.md)

#### Inherited from

[Behaviour](behaviour.md).[node](behaviour.md#node)

#### Defined in

[elements/behaviours/Behaviour.ts:38](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Behaviour.ts#L38)

___

### repeat

• **repeat**: `number` = `1`

#### Defined in

[elements/behaviours/Timer.ts:56](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Timer.ts#L56)

___

### timeCycle

• **timeCycle**: `any`

#### Defined in

[elements/behaviours/Timer.ts:57](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Timer.ts#L57)

___

### timeDate

• **timeDate**: `any`

#### Defined in

[elements/behaviours/Timer.ts:58](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Timer.ts#L58)

## Methods

### describe

▸ **describe**(): `string`[]

#### Returns

`string`[]

#### Overrides

[Behaviour](behaviour.md).[describe](behaviour.md#describe)

#### Defined in

[elements/behaviours/Timer.ts:82](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Timer.ts#L82)

___

### end

▸ **end**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

`void`

#### Overrides

[Behaviour](behaviour.md).[end](behaviour.md#end)

#### Defined in

[elements/behaviours/Timer.ts:193](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Timer.ts#L193)

___

### enter

▸ **enter**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

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
| `item` | [`Item`](item.md) |

#### Returns

`void`

#### Inherited from

[Behaviour](behaviour.md).[exit](behaviour.md#exit)

#### Defined in

[elements/behaviours/Behaviour.ts:52](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Behaviour.ts#L52)

___

### expires

▸ **expires**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

#### Defined in

[elements/behaviours/Timer.ts:157](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Timer.ts#L157)

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

### getRepeat

▸ **getRepeat**(`input`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `input` | `any` |

#### Returns

`any`

#### Defined in

[elements/behaviours/Timer.ts:120](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Timer.ts#L120)

___

### init

▸ **init**(): `void`

#### Returns

`void`

#### Overrides

[Behaviour](behaviour.md).[init](behaviour.md#init)

#### Defined in

[elements/behaviours/Timer.ts:59](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Timer.ts#L59)

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

▸ **resume**(): `void`

#### Returns

`void`

#### Overrides

[Behaviour](behaviour.md).[resume](behaviour.md#resume)

#### Defined in

[elements/behaviours/Timer.ts:197](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Timer.ts#L197)

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

▸ **start**(`item`): [`NODE_ACTION`](../enums/node_action.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | [`Item`](item.md) |

#### Returns

[`NODE_ACTION`](../enums/node_action.md)

#### Overrides

[Behaviour](behaviour.md).[start](behaviour.md#start)

#### Defined in

[elements/behaviours/Timer.ts:128](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Timer.ts#L128)

___

### startTimer

▸ **startTimer**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |

#### Returns

`void`

#### Defined in

[elements/behaviours/Timer.ts:139](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Timer.ts#L139)

___

### timeDue

▸ **timeDue**(`item`, `timerModifier?`): `any`

return the next time the timer is due
format is time format

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `item` | `any` | `undefined` | - |
| `timerModifier` | `any` | `null` | for testing purposes configuration can alter the timer |

#### Returns

`any`

#### Defined in

[elements/behaviours/Timer.ts:90](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/Timer.ts#L90)
