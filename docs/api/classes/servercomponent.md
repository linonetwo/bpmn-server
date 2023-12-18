[bpmn-server](../README.md) / ServerComponent

# Class: ServerComponent

super class for various objects that are part of the server

## Hierarchy

- **`ServerComponent`**

  ↳ [`Execution`](execution.md)

  ↳ [`Cron`](cron.md)

  ↳ [`CacheManager`](cachemanager.md)

  ↳ [`NoCacheManager`](nocachemanager.md)

  ↳ [`Engine`](engine.md)

  ↳ [`DataStore`](datastore.md)

  ↳ [`ModelsDatastoreDB`](modelsdatastoredb.md)

## Table of contents

### Constructors

- [constructor](servercomponent.md#constructor)

### Properties

- [server](servercomponent.md#server)

### Accessors

- [appDelegate](servercomponent.md#appdelegate)
- [cache](servercomponent.md#cache)
- [configuration](servercomponent.md#configuration)
- [cron](servercomponent.md#cron)
- [dataStore](servercomponent.md#datastore)
- [definitions](servercomponent.md#definitions)
- [engine](servercomponent.md#engine)
- [listener](servercomponent.md#listener)
- [logger](servercomponent.md#logger)

## Constructors

### constructor

• **new ServerComponent**(`server`): [`ServerComponent`](servercomponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | [`IBPMNServer`](../interfaces/ibpmnserver.md) |

#### Returns

[`ServerComponent`](servercomponent.md)

#### Defined in

[server/ServerComponent.ts:10](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L10)

## Properties

### server

• **server**: `any`

#### Defined in

[server/ServerComponent.ts:9](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L9)

## Accessors

### appDelegate

• `get` **appDelegate**(): `any`

#### Returns

`any`

#### Defined in

[server/ServerComponent.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L18)

___

### cache

• `get` **cache**(): [`CacheManager`](cachemanager.md)

#### Returns

[`CacheManager`](cachemanager.md)

#### Defined in

[server/ServerComponent.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L17)

___

### configuration

• `get` **configuration**(): `any`

#### Returns

`any`

#### Defined in

[server/ServerComponent.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L14)

___

### cron

• `get` **cron**(): [`Cron`](cron.md)

#### Returns

[`Cron`](cron.md)

#### Defined in

[server/ServerComponent.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L16)

___

### dataStore

• `get` **dataStore**(): `any`

#### Returns

`any`

#### Defined in

[server/ServerComponent.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L20)

___

### definitions

• `get` **definitions**(): `any`

#### Returns

`any`

#### Defined in

[server/ServerComponent.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L21)

___

### engine

• `get` **engine**(): [`IEngine`](../interfaces/iengine.md)

#### Returns

[`IEngine`](../interfaces/iengine.md)

#### Defined in

[server/ServerComponent.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L19)

___

### listener

• `get` **listener**(): `any`

#### Returns

`any`

#### Defined in

[server/ServerComponent.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L22)

___

### logger

• `get` **logger**(): `any`

#### Returns

`any`

#### Defined in

[server/ServerComponent.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L15)
