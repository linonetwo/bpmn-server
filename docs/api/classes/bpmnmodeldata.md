[bpmn-server](../README.md) / BpmnModelData

# Class: BpmnModelData

## Implements

- [`IBpmnModelData`](../interfaces/ibpmnmodeldata.md)

## Table of contents

### Constructors

- [constructor](bpmnmodeldata.md#constructor)

### Properties

- [events](bpmnmodeldata.md#events)
- [name](bpmnmodeldata.md#name)
- [processes](bpmnmodeldata.md#processes)
- [saved](bpmnmodeldata.md#saved)
- [source](bpmnmodeldata.md#source)
- [svg](bpmnmodeldata.md#svg)

### Methods

- [parse](bpmnmodeldata.md#parse)

## Constructors

### constructor

• **new BpmnModelData**(`name`, `source`, `svg`, `processes`, `events`): [`BpmnModelData`](bpmnmodeldata.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `any` |
| `source` | `any` |
| `svg` | `any` |
| `processes` | `any` |
| `events` | `any` |

#### Returns

[`BpmnModelData`](bpmnmodeldata.md)

#### Defined in

[datastore/ModelsData.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsData.ts#L18)

## Properties

### events

• **events**: [`IEventData`](../interfaces/ieventdata.md)[]

#### Implementation of

[IBpmnModelData](../interfaces/ibpmnmodeldata.md).[events](../interfaces/ibpmnmodeldata.md#events)

#### Defined in

[datastore/ModelsData.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsData.ts#L16)

___

### name

• **name**: `any`

#### Implementation of

[IBpmnModelData](../interfaces/ibpmnmodeldata.md).[name](../interfaces/ibpmnmodeldata.md#name)

#### Defined in

[datastore/ModelsData.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsData.ts#L12)

___

### processes

• **processes**: [`IProcessData`](../interfaces/iprocessdata.md)[]

#### Implementation of

[IBpmnModelData](../interfaces/ibpmnmodeldata.md).[processes](../interfaces/ibpmnmodeldata.md#processes)

#### Defined in

[datastore/ModelsData.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsData.ts#L15)

___

### saved

• **saved**: `any`

#### Implementation of

[IBpmnModelData](../interfaces/ibpmnmodeldata.md).[saved](../interfaces/ibpmnmodeldata.md#saved)

#### Defined in

[datastore/ModelsData.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsData.ts#L17)

___

### source

• **source**: `any`

#### Implementation of

[IBpmnModelData](../interfaces/ibpmnmodeldata.md).[source](../interfaces/ibpmnmodeldata.md#source)

#### Defined in

[datastore/ModelsData.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsData.ts#L13)

___

### svg

• **svg**: `any`

#### Implementation of

[IBpmnModelData](../interfaces/ibpmnmodeldata.md).[svg](../interfaces/ibpmnmodeldata.md#svg)

#### Defined in

[datastore/ModelsData.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsData.ts#L14)

## Methods

### parse

▸ **parse**(`definition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `definition` | [`Definition`](definition.md) |

#### Returns

`void`

#### Defined in

[datastore/ModelsData.ts:30](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsData.ts#L30)
