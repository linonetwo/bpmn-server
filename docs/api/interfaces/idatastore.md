[bpmn-server](../README.md) / IDataStore

# Interface: IDataStore

## Implemented by

- [`DataStore`](../classes/datastore.md)

## Table of contents

### Properties

- [db](idatastore.md#db)
- [dbConfiguration](idatastore.md#dbconfiguration)
- [locker](idatastore.md#locker)
- [logger](idatastore.md#logger)

### Methods

- [deleteInstances](idatastore.md#deleteinstances)
- [findInstance](idatastore.md#findinstance)
- [findInstances](idatastore.md#findinstances)
- [findItem](idatastore.md#finditem)
- [findItems](idatastore.md#finditems)
- [install](idatastore.md#install)
- [loadInstance](idatastore.md#loadinstance)
- [save](idatastore.md#save)

## Properties

### db

• **db**: `any`

#### Defined in

[interfaces/datastore.ts:8](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/datastore.ts#L8)

___

### dbConfiguration

• **dbConfiguration**: `any`

#### Defined in

[interfaces/datastore.ts:7](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/datastore.ts#L7)

___

### locker

• **locker**: `any`

#### Defined in

[interfaces/datastore.ts:10](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/datastore.ts#L10)

___

### logger

• **logger**: `any`

#### Defined in

[interfaces/datastore.ts:9](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/datastore.ts#L9)

## Methods

### deleteInstances

▸ **deleteInstances**(`query?`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `query?` | `any` |

#### Returns

`Promise`\<`void`\>

#### Defined in

[interfaces/datastore.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/datastore.ts#L20)

___

### findInstance

▸ **findInstance**(`query`, `options`): `Promise`\<[`IInstanceData`](iinstancedata.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | `any` |
| `options` | `any` |

#### Returns

`Promise`\<[`IInstanceData`](iinstancedata.md)\>

#### Defined in

[interfaces/datastore.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/datastore.ts#L17)

___

### findInstances

▸ **findInstances**(`query`, `option`): `Promise`\<[`IInstanceData`](iinstancedata.md)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | `any` |
| `option` | ``"full"`` \| ``"summary"`` |

#### Returns

`Promise`\<[`IInstanceData`](iinstancedata.md)[]\>

#### Defined in

[interfaces/datastore.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/datastore.ts#L18)

___

### findItem

▸ **findItem**(`query`): `Promise`\<[`IItemData`](iitemdata.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | `any` |

#### Returns

`Promise`\<[`IItemData`](iitemdata.md)\>

#### Defined in

[interfaces/datastore.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/datastore.ts#L16)

___

### findItems

▸ **findItems**(`query`): `Promise`\<[`IItemData`](iitemdata.md)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | `any` |

#### Returns

`Promise`\<[`IItemData`](iitemdata.md)[]\>

#### Defined in

[interfaces/datastore.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/datastore.ts#L19)

___

### install

▸ **install**(): `any`

#### Returns

`any`

#### Defined in

[interfaces/datastore.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/datastore.ts#L21)

___

### loadInstance

▸ **loadInstance**(`instanceId`, `options`): `Promise`\<\{ `instance`: `any` ; `items`: `any`[]  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `instanceId` | `any` |
| `options` | `any` |

#### Returns

`Promise`\<\{ `instance`: `any` ; `items`: `any`[]  }\>

#### Defined in

[interfaces/datastore.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/datastore.ts#L12)

___

### save

▸ **save**(`instance`, `options`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `instance` | `any` |
| `options` | `any` |

#### Returns

`Promise`\<`void`\>

#### Defined in

[interfaces/datastore.ts:11](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/datastore.ts#L11)
