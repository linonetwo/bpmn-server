[bpmn-server](../README.md) / IConfiguration

# Interface: IConfiguration

## Implemented by

- [`Configuration`](../classes/configuration.md)

## Table of contents

### Properties

- [apiKey](iconfiguration.md#apikey)
- [database](iconfiguration.md#database)
- [definitionsPath](iconfiguration.md#definitionspath)
- [logger](iconfiguration.md#logger)
- [templatesPath](iconfiguration.md#templatespath)
- [timers](iconfiguration.md#timers)

### Methods

- [appDelegate](iconfiguration.md#appdelegate)
- [cacheManager](iconfiguration.md#cachemanager)
- [dataStore](iconfiguration.md#datastore)
- [definitions](iconfiguration.md#definitions)
- [userService](iconfiguration.md#userservice)

## Properties

### apiKey

• **apiKey**: `string`

#### Defined in

[interfaces/common.ts:23](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L23)

___

### database

• **database**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `MongoDB` | \{ `db`: `string` ; `db_url`: `string`  } |
| `MongoDB.db` | `string` |
| `MongoDB.db_url` | `string` |
| `loopbackRepositories?` | `any` |

#### Defined in

[interfaces/common.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L15)

___

### definitionsPath

• **definitionsPath**: `string`

#### Defined in

[interfaces/common.ts:9](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L9)

___

### logger

• **logger**: [`ILogger`](ilogger.md)

#### Defined in

[interfaces/common.ts:24](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L24)

___

### templatesPath

• **templatesPath**: `string`

#### Defined in

[interfaces/common.ts:10](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L10)

___

### timers

• **timers**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `forceTimersDelay` | `number` |
| `precision` | `number` |

#### Defined in

[interfaces/common.ts:11](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L11)

## Methods

### appDelegate

▸ **appDelegate**(`server`): [`IAppDelegate`](iappdelegate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | `any` |

#### Returns

[`IAppDelegate`](iappdelegate.md)

#### Defined in

[interfaces/common.ts:26](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L26)

___

### cacheManager

▸ **cacheManager**(`server`): [`ICacheManager`](icachemanager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | `any` |

#### Returns

[`ICacheManager`](icachemanager.md)

#### Defined in

[interfaces/common.ts:28](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L28)

___

### dataStore

▸ **dataStore**(`server`): [`IDataStore`](idatastore.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | `any` |

#### Returns

[`IDataStore`](idatastore.md)

#### Defined in

[interfaces/common.ts:27](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L27)

___

### definitions

▸ **definitions**(`server`): [`IModelsDatastore`](imodelsdatastore.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | `any` |

#### Returns

[`IModelsDatastore`](imodelsdatastore.md)

#### Defined in

[interfaces/common.ts:25](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L25)

___

### userService

▸ **userService**(`server`): [`IUserService`](iuserservice.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | `any` |

#### Returns

[`IUserService`](iuserservice.md)

#### Defined in

[interfaces/common.ts:29](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/common.ts#L29)
