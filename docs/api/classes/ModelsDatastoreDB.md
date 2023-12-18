[bpmn-server](../README.md) / ModelsDatastoreDB

# Class: ModelsDatastoreDB

super class for various objects that are part of the server

## Hierarchy

- [`ServerComponent`](servercomponent.md)

  ↳ **`ModelsDatastoreDB`**

  ↳↳ [`ModelsDatastore`](modelsdatastore.md)

## Implements

- [`IModelsDatastore`](../interfaces/imodelsdatastore.md)

## Table of contents

### Constructors

- [constructor](modelsdatastoredb.md#constructor)

### Properties

- [db](modelsdatastoredb.md#db)
- [dbConfiguration](modelsdatastoredb.md#dbconfiguration)
- [server](modelsdatastoredb.md#server)

### Accessors

- [appDelegate](modelsdatastoredb.md#appdelegate)
- [cache](modelsdatastoredb.md#cache)
- [configuration](modelsdatastoredb.md#configuration)
- [cron](modelsdatastoredb.md#cron)
- [dataStore](modelsdatastoredb.md#datastore)
- [definitions](modelsdatastoredb.md#definitions)
- [engine](modelsdatastoredb.md#engine)
- [listener](modelsdatastoredb.md#listener)
- [logger](modelsdatastoredb.md#logger)

### Methods

- [deleteModel](modelsdatastoredb.md#deletemodel)
- [export](modelsdatastoredb.md#export)
- [findEvents](modelsdatastoredb.md#findevents)
- [getList](modelsdatastoredb.md#getlist)
- [getSVG](modelsdatastoredb.md#getsvg)
- [getSource](modelsdatastoredb.md#getsource)
- [import](modelsdatastoredb.md#import)
- [install](modelsdatastoredb.md#install)
- [load](modelsdatastoredb.md#load)
- [loadModel](modelsdatastoredb.md#loadmodel)
- [rebuild](modelsdatastoredb.md#rebuild)
- [renameModel](modelsdatastoredb.md#renamemodel)
- [save](modelsdatastoredb.md#save)
- [saveModel](modelsdatastoredb.md#savemodel)
- [updateTimer](modelsdatastoredb.md#updatetimer)

## Constructors

### constructor

• **new ModelsDatastoreDB**(`server`): [`ModelsDatastoreDB`](modelsdatastoredb.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | [`BPMNServer`](bpmnserver.md) |

#### Returns

[`ModelsDatastoreDB`](modelsdatastoredb.md)

#### Overrides

[ServerComponent](servercomponent.md).[constructor](servercomponent.md#constructor)

#### Defined in

[datastore/ModelsDatastoreDB.ts:27](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L27)

## Properties

### db

• **db**: `any`

#### Defined in

[datastore/ModelsDatastoreDB.ts:25](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L25)

___

### dbConfiguration

• **dbConfiguration**: `any`

#### Defined in

[datastore/ModelsDatastoreDB.ts:24](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L24)

___

### server

• **server**: `any`

#### Inherited from

[ServerComponent](servercomponent.md).[server](servercomponent.md#server)

#### Defined in

[server/ServerComponent.ts:9](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L9)

## Accessors

### appDelegate

• `get` **appDelegate**(): `any`

#### Returns

`any`

#### Inherited from

ServerComponent.appDelegate

#### Defined in

[server/ServerComponent.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L18)

___

### cache

• `get` **cache**(): [`CacheManager`](cachemanager.md)

#### Returns

[`CacheManager`](cachemanager.md)

#### Inherited from

ServerComponent.cache

#### Defined in

[server/ServerComponent.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L17)

___

### configuration

• `get` **configuration**(): `any`

#### Returns

`any`

#### Inherited from

ServerComponent.configuration

#### Defined in

[server/ServerComponent.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L14)

___

### cron

• `get` **cron**(): [`Cron`](cron.md)

#### Returns

[`Cron`](cron.md)

#### Inherited from

ServerComponent.cron

#### Defined in

[server/ServerComponent.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L16)

___

### dataStore

• `get` **dataStore**(): `any`

#### Returns

`any`

#### Inherited from

ServerComponent.dataStore

#### Defined in

[server/ServerComponent.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L20)

___

### definitions

• `get` **definitions**(): `any`

#### Returns

`any`

#### Inherited from

ServerComponent.definitions

#### Defined in

[server/ServerComponent.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L21)

___

### engine

• `get` **engine**(): [`IEngine`](../interfaces/iengine.md)

#### Returns

[`IEngine`](../interfaces/iengine.md)

#### Inherited from

ServerComponent.engine

#### Defined in

[server/ServerComponent.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L19)

___

### listener

• `get` **listener**(): `any`

#### Returns

`any`

#### Inherited from

ServerComponent.listener

#### Defined in

[server/ServerComponent.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L22)

___

### logger

• `get` **logger**(): `any`

#### Returns

`any`

#### Inherited from

ServerComponent.logger

#### Defined in

[server/ServerComponent.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L15)

## Methods

### deleteModel

▸ **deleteModel**(`name`, `owner?`): `Promise`\<`void`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `name` | `any` | `undefined` |
| `owner` | `any` | `null` |

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[deleteModel](../interfaces/imodelsdatastore.md#deletemodel)

#### Defined in

[datastore/ModelsDatastoreDB.ts:210](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L210)

___

### export

▸ **export**(`name`, `folderPath`, `owner?`): `Promise`\<`void`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `name` | `any` | `undefined` |
| `folderPath` | `any` | `undefined` |
| `owner` | `any` | `null` |

#### Returns

`Promise`\<`void`\>

#### Defined in

[datastore/ModelsDatastoreDB.ts:233](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L233)

___

### findEvents

▸ **findEvents**(`query`, `owner?`): `Promise`\<[`IEventData`](../interfaces/ieventdata.md)[]\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `query` | `any` | `undefined` |
| `owner` | `any` | `null` |

#### Returns

`Promise`\<[`IEventData`](../interfaces/ieventdata.md)[]\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[findEvents](../interfaces/imodelsdatastore.md#findevents)

#### Defined in

[datastore/ModelsDatastoreDB.ts:97](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L97)

___

### getList

▸ **getList**(`query?`): `Promise`\<`string`[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | `Object` |

#### Returns

`Promise`\<`string`[]\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[getList](../interfaces/imodelsdatastore.md#getlist)

#### Defined in

[datastore/ModelsDatastoreDB.ts:34](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L34)

___

### getSVG

▸ **getSVG**(`name`, `owner?`): `Promise`\<`any`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `name` | `any` | `undefined` |
| `owner` | `any` | `null` |

#### Returns

`Promise`\<`any`\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[getSVG](../interfaces/imodelsdatastore.md#getsvg)

#### Defined in

[datastore/ModelsDatastoreDB.ts:59](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L59)

___

### getSource

▸ **getSource**(`name`, `owner?`): `Promise`\<`any`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `name` | `any` | `undefined` |
| `owner` | `any` | `null` |

#### Returns

`Promise`\<`any`\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[getSource](../interfaces/imodelsdatastore.md#getsource)

#### Defined in

[datastore/ModelsDatastoreDB.ts:54](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L54)

___

### import

▸ **import**(`data`, `owner?`): `Promise`\<`any`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `data` | `any` | `undefined` |
| `owner` | `any` | `null` |

#### Returns

`Promise`\<`any`\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[import](../interfaces/imodelsdatastore.md#import)

#### Defined in

[datastore/ModelsDatastoreDB.ts:160](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L160)

___

### install

▸ **install**(): `Promise`\<`any`\>

first time installation of DB

creates a new collection and add an index

#### Returns

`Promise`\<`any`\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[install](../interfaces/imodelsdatastore.md#install)

#### Defined in

[datastore/ModelsDatastoreDB.ts:157](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L157)

___

### load

▸ **load**(`name`, `owner?`): `Promise`\<[`Definition`](definition.md)\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `name` | `any` | `undefined` |
| `owner` | `any` | `null` |

#### Returns

`Promise`\<[`Definition`](definition.md)\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[load](../interfaces/imodelsdatastore.md#load)

#### Defined in

[datastore/ModelsDatastoreDB.ts:47](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L47)

___

### loadModel

▸ **loadModel**(`name`, `owner?`): `Promise`\<[`BpmnModelData`](bpmnmodeldata.md)\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `name` | `any` | `undefined` |
| `owner` | `any` | `null` |

#### Returns

`Promise`\<[`BpmnModelData`](bpmnmodeldata.md)\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[loadModel](../interfaces/imodelsdatastore.md#loadmodel)

#### Defined in

[datastore/ModelsDatastoreDB.ts:68](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L68)

___

### rebuild

▸ **rebuild**(`model?`): `Promise`\<`void`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `model` | `any` | `null` |

#### Returns

`Promise`\<`void`\>

#### Defined in

[datastore/ModelsDatastoreDB.ts:251](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L251)

___

### renameModel

▸ **renameModel**(`name`, `newName`, `owner?`): `Promise`\<`boolean`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `name` | `any` | `undefined` |
| `newName` | `any` | `undefined` |
| `owner` | `any` | `null` |

#### Returns

`Promise`\<`boolean`\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[renameModel](../interfaces/imodelsdatastore.md#renamemodel)

#### Defined in

[datastore/ModelsDatastoreDB.ts:215](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L215)

___

### save

▸ **save**(`name`, `source`, `svg`, `owner?`): `Promise`\<`any`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `name` | `any` | `undefined` |
| `source` | `any` | `undefined` |
| `svg` | `any` | `undefined` |
| `owner` | `any` | `null` |

#### Returns

`Promise`\<`any`\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[save](../interfaces/imodelsdatastore.md#save)

#### Defined in

[datastore/ModelsDatastoreDB.ts:78](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L78)

___

### saveModel

▸ **saveModel**(`model`, `owner?`): `Promise`\<`boolean`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `model` | [`IBpmnModelData`](../interfaces/ibpmnmodeldata.md) | `undefined` |
| `owner` | `any` | `null` |

#### Returns

`Promise`\<`boolean`\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[saveModel](../interfaces/imodelsdatastore.md#savemodel)

#### Defined in

[datastore/ModelsDatastoreDB.ts:190](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L190)

___

### updateTimer

▸ **updateTimer**(`name`, `owner?`): `Promise`\<`boolean`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `name` | `any` | `undefined` |
| `owner` | `any` | `null` |

#### Returns

`Promise`\<`boolean`\>

#### Defined in

[datastore/ModelsDatastoreDB.ts:164](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L164)
