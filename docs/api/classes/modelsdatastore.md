[bpmn-server](../README.md) / ModelsDatastore

# Class: ModelsDatastore

super class for various objects that are part of the server

## Hierarchy

- [`ModelsDatastoreDB`](modelsdatastoredb.md)

  ↳ **`ModelsDatastore`**

## Implements

- [`IModelsDatastore`](../interfaces/imodelsdatastore.md)

## Table of contents

### Constructors

- [constructor](modelsdatastore.md#constructor)

### Properties

- [db](modelsdatastore.md#db)
- [dbConfiguration](modelsdatastore.md#dbconfiguration)
- [definitionsPath](modelsdatastore.md#definitionspath)
- [server](modelsdatastore.md#server)

### Accessors

- [appDelegate](modelsdatastore.md#appdelegate)
- [cache](modelsdatastore.md#cache)
- [configuration](modelsdatastore.md#configuration)
- [cron](modelsdatastore.md#cron)
- [dataStore](modelsdatastore.md#datastore)
- [definitions](modelsdatastore.md#definitions)
- [engine](modelsdatastore.md#engine)
- [listener](modelsdatastore.md#listener)
- [logger](modelsdatastore.md#logger)

### Methods

- [deleteModel](modelsdatastore.md#deletemodel)
- [export](modelsdatastore.md#export)
- [findEvents](modelsdatastore.md#findevents)
- [getList](modelsdatastore.md#getlist)
- [getSVG](modelsdatastore.md#getsvg)
- [getSource](modelsdatastore.md#getsource)
- [import](modelsdatastore.md#import)
- [install](modelsdatastore.md#install)
- [load](modelsdatastore.md#load)
- [loadModel](modelsdatastore.md#loadmodel)
- [rebuild](modelsdatastore.md#rebuild)
- [renameModel](modelsdatastore.md#renamemodel)
- [save](modelsdatastore.md#save)
- [saveModel](modelsdatastore.md#savemodel)
- [updateTimer](modelsdatastore.md#updatetimer)

## Constructors

### constructor

• **new ModelsDatastore**(`server`): [`ModelsDatastore`](modelsdatastore.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | [`BPMNServer`](bpmnserver.md) |

#### Returns

[`ModelsDatastore`](modelsdatastore.md)

#### Overrides

[ModelsDatastoreDB](modelsdatastoredb.md).[constructor](modelsdatastoredb.md#constructor)

#### Defined in

[datastore/ModelsDatastore.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastore.ts#L19)

## Properties

### db

• **db**: `any`

#### Inherited from

[ModelsDatastoreDB](modelsdatastoredb.md).[db](modelsdatastoredb.md#db)

#### Defined in

[datastore/ModelsDatastoreDB.ts:25](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L25)

___

### dbConfiguration

• **dbConfiguration**: `any`

#### Inherited from

[ModelsDatastoreDB](modelsdatastoredb.md).[dbConfiguration](modelsdatastoredb.md#dbconfiguration)

#### Defined in

[datastore/ModelsDatastoreDB.ts:24](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L24)

___

### definitionsPath

• **definitionsPath**: `any`

#### Defined in

[datastore/ModelsDatastore.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastore.ts#L18)

___

### server

• **server**: `any`

#### Inherited from

[ModelsDatastoreDB](modelsdatastoredb.md).[server](modelsdatastoredb.md#server)

#### Defined in

[server/ServerComponent.ts:9](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L9)

## Accessors

### appDelegate

• `get` **appDelegate**(): `any`

#### Returns

`any`

#### Inherited from

ModelsDatastoreDB.appDelegate

#### Defined in

[server/ServerComponent.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L18)

___

### cache

• `get` **cache**(): [`CacheManager`](cachemanager.md)

#### Returns

[`CacheManager`](cachemanager.md)

#### Inherited from

ModelsDatastoreDB.cache

#### Defined in

[server/ServerComponent.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L17)

___

### configuration

• `get` **configuration**(): `any`

#### Returns

`any`

#### Inherited from

ModelsDatastoreDB.configuration

#### Defined in

[server/ServerComponent.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L14)

___

### cron

• `get` **cron**(): [`Cron`](cron.md)

#### Returns

[`Cron`](cron.md)

#### Inherited from

ModelsDatastoreDB.cron

#### Defined in

[server/ServerComponent.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L16)

___

### dataStore

• `get` **dataStore**(): `any`

#### Returns

`any`

#### Inherited from

ModelsDatastoreDB.dataStore

#### Defined in

[server/ServerComponent.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L20)

___

### definitions

• `get` **definitions**(): `any`

#### Returns

`any`

#### Inherited from

ModelsDatastoreDB.definitions

#### Defined in

[server/ServerComponent.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L21)

___

### engine

• `get` **engine**(): [`IEngine`](../interfaces/iengine.md)

#### Returns

[`IEngine`](../interfaces/iengine.md)

#### Inherited from

ModelsDatastoreDB.engine

#### Defined in

[server/ServerComponent.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L19)

___

### listener

• `get` **listener**(): `any`

#### Returns

`any`

#### Inherited from

ModelsDatastoreDB.listener

#### Defined in

[server/ServerComponent.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L22)

___

### logger

• `get` **logger**(): `any`

#### Returns

`any`

#### Inherited from

ModelsDatastoreDB.logger

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

#### Overrides

[ModelsDatastoreDB](modelsdatastoredb.md).[deleteModel](modelsdatastoredb.md#deletemodel)

#### Defined in

[datastore/ModelsDatastore.ts:100](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastore.ts#L100)

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

#### Inherited from

[ModelsDatastoreDB](modelsdatastoredb.md).[export](modelsdatastoredb.md#export)

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

#### Inherited from

[ModelsDatastoreDB](modelsdatastoredb.md).[findEvents](modelsdatastoredb.md#findevents)

#### Defined in

[datastore/ModelsDatastoreDB.ts:97](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L97)

___

### getList

▸ **getList**(`query?`): `Promise`\<`string`[]\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `query` | `any` | `null` |

#### Returns

`Promise`\<`string`[]\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[getList](../interfaces/imodelsdatastore.md#getlist)

#### Overrides

[ModelsDatastoreDB](modelsdatastoredb.md).[getList](modelsdatastoredb.md#getlist)

#### Defined in

[datastore/ModelsDatastore.ts:30](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastore.ts#L30)

___

### getSVG

▸ **getSVG**(`name`, `owner?`): `Promise`\<`string`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `name` | `any` | `undefined` |
| `owner` | `any` | `null` |

#### Returns

`Promise`\<`string`\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[getSVG](../interfaces/imodelsdatastore.md#getsvg)

#### Overrides

[ModelsDatastoreDB](modelsdatastoredb.md).[getSVG](modelsdatastoredb.md#getsvg)

#### Defined in

[datastore/ModelsDatastore.ts:84](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastore.ts#L84)

___

### getSource

▸ **getSource**(`name`, `owner?`): `Promise`\<`string`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `name` | `any` | `undefined` |
| `owner` | `any` | `null` |

#### Returns

`Promise`\<`string`\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[getSource](../interfaces/imodelsdatastore.md#getsource)

#### Overrides

[ModelsDatastoreDB](modelsdatastoredb.md).[getSource](modelsdatastoredb.md#getsource)

#### Defined in

[datastore/ModelsDatastore.ts:79](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastore.ts#L79)

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

#### Overrides

[ModelsDatastoreDB](modelsdatastoredb.md).[import](modelsdatastoredb.md#import)

#### Defined in

[datastore/ModelsDatastore.ts:25](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastore.ts#L25)

___

### install

▸ **install**(): `Promise`\<`any`\>

first time installation of DB

creates a new collection and add an index

#### Returns

`Promise`\<`any`\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[install](../interfaces/imodelsdatastore.md#install)

#### Inherited from

[ModelsDatastoreDB](modelsdatastoredb.md).[install](modelsdatastoredb.md#install)

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

#### Overrides

[ModelsDatastoreDB](modelsdatastoredb.md).[load](modelsdatastoredb.md#load)

#### Defined in

[datastore/ModelsDatastore.ts:49](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastore.ts#L49)

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

#### Inherited from

[ModelsDatastoreDB](modelsdatastoredb.md).[loadModel](modelsdatastoredb.md#loadmodel)

#### Defined in

[datastore/ModelsDatastoreDB.ts:68](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L68)

___

### rebuild

▸ **rebuild**(`model?`): `Promise`\<`void`\>

reconstruct the models database from files

use when modifying the files manually or importing new environment

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `model` | `any` | `null` |

#### Returns

`Promise`\<`void`\>

#### Overrides

[ModelsDatastoreDB](modelsdatastoredb.md).[rebuild](modelsdatastoredb.md#rebuild)

#### Defined in

[datastore/ModelsDatastore.ts:128](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastore.ts#L128)

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

#### Overrides

[ModelsDatastoreDB](modelsdatastoredb.md).[renameModel](modelsdatastoredb.md#renamemodel)

#### Defined in

[datastore/ModelsDatastore.ts:110](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastore.ts#L110)

___

### save

▸ **save**(`name`, `bpmn`, `svg?`, `owner?`): `Promise`\<`boolean`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `name` | `any` | `undefined` |
| `bpmn` | `any` | `undefined` |
| `svg?` | `any` | `undefined` |
| `owner` | `any` | `null` |

#### Returns

`Promise`\<`boolean`\>

#### Implementation of

[IModelsDatastore](../interfaces/imodelsdatastore.md).[save](../interfaces/imodelsdatastore.md#save)

#### Overrides

[ModelsDatastoreDB](modelsdatastoredb.md).[save](modelsdatastoredb.md#save)

#### Defined in

[datastore/ModelsDatastore.ts:88](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastore.ts#L88)

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

#### Inherited from

[ModelsDatastoreDB](modelsdatastoredb.md).[saveModel](modelsdatastoredb.md#savemodel)

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

#### Inherited from

[ModelsDatastoreDB](modelsdatastoredb.md).[updateTimer](modelsdatastoredb.md#updatetimer)

#### Defined in

[datastore/ModelsDatastoreDB.ts:164](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/datastore/ModelsDatastoreDB.ts#L164)
