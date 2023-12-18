[bpmn-server](../README.md) / CacheManager

# Class: CacheManager

super class for various objects that are part of the server

## Hierarchy

- [`ServerComponent`](servercomponent.md)

  ↳ **`CacheManager`**

## Implements

- [`ICacheManager`](../interfaces/icachemanager.md)

## Table of contents

### Constructors

- [constructor](cachemanager.md#constructor)

### Properties

- [server](cachemanager.md#server)
- [liveInstances](cachemanager.md#liveinstances)

### Accessors

- [appDelegate](cachemanager.md#appdelegate)
- [cache](cachemanager.md#cache)
- [configuration](cachemanager.md#configuration)
- [cron](cachemanager.md#cron)
- [dataStore](cachemanager.md#datastore)
- [definitions](cachemanager.md#definitions)
- [engine](cachemanager.md#engine)
- [listener](cachemanager.md#listener)
- [logger](cachemanager.md#logger)

### Methods

- [add](cachemanager.md#add)
- [getInstance](cachemanager.md#getinstance)
- [list](cachemanager.md#list)
- [remove](cachemanager.md#remove)
- [shutdown](cachemanager.md#shutdown)

## Constructors

### constructor

• **new CacheManager**(`server`): [`CacheManager`](cachemanager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | `any` |

#### Returns

[`CacheManager`](cachemanager.md)

#### Overrides

[ServerComponent](servercomponent.md).[constructor](servercomponent.md#constructor)

#### Defined in

[server/CacheManager.ts:32](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/CacheManager.ts#L32)

## Properties

### server

• **server**: `any`

#### Inherited from

[ServerComponent](servercomponent.md).[server](servercomponent.md#server)

#### Defined in

[server/ServerComponent.ts:9](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L9)

___

### liveInstances

▪ `Static` **liveInstances**: `Map`\<`any`, `any`\>

#### Defined in

[server/CacheManager.ts:30](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/CacheManager.ts#L30)

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

### add

▸ **add**(`execution`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `execution` | [`IExecution`](../interfaces/iexecution.md) |

#### Returns

`void`

#### Implementation of

[ICacheManager](../interfaces/icachemanager.md).[add](../interfaces/icachemanager.md#add)

#### Defined in

[server/CacheManager.ts:58](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/CacheManager.ts#L58)

___

### getInstance

▸ **getInstance**(`instanceId`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `instanceId` | `any` |

#### Returns

`any`

#### Defined in

[server/CacheManager.ts:52](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/CacheManager.ts#L52)

___

### list

▸ **list**(): `any`[]

#### Returns

`any`[]

#### Implementation of

[ICacheManager](../interfaces/icachemanager.md).[list](../interfaces/icachemanager.md#list)

#### Defined in

[server/CacheManager.ts:44](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/CacheManager.ts#L44)

___

### remove

▸ **remove**(`instanceId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `instanceId` | `any` |

#### Returns

`void`

#### Implementation of

[ICacheManager](../interfaces/icachemanager.md).[remove](../interfaces/icachemanager.md#remove)

#### Defined in

[server/CacheManager.ts:62](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/CacheManager.ts#L62)

___

### shutdown

▸ **shutdown**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

#### Implementation of

[ICacheManager](../interfaces/icachemanager.md).[shutdown](../interfaces/icachemanager.md#shutdown)

#### Defined in

[server/CacheManager.ts:66](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/CacheManager.ts#L66)
