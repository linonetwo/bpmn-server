[bpmn-server](../README.md) / NoCacheManager

# Class: NoCacheManager

super class for various objects that are part of the server

## Hierarchy

- [`ServerComponent`](servercomponent.md)

  ↳ **`NoCacheManager`**

## Implements

- [`ICacheManager`](../interfaces/icachemanager.md)

## Table of contents

### Constructors

- [constructor](nocachemanager.md#constructor)

### Properties

- [server](nocachemanager.md#server)

### Accessors

- [appDelegate](nocachemanager.md#appdelegate)
- [cache](nocachemanager.md#cache)
- [configuration](nocachemanager.md#configuration)
- [cron](nocachemanager.md#cron)
- [dataStore](nocachemanager.md#datastore)
- [definitions](nocachemanager.md#definitions)
- [engine](nocachemanager.md#engine)
- [listener](nocachemanager.md#listener)
- [logger](nocachemanager.md#logger)

### Methods

- [add](nocachemanager.md#add)
- [getInstance](nocachemanager.md#getinstance)
- [list](nocachemanager.md#list)
- [remove](nocachemanager.md#remove)
- [restart](nocachemanager.md#restart)
- [shutdown](nocachemanager.md#shutdown)

## Constructors

### constructor

• **new NoCacheManager**(`server`): [`NoCacheManager`](nocachemanager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | `any` |

#### Returns

[`NoCacheManager`](nocachemanager.md)

#### Overrides

[ServerComponent](servercomponent.md).[constructor](servercomponent.md#constructor)

#### Defined in

[server/CacheManager.ts:13](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/CacheManager.ts#L13)

## Properties

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

### add

▸ **add**(`execution`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `execution` | [`IExecution`](../interfaces/iexecution.md) |

#### Returns

`any`

#### Implementation of

[ICacheManager](../interfaces/icachemanager.md).[add](../interfaces/icachemanager.md#add)

#### Defined in

[server/CacheManager.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/CacheManager.ts#L22)

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

[server/CacheManager.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/CacheManager.ts#L20)

___

### list

▸ **list**(): `any`[]

#### Returns

`any`[]

#### Implementation of

[ICacheManager](../interfaces/icachemanager.md).[list](../interfaces/icachemanager.md#list)

#### Defined in

[server/CacheManager.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/CacheManager.ts#L17)

___

### remove

▸ **remove**(`instanceId`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `instanceId` | `any` |

#### Returns

`any`

#### Implementation of

[ICacheManager](../interfaces/icachemanager.md).[remove](../interfaces/icachemanager.md#remove)

#### Defined in

[server/CacheManager.ts:23](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/CacheManager.ts#L23)

___

### restart

▸ **restart**(): `void`

#### Returns

`void`

#### Defined in

[server/CacheManager.ts:26](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/CacheManager.ts#L26)

___

### shutdown

▸ **shutdown**(): `void`

#### Returns

`void`

#### Implementation of

[ICacheManager](../interfaces/icachemanager.md).[shutdown](../interfaces/icachemanager.md#shutdown)

#### Defined in

[server/CacheManager.ts:25](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/CacheManager.ts#L25)
