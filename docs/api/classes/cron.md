[bpmn-server](../README.md) / Cron

# Class: Cron

super class for various objects that are part of the server

## Hierarchy

- [`ServerComponent`](servercomponent.md)

  ↳ **`Cron`**

## Implements

- [`ICron`](../interfaces/ICron.md)

## Table of contents

### Constructors

- [constructor](Cron.md#constructor)

### Properties

- [server](Cron.md#server)

### Accessors

- [appDelegate](Cron.md#appdelegate)
- [cache](Cron.md#cache)
- [configuration](Cron.md#configuration)
- [cron](Cron.md#cron)
- [dataStore](Cron.md#datastore)
- [definitions](Cron.md#definitions)
- [engine](Cron.md#engine)
- [listener](Cron.md#listener)
- [logger](Cron.md#logger)

### Methods

- [checkTimers](Cron.md#checktimers)
- [start](Cron.md#start)
- [startTimers](Cron.md#starttimers)
- [checkCron](Cron.md#checkcron)
- [timeDue](Cron.md#timedue)
- [timerEnded](Cron.md#timerended)
- [timerScheduled](Cron.md#timerscheduled)

## Constructors

### constructor

• **new Cron**(`server`): [`Cron`](Cron.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | [`IBPMNServer`](../interfaces/ibpmnserver.md) |

#### Returns

[`Cron`](Cron.md)

#### Inherited from

[ServerComponent](servercomponent.md).[constructor](servercomponent.md#constructor)

#### Defined in

[server/ServerComponent.ts:10](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L10)

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

• `get` **cache**(): [`CacheManager`](CacheManager.md)

#### Returns

[`CacheManager`](CacheManager.md)

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

• `get` **cron**(): [`Cron`](Cron.md)

#### Returns

[`Cron`](Cron.md)

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

• `get` **engine**(): [`IEngine`](../interfaces/IEngine.md)

#### Returns

[`IEngine`](../interfaces/IEngine.md)

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

### checkTimers

▸ **checkTimers**(`duration?`): `Promise`\<`void`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `duration` | `number` | `0` |

#### Returns

`Promise`\<`void`\>

#### Implementation of

[ICron](../interfaces/ICron.md).[checkTimers](../interfaces/ICron.md#checktimers)

#### Defined in

[server/Cron.ts:26](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/Cron.ts#L26)

___

### start

▸ **start**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

#### Implementation of

[ICron](../interfaces/ICron.md).[start](../interfaces/ICron.md#start)

#### Defined in

[server/Cron.ts:29](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/Cron.ts#L29)

___

### startTimers

▸ **startTimers**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

#### Implementation of

[ICron](../interfaces/ICron.md).[startTimers](../interfaces/ICron.md#starttimers)

#### Defined in

[server/Cron.ts:32](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/Cron.ts#L32)

___

### checkCron

▸ **checkCron**(`expression`, `referenceDateTime`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `expression` | `any` |
| `referenceDateTime` | `any` |

#### Returns

`number`

#### Defined in

[server/Cron.ts:128](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/Cron.ts#L128)

___

### timeDue

▸ **timeDue**(`expression`, `referenceDateTime`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `expression` | `any` |
| `referenceDateTime` | `any` |

#### Returns

`any`

#### Defined in

[server/Cron.ts:147](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/Cron.ts#L147)

___

### timerEnded

▸ **timerEnded**(`item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |

#### Returns

`void`

#### Defined in

[server/Cron.ts:22](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/Cron.ts#L22)

___

### timerScheduled

▸ **timerScheduled**(`timeDue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `timeDue` | `any` |

#### Returns

`void`

#### Defined in

[server/Cron.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/Cron.ts#L19)
