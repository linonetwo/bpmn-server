[bpmn-server](../README.md) / Execution

# Class: Execution

is accessed two ways:
     execute - start process
     signal  - invoke a node (userTask, event, etc.)

## Hierarchy

- [`ServerComponent`](servercomponent.md)

  ↳ **`Execution`**

## Implements

- [`IExecution`](../interfaces/iexecution.md)

## Table of contents

### Constructors

- [constructor](execution.md#constructor)

### Properties

- [definition](execution.md#definition)
- [errors](execution.md#errors)
- [instance](execution.md#instance)
- [isLocked](execution.md#islocked)
- [item](execution.md#item)
- [messageMatchingKey](execution.md#messagematchingkey)
- [operation](execution.md#operation)
- [options](execution.md#options)
- [process](execution.md#process)
- [promises](execution.md#promises)
- [server](execution.md#server)
- [servicesProvider](execution.md#servicesprovider)
- [tokens](execution.md#tokens)
- [uids](execution.md#uids)
- [userName](execution.md#username)
- [worker](execution.md#worker)

### Accessors

- [appDelegate](execution.md#appdelegate)
- [cache](execution.md#cache)
- [configuration](execution.md#configuration)
- [cron](execution.md#cron)
- [dataStore](execution.md#datastore)
- [definitions](execution.md#definitions)
- [engine](execution.md#engine)
- [execution](execution.md#execution)
- [id](execution.md#id)
- [listener](execution.md#listener)
- [logger](execution.md#logger)
- [name](execution.md#name)
- [status](execution.md#status)

### Methods

- [addHistory](execution.md#addhistory)
- [appendData](execution.md#appenddata)
- [assign](execution.md#assign)
- [doExecutionEvent](execution.md#doexecutionevent)
- [doItemEvent](execution.md#doitemevent)
- [end](execution.md#end)
- [error](execution.md#error)
- [execute](execution.md#execute)
- [getAndCreateData](execution.md#getandcreatedata)
- [getData](execution.md#getdata)
- [getItems](execution.md#getitems)
- [getItemsData](execution.md#getitemsdata)
- [getNewId](execution.md#getnewid)
- [getNodeById](execution.md#getnodebyid)
- [getState](execution.md#getstate)
- [getToken](execution.md#gettoken)
- [getUUID](execution.md#getuuid)
- [log](execution.md#log)
- [report](execution.md#report)
- [restored](execution.md#restored)
- [resume](execution.md#resume)
- [save](execution.md#save)
- [signalEvent](execution.md#signalevent)
- [signalItem](execution.md#signalitem)
- [signalRepeatTimerEvent](execution.md#signalrepeattimerevent)
- [stop](execution.md#stop)
- [terminate](execution.md#terminate)
- [tillDone](execution.md#tilldone)
- [tokenEnded](execution.md#tokenended)
- [restore](execution.md#restore)

## Constructors

### constructor

• **new Execution**(`server`, `name`, `source`, `state?`): [`Execution`](execution.md)

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `server` | `any` | `undefined` | - |
| `name` | `string` | `undefined` | process name |
| `source` | `any` | `undefined` | bpmn source |
| `state` | `any` | `null` | - |

#### Returns

[`Execution`](execution.md)

#### Overrides

[ServerComponent](servercomponent.md).[constructor](servercomponent.md#constructor)

#### Defined in

[engine/Execution.ts:62](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L62)

## Properties

### definition

• **definition**: [`IDefinition`](../interfaces/idefinition.md)

#### Implementation of

[IExecution](../interfaces/iexecution.md).[definition](../interfaces/iexecution.md#definition)

#### Defined in

[engine/Execution.ts:28](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L28)

___

### errors

• **errors**: `any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[errors](../interfaces/iexecution.md#errors)

#### Defined in

[engine/Execution.ts:30](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L30)

___

### instance

• **instance**: [`InstanceObject`](instanceobject.md)

#### Implementation of

[IExecution](../interfaces/iexecution.md).[instance](../interfaces/iexecution.md#instance)

#### Defined in

[engine/Execution.ts:26](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L26)

___

### isLocked

• **isLocked**: `boolean` = `false`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[isLocked](../interfaces/iexecution.md#islocked)

#### Defined in

[engine/Execution.ts:37](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L37)

___

### item

• **item**: `any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[item](../interfaces/iexecution.md#item)

#### Defined in

[engine/Execution.ts:31](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L31)

___

### messageMatchingKey

• **messageMatchingKey**: `any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[messageMatchingKey](../interfaces/iexecution.md#messagematchingkey)

#### Defined in

[engine/Execution.ts:32](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L32)

___

### operation

• **operation**: `any`

#### Defined in

[engine/Execution.ts:39](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L39)

___

### options

• **options**: `any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[options](../interfaces/iexecution.md#options)

#### Defined in

[engine/Execution.ts:38](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L38)

___

### process

• **process**: [`Process`](process.md)

#### Implementation of

[IExecution](../interfaces/iexecution.md).[process](../interfaces/iexecution.md#process)

#### Defined in

[engine/Execution.ts:29](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L29)

___

### promises

• **promises**: `any`[] = `[]`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[promises](../interfaces/iexecution.md#promises)

#### Defined in

[engine/Execution.ts:35](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L35)

___

### server

• **server**: `any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[server](../interfaces/iexecution.md#server)

#### Inherited from

[ServerComponent](servercomponent.md).[server](servercomponent.md#server)

#### Defined in

[server/ServerComponent.ts:9](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L9)

___

### servicesProvider

• **servicesProvider**: `any`

#### Defined in

[engine/Execution.ts:36](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L36)

___

### tokens

• **tokens**: `Map`\<`any`, `any`\>

#### Implementation of

[IExecution](../interfaces/iexecution.md).[tokens](../interfaces/iexecution.md#tokens)

#### Defined in

[engine/Execution.ts:27](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L27)

___

### uids

• **uids**: `Object` = `{}`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[uids](../interfaces/iexecution.md#uids)

#### Defined in

[engine/Execution.ts:524](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L524)

___

### userName

• **userName**: `any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[userName](../interfaces/iexecution.md#username)

#### Defined in

[engine/Execution.ts:34](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L34)

___

### worker

• **worker**: `any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[worker](../interfaces/iexecution.md#worker)

#### Defined in

[engine/Execution.ts:33](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L33)

## Accessors

### appDelegate

• `get` **appDelegate**(): `any`

#### Returns

`any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[appDelegate](../interfaces/iexecution.md#appdelegate)

#### Inherited from

ServerComponent.appDelegate

#### Defined in

[server/ServerComponent.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L18)

___

### cache

• `get` **cache**(): [`CacheManager`](cachemanager.md)

#### Returns

[`CacheManager`](cachemanager.md)

#### Implementation of

[IExecution](../interfaces/iexecution.md).[cache](../interfaces/iexecution.md#cache)

#### Inherited from

ServerComponent.cache

#### Defined in

[server/ServerComponent.ts:17](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L17)

___

### configuration

• `get` **configuration**(): `any`

#### Returns

`any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[configuration](../interfaces/iexecution.md#configuration)

#### Inherited from

ServerComponent.configuration

#### Defined in

[server/ServerComponent.ts:14](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L14)

___

### cron

• `get` **cron**(): [`Cron`](cron.md)

#### Returns

[`Cron`](cron.md)

#### Implementation of

[IExecution](../interfaces/iexecution.md).[cron](../interfaces/iexecution.md#cron)

#### Inherited from

ServerComponent.cron

#### Defined in

[server/ServerComponent.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L16)

___

### dataStore

• `get` **dataStore**(): `any`

#### Returns

`any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[dataStore](../interfaces/iexecution.md#datastore)

#### Inherited from

ServerComponent.dataStore

#### Defined in

[server/ServerComponent.ts:20](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L20)

___

### definitions

• `get` **definitions**(): `any`

#### Returns

`any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[definitions](../interfaces/iexecution.md#definitions)

#### Inherited from

ServerComponent.definitions

#### Defined in

[server/ServerComponent.ts:21](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L21)

___

### engine

• `get` **engine**(): [`IEngine`](../interfaces/iengine.md)

#### Returns

[`IEngine`](../interfaces/iengine.md)

#### Implementation of

[IExecution](../interfaces/iexecution.md).[engine](../interfaces/iexecution.md#engine)

#### Inherited from

ServerComponent.engine

#### Defined in

[server/ServerComponent.ts:19](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L19)

___

### execution

• `get` **execution**(): `this`

#### Returns

`this`

#### Defined in

[engine/Execution.ts:44](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L44)

___

### id

• `get` **id**(): `any`

#### Returns

`any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[id](../interfaces/iexecution.md#id)

#### Defined in

[engine/Execution.ts:41](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L41)

___

### listener

• `get` **listener**(): `any`

#### Returns

`any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[listener](../interfaces/iexecution.md#listener)

#### Overrides

ServerComponent.listener

#### Defined in

[engine/Execution.ts:52](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L52)

___

### logger

• `get` **logger**(): `any`

#### Returns

`any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[logger](../interfaces/iexecution.md#logger)

#### Inherited from

ServerComponent.logger

#### Defined in

[server/ServerComponent.ts:15](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/server/ServerComponent.ts#L15)

___

### name

• `get` **name**(): `any`

#### Returns

`any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[name](../interfaces/iexecution.md#name)

#### Defined in

[engine/Execution.ts:42](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L42)

___

### status

• `get` **status**(): [`EXECUTION_STATUS`](../enums/execution_status.md)

#### Returns

[`EXECUTION_STATUS`](../enums/execution_status.md)

#### Implementation of

[IExecution](../interfaces/iexecution.md).[status](../interfaces/iexecution.md#status)

#### Defined in

[engine/Execution.ts:43](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L43)

## Methods

### addHistory

▸ **addHistory**(`inputData`, `assignment`, `item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `inputData` | `any` |
| `assignment` | `any` |
| `item` | `any` |

#### Returns

`void`

#### Defined in

[engine/Execution.ts:599](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L599)

___

### appendData

▸ **appendData**(`inputData`, `item`, `dataPath?`, `assignment?`): `void`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `inputData` | `any` | `undefined` |
| `item` | `any` | `undefined` |
| `dataPath` | `any` | `null` |
| `assignment` | `any` | `null` |

#### Returns

`void`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[appendData](../interfaces/iexecution.md#appenddata)

#### Defined in

[engine/Execution.ts:562](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L562)

___

### assign

▸ **assign**(`executionId`, `inputData`, `assignment?`, `userName`, `options?`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `executionId` | `any` |
| `inputData` | `any` |
| `assignment` | `Object` |
| `userName` | `any` |
| `options` | `Object` |

#### Returns

`Promise`\<`void`\>

#### Defined in

[engine/Execution.ts:179](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L179)

___

### doExecutionEvent

▸ **doExecutionEvent**(`process`, `event`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `process` | `any` |
| `event` | `any` |

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IExecution](../interfaces/iexecution.md).[doExecutionEvent](../interfaces/iexecution.md#doexecutionevent)

#### Defined in

[engine/Execution.ts:540](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L540)

___

### doItemEvent

▸ **doItemEvent**(`item`, `event`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |
| `event` | `any` |

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IExecution](../interfaces/iexecution.md).[doItemEvent](../interfaces/iexecution.md#doitemevent)

#### Defined in

[engine/Execution.ts:546](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L546)

___

### end

▸ **end**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IExecution](../interfaces/iexecution.md).[end](../interfaces/iexecution.md#end)

#### Defined in

[engine/Execution.ts:90](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L90)

___

### error

▸ **error**(`msg`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `msg` | `any` |

#### Returns

`void`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[error](../interfaces/iexecution.md#error)

#### Defined in

[engine/Execution.ts:554](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L554)

___

### execute

▸ **execute**(`startNodeId?`, `inputData?`, `options?`): `Promise`\<`void`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `startNodeId` | `any` | `null` |
| `inputData` | `Object` | `{}` |
| `options` | `Object` | `{}` |

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IExecution](../interfaces/iexecution.md).[execute](../interfaces/iexecution.md#execute)

#### Defined in

[engine/Execution.ts:120](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L120)

___

### getAndCreateData

▸ **getAndCreateData**(`dataPath`, `asArray?`): `any`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `dataPath` | `any` | `undefined` |
| `asArray` | `boolean` | `false` |

#### Returns

`any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[getAndCreateData](../interfaces/iexecution.md#getandcreatedata)

#### Defined in

[engine/Execution.ts:630](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L630)

___

### getData

▸ **getData**(`dataPath`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `dataPath` | `any` |

#### Returns

`any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[getData](../interfaces/iexecution.md#getdata)

#### Defined in

[engine/Execution.ts:617](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L617)

___

### getItems

▸ **getItems**(): [`Item`](item.md)[]

#### Returns

[`Item`](item.md)[]

#### Implementation of

[IExecution](../interfaces/iexecution.md).[getItems](../interfaces/iexecution.md#getitems)

#### Defined in

[engine/Execution.ts:376](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L376)

___

### getItemsData

▸ **getItemsData**(): `any`[]

#### Returns

`any`[]

#### Implementation of

[IExecution](../interfaces/iexecution.md).[getItemsData](../interfaces/iexecution.md#getitemsdata)

#### Defined in

[engine/Execution.ts:387](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L387)

___

### getNewId

▸ **getNewId**(`scope`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `scope` | `string` |

#### Returns

`number`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[getNewId](../interfaces/iexecution.md#getnewid)

#### Defined in

[engine/Execution.ts:526](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L526)

___

### getNodeById

▸ **getNodeById**(`id`): [`Node`](node.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `any` |

#### Returns

[`Node`](node.md)

#### Implementation of

[IExecution](../interfaces/iexecution.md).[getNodeById](../interfaces/iexecution.md#getnodebyid)

#### Defined in

[engine/Execution.ts:76](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L76)

___

### getState

▸ **getState**(): [`IInstanceData`](../interfaces/iinstancedata.md)

#### Returns

[`IInstanceData`](../interfaces/iinstancedata.md)

#### Implementation of

[IExecution](../interfaces/iexecution.md).[getState](../interfaces/iexecution.md#getstate)

#### Defined in

[engine/Execution.ts:397](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L397)

___

### getToken

▸ **getToken**(`id`): [`Token`](token.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `number` |

#### Returns

[`Token`](token.md)

#### Implementation of

[IExecution](../interfaces/iexecution.md).[getToken](../interfaces/iexecution.md#gettoken)

#### Defined in

[engine/Execution.ts:79](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L79)

___

### getUUID

▸ **getUUID**(): `any`

#### Returns

`any`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[getUUID](../interfaces/iexecution.md#getuuid)

#### Defined in

[engine/Execution.ts:533](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L533)

___

### log

▸ **log**(`...msg`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...msg` | `any`[] |

#### Returns

`void`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[log](../interfaces/iexecution.md#log)

#### Defined in

[engine/Execution.ts:551](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L551)

___

### report

▸ **report**(): `void`

#### Returns

`void`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[report](../interfaces/iexecution.md#report)

#### Defined in

[engine/Execution.ts:496](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L496)

___

### restored

▸ **restored**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IExecution](../interfaces/iexecution.md).[restored](../interfaces/iexecution.md#restored)

#### Defined in

[engine/Execution.ts:483](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L483)

___

### resume

▸ **resume**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IExecution](../interfaces/iexecution.md).[resume](../interfaces/iexecution.md#resume)

#### Defined in

[engine/Execution.ts:490](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L490)

___

### save

▸ **save**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IExecution](../interfaces/iexecution.md).[save](../interfaces/iexecution.md#save)

#### Defined in

[engine/Execution.ts:363](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L363)

___

### signalEvent

▸ **signalEvent**(`executionId`, `inputData`, `options?`): `Promise`\<[`IExecution`](../interfaces/iexecution.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `executionId` | `any` |
| `inputData` | `any` |
| `options` | `Object` |

#### Returns

`Promise`\<[`IExecution`](../interfaces/iexecution.md)\>

#### Implementation of

[IExecution](../interfaces/iexecution.md).[signalEvent](../interfaces/iexecution.md#signalevent)

#### Defined in

[engine/Execution.ts:258](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L258)

___

### signalItem

▸ **signalItem**(`itemId`, `inputData`, `userName`, `options?`): `Promise`\<[`IExecution`](../interfaces/iexecution.md)\>

invoke scenarios:
     itemId
     elementId   - but only one is active
     elementId   - for a startEvent in a secondary process

#### Parameters

| Name | Type |
| :------ | :------ |
| `itemId` | `any` |
| `inputData` | `any` |
| `userName` | `any` |
| `options` | `Object` |

#### Returns

`Promise`\<[`IExecution`](../interfaces/iexecution.md)\>

#### Implementation of

[IExecution](../interfaces/iexecution.md).[signalItem](../interfaces/iexecution.md#signalitem)

#### Defined in

[engine/Execution.ts:216](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L216)

___

### signalRepeatTimerEvent

▸ **signalRepeatTimerEvent**(`executionId`, `prevItem`, `inputData`, `options?`): `Promise`\<[`IExecution`](../interfaces/iexecution.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `executionId` | `any` |
| `prevItem` | `any` |
| `inputData` | `any` |
| `options` | `Object` |

#### Returns

`Promise`\<[`IExecution`](../interfaces/iexecution.md)\>

#### Implementation of

[IExecution](../interfaces/iexecution.md).[signalRepeatTimerEvent](../interfaces/iexecution.md#signalrepeattimerevent)

#### Defined in

[engine/Execution.ts:333](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L333)

___

### stop

▸ **stop**(): `void`

causes the execution to stop from running any further

#### Returns

`void`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[stop](../interfaces/iexecution.md#stop)

#### Defined in

[engine/Execution.ts:113](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L113)

___

### terminate

▸ **terminate**(): `void`

causes the execution to stop from running any further

#### Returns

`void`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[terminate](../interfaces/iexecution.md#terminate)

#### Defined in

[engine/Execution.ts:103](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L103)

___

### tillDone

▸ **tillDone**(): `Promise`\<[`Execution`](execution.md)\>

#### Returns

`Promise`\<[`Execution`](execution.md)\>

#### Defined in

[engine/Execution.ts:46](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L46)

___

### tokenEnded

▸ **tokenEnded**(`token`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `token` | [`Token`](token.md) |

#### Returns

`void`

#### Implementation of

[IExecution](../interfaces/iexecution.md).[tokenEnded](../interfaces/iexecution.md#tokenended)

#### Defined in

[engine/Execution.ts:82](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L82)

___

### restore

▸ **restore**(`server`, `state`): `Promise`\<[`Execution`](execution.md)\>

re-enstate the execution from db

#### Parameters

| Name | Type |
| :------ | :------ |
| `server` | `any` |
| `state` | [`IInstanceData`](../interfaces/iinstancedata.md) |

#### Returns

`Promise`\<[`Execution`](execution.md)\>

#### Defined in

[engine/Execution.ts:423](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Execution.ts#L423)
