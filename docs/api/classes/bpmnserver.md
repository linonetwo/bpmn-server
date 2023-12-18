[bpmn-server](../README.md) / BPMNServer

# Class: BPMNServer

The main class of Server Layer
	provides the full functionalities:
	
		at start of the app:
			new BPMNServer(configuration,options);
			
		after that point:
		
			BPMNServer.engine.start(...)
			BPMNServer.engine.invoke(...)
			BPMNServer.dataStore.findInstances(...)
			BPMNServer.dataStore.findItems(...)

## Implements

- [`IBPMNServer`](../interfaces/ibpmnserver.md)

## Table of contents

### Constructors

- [constructor](bpmnserver.md#constructor)

### Properties

- [appDelegate](bpmnserver.md#appdelegate)
- [cache](bpmnserver.md#cache)
- [configuration](bpmnserver.md#configuration)
- [cron](bpmnserver.md#cron)
- [dataStore](bpmnserver.md#datastore)
- [definitions](bpmnserver.md#definitions)
- [engine](bpmnserver.md#engine)
- [error](bpmnserver.md#error)
- [listener](bpmnserver.md#listener)
- [logger](bpmnserver.md#logger)
- [userService](bpmnserver.md#userservice)

### Accessors

- [engine](bpmnserver.md#engine-1)

### Methods

- [getInstance](bpmnserver.md#getinstance)
- [getVersion](bpmnserver.md#getversion)

## Constructors

### constructor

• **new BPMNServer**(`configuration`, `logger?`, `options?`): [`BPMNServer`](bpmnserver.md)

Server Constructor

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `configuration` | [`IConfiguration`](../interfaces/iconfiguration.md) | see |
| `logger?` | [`ILogger`](../interfaces/ilogger.md) |  |
| `options` | `Object` | - |

#### Returns

[`BPMNServer`](bpmnserver.md)

#### Defined in

[server/BPMNServer.ts:64](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/BPMNServer.ts#L64)

## Properties

### appDelegate

• **appDelegate**: [`IAppDelegate`](../interfaces/iappdelegate.md)

#### Implementation of

[IBPMNServer](../interfaces/ibpmnserver.md).[appDelegate](../interfaces/ibpmnserver.md#appdelegate)

#### Defined in

[server/BPMNServer.ts:48](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/BPMNServer.ts#L48)

___

### cache

• **cache**: [`ICacheManager`](../interfaces/icachemanager.md)

#### Implementation of

[IBPMNServer](../interfaces/ibpmnserver.md).[cache](../interfaces/ibpmnserver.md#cache)

#### Defined in

[server/BPMNServer.ts:50](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/BPMNServer.ts#L50)

___

### configuration

• **configuration**: [`IConfiguration`](../interfaces/iconfiguration.md)

#### Implementation of

[IBPMNServer](../interfaces/ibpmnserver.md).[configuration](../interfaces/ibpmnserver.md#configuration)

#### Defined in

[server/BPMNServer.ts:45](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/BPMNServer.ts#L45)

___

### cron

• **cron**: [`Cron`](cron.md)

#### Implementation of

[IBPMNServer](../interfaces/ibpmnserver.md).[cron](../interfaces/ibpmnserver.md#cron)

#### Defined in

[server/BPMNServer.ts:51](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/BPMNServer.ts#L51)

___

### dataStore

• **dataStore**: [`IDataStore`](../interfaces/idatastore.md)

#### Implementation of

[IBPMNServer](../interfaces/ibpmnserver.md).[dataStore](../interfaces/ibpmnserver.md#datastore)

#### Defined in

[server/BPMNServer.ts:49](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/BPMNServer.ts#L49)

___

### definitions

• **definitions**: `any`

#### Implementation of

[IBPMNServer](../interfaces/ibpmnserver.md).[definitions](../interfaces/ibpmnserver.md#definitions)

#### Defined in

[server/BPMNServer.ts:47](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/BPMNServer.ts#L47)

___

### engine

• **engine**: [`Engine`](engine.md)

#### Implementation of

[IBPMNServer](../interfaces/ibpmnserver.md).[engine](../interfaces/ibpmnserver.md#engine)

#### Defined in

[server/BPMNServer.ts:43](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/BPMNServer.ts#L43)

___

### error

• **error**: `any`

#### Defined in

[server/BPMNServer.ts:53](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/BPMNServer.ts#L53)

___

### listener

• **listener**: `EventEmitter`

#### Implementation of

[IBPMNServer](../interfaces/ibpmnserver.md).[listener](../interfaces/ibpmnserver.md#listener)

#### Defined in

[server/BPMNServer.ts:44](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/BPMNServer.ts#L44)

___

### logger

• **logger**: [`ILogger`](../interfaces/ilogger.md)

#### Implementation of

[IBPMNServer](../interfaces/ibpmnserver.md).[logger](../interfaces/ibpmnserver.md#logger)

#### Defined in

[server/BPMNServer.ts:46](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/BPMNServer.ts#L46)

___

### userService

• **userService**: [`IUserService`](../interfaces/iuserservice.md)

#### Implementation of

[IBPMNServer](../interfaces/ibpmnserver.md).[userService](../interfaces/ibpmnserver.md#userservice)

#### Defined in

[server/BPMNServer.ts:52](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/BPMNServer.ts#L52)

## Accessors

### engine

• `get` **engine**(): [`Engine`](engine.md)

#### Returns

[`Engine`](engine.md)

#### Defined in

[server/BPMNServer.ts:110](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/BPMNServer.ts#L110)

## Methods

### getInstance

▸ **getInstance**(): [`BPMNServer`](bpmnserver.md)

#### Returns

[`BPMNServer`](bpmnserver.md)

#### Defined in

[server/BPMNServer.ts:113](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/BPMNServer.ts#L113)

___

### getVersion

▸ **getVersion**(): `any`

#### Returns

`any`

#### Defined in

[server/BPMNServer.ts:95](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/BPMNServer.ts#L95)
