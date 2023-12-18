[bpmn-server](../README.md) / Configuration

# Class: Configuration

## Implements

- [`IConfiguration`](../interfaces/iconfiguration.md)

## Table of contents

### Constructors

- [constructor](configuration.md#constructor)

### Properties

- [apiKey](configuration.md#apikey)
- [database](configuration.md#database)
- [definitionsPath](configuration.md#definitionspath)
- [logger](configuration.md#logger)
- [sendGridAPIKey](configuration.md#sendgridapikey)
- [templatesPath](configuration.md#templatespath)
- [timers](configuration.md#timers)

### Methods

- [appDelegate](configuration.md#appdelegate)
- [cacheManager](configuration.md#cachemanager)
- [dataStore](configuration.md#datastore)
- [definitions](configuration.md#definitions)
- [userService](configuration.md#userservice)

## Constructors

### constructor

• **new Configuration**(`«destructured»`): [`Configuration`](configuration.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `«destructured»` | `Object` |
| › `apiKey` | `any` |
| › `appDelegate` | `any` |
| › `cacheManager` | `any` |
| › `dataStore` | `any` |
| › `database` | `any` |
| › `definitions` | `any` |
| › `definitionsPath` | `any` |
| › `logger` | `any` |
| › `templatesPath` | `any` |
| › `timers` | `any` |
| › `userService` | `any` |

#### Returns

[`Configuration`](configuration.md)

#### Defined in

[common/DefaultConfiguration.ts:39](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/DefaultConfiguration.ts#L39)

## Properties

### apiKey

• **apiKey**: `string`

#### Implementation of

[IConfiguration](../interfaces/iconfiguration.md).[apiKey](../interfaces/iconfiguration.md#apikey)

#### Defined in

[common/DefaultConfiguration.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/DefaultConfiguration.ts#L20)

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

#### Implementation of

[IConfiguration](../interfaces/iconfiguration.md).[database](../interfaces/iconfiguration.md#database)

#### Defined in

[common/DefaultConfiguration.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/DefaultConfiguration.ts#L15)

___

### definitionsPath

• **definitionsPath**: `string`

#### Implementation of

[IConfiguration](../interfaces/iconfiguration.md).[definitionsPath](../interfaces/iconfiguration.md#definitionspath)

#### Defined in

[common/DefaultConfiguration.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/DefaultConfiguration.ts#L12)

___

### logger

• **logger**: [`ILogger`](../interfaces/ilogger.md)

#### Implementation of

[IConfiguration](../interfaces/iconfiguration.md).[logger](../interfaces/iconfiguration.md#logger)

#### Defined in

[common/DefaultConfiguration.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/DefaultConfiguration.ts#L19)

___

### sendGridAPIKey

• **sendGridAPIKey**: `string`

#### Defined in

[common/DefaultConfiguration.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/DefaultConfiguration.ts#L21)

___

### templatesPath

• **templatesPath**: `string`

#### Implementation of

[IConfiguration](../interfaces/iconfiguration.md).[templatesPath](../interfaces/iconfiguration.md#templatespath)

#### Defined in

[common/DefaultConfiguration.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/DefaultConfiguration.ts#L13)

___

### timers

• **timers**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `forceTimersDelay` | `number` |
| `precision` | `number` |

#### Implementation of

[IConfiguration](../interfaces/iconfiguration.md).[timers](../interfaces/iconfiguration.md#timers)

#### Defined in

[common/DefaultConfiguration.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/DefaultConfiguration.ts#L14)

## Methods

### appDelegate

▸ **appDelegate**(`server`): [`IAppDelegate`](../interfaces/iappdelegate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | `any` |

#### Returns

[`IAppDelegate`](../interfaces/iappdelegate.md)

#### Implementation of

[IConfiguration](../interfaces/iconfiguration.md).[appDelegate](../interfaces/iconfiguration.md#appdelegate)

#### Defined in

[common/DefaultConfiguration.ts:25](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/DefaultConfiguration.ts#L25)

___

### cacheManager

▸ **cacheManager**(`server`): [`NoCacheManager`](nocachemanager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | `any` |

#### Returns

[`NoCacheManager`](nocachemanager.md)

#### Implementation of

[IConfiguration](../interfaces/iconfiguration.md).[cacheManager](../interfaces/iconfiguration.md#cachemanager)

#### Defined in

[common/DefaultConfiguration.ts:31](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/DefaultConfiguration.ts#L31)

___

### dataStore

▸ **dataStore**(`server`): [`DataStore`](datastore.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | `any` |

#### Returns

[`DataStore`](datastore.md)

#### Implementation of

[IConfiguration](../interfaces/iconfiguration.md).[dataStore](../interfaces/iconfiguration.md#datastore)

#### Defined in

[common/DefaultConfiguration.ts:28](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/DefaultConfiguration.ts#L28)

___

### definitions

▸ **definitions**(`server`): [`ModelsDatastore`](modelsdatastore.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | `any` |

#### Returns

[`ModelsDatastore`](modelsdatastore.md)

#### Implementation of

[IConfiguration](../interfaces/iconfiguration.md).[definitions](../interfaces/iconfiguration.md#definitions)

#### Defined in

[common/DefaultConfiguration.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/DefaultConfiguration.ts#L22)

___

### userService

▸ **userService**(`server`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | `any` |

#### Returns

`any`

#### Implementation of

[IConfiguration](../interfaces/iconfiguration.md).[userService](../interfaces/iconfiguration.md#userservice)

#### Defined in

[common/DefaultConfiguration.ts:34](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/DefaultConfiguration.ts#L34)
