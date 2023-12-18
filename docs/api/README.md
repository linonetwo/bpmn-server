bpmn-server

# bpmn-server

## Table of contents

### Enumerations

- [BPMN\_TYPE](enums/bpmn_type.md)
- [EXECUTION\_EVENT](enums/execution_event.md)
- [EXECUTION\_STATUS](enums/execution_status.md)
- [FLOW\_ACTION](enums/flow_action.md)
- [ITEM\_STATUS](enums/item_status.md)
- [NODE\_ACTION](enums/node_action.md)
- [NODE\_SUBTYPE](enums/node_subtype.md)
- [TOKEN\_STATUS](enums/token_status.md)
- [TOKEN\_TYPE](enums/token_type.md)
- [USER\_ROLE](enums/USER_ROLE.md)

### Classes

- [APIData](classes/apidata.md)
- [APIEngine](classes/apiengine.md)
- [APIModel](classes/apimodel.md)
- [BPMNAPI](classes/bpmnapi.md)
- [BPMNServer](classes/bpmnserver.md)
- [Behaviour](classes/behaviour.md)
- [BehaviourLoader](classes/behaviourloader.md)
- [BoundaryEvent](classes/boundaryevent.md)
- [BpmnModelData](classes/bpmnmodeldata.md)
- [BusinessRuleTask](classes/businessruletask.md)
- [CacheManager](classes/cachemanager.md)
- [CallActivity](classes/callactivity.md)
- [CamundaFormData](classes/camundaformdata.md)
- [CatchEvent](classes/catchevent.md)
- [Configuration](classes/configuration.md)
- [Cron](classes/cron.md)
- [DataStore](classes/datastore.md)
- [DefaultAppDelegate](classes/defaultappdelegate.md)
- [Definition](classes/definition.md)
- [Element](classes/element.md)
- [EndEvent](classes/endevent.md)
- [Engine](classes/engine.md)
- [Event](classes/event.md)
- [EventBasedGateway](classes/eventbasedgateway.md)
- [EventData](classes/eventdata.md)
- [Execution](classes/execution.md)
- [Flow](classes/flow.md)
- [Gateway](classes/gateway.md)
- [IOBehaviour](classes/iobehaviour.md)
- [InstanceLocker](classes/instancelocker.md)
- [InstanceObject](classes/instanceobject.md)
- [Item](classes/item.md)
- [ItemObject](classes/itemobject.md)
- [Logger](classes/logger.md)
- [Loop](classes/loop.md)
- [LoopBehaviour](classes/loopbehaviour.md)
- [LoopObject](classes/loopobject.md)
- [MessageEventBehaviour](classes/messageeventbehaviour.md)
- [MessageFlow](classes/messageflow.md)
- [ModelsDatastore](classes/modelsdatastore.md)
- [ModelsDatastoreDB](classes/modelsdatastoredb.md)
- [MongoDB](classes/mongodb.md)
- [NoCacheManager](classes/nocachemanager.md)
- [Node](classes/node.md)
- [NodeLoader](classes/nodeloader.md)
- [Process](classes/process.md)
- [ProcessData](classes/processdata.md)
- [Query](classes/query.md)
- [ReceiveTask](classes/receivetask.md)
- [ScriptBehaviour](classes/scriptbehaviour.md)
- [ScriptHandler](classes/scripthandler.md)
- [ScriptTask](classes/scripttask.md)
- [SecureUser](classes/secureuser.md)
- [SendTask](classes/sendtask.md)
- [ServerComponent](classes/servercomponent.md)
- [ServiceTask](classes/servicetask.md)
- [SignalEventBehaviour](classes/signaleventbehaviour.md)
- [StartEvent](classes/startevent.md)
- [SubProcess](classes/subprocess.md)
- [TerminateBehaviour](classes/terminatebehaviour.md)
- [ThrowEvent](classes/throwevent.md)
- [TimerBehaviour](classes/timerbehaviour.md)
- [Token](classes/token.md)
- [TokenObject](classes/tokenobject.md)
- [Transaction](classes/transaction.md)
- [UserTask](classes/usertask.md)
- [XORGateway](classes/xorgateway.md)

### Interfaces

- [IAppDelegate](interfaces/iappdelegate.md)
- [IBPMNServer](interfaces/ibpmnserver.md)
- [IBehaviour](interfaces/ibehaviour.md)
- [IBpmnModelData](interfaces/ibpmnmodeldata.md)
- [ICacheManager](interfaces/icachemanager.md)
- [IConfiguration](interfaces/iconfiguration.md)
- [ICron](interfaces/icron.md)
- [IDataStore](interfaces/idatastore.md)
- [IDefinition](interfaces/idefinition.md)
- [IDefinitionData](interfaces/idefinitiondata.md)
- [IElement](interfaces/ielement.md)
- [IElementData](interfaces/ielementdata.md)
- [IEngine](interfaces/iengine.md)
- [IEventData](interfaces/ieventdata.md)
- [IExecution](interfaces/iexecution.md)
- [IFlow](interfaces/iflow.md)
- [IFlowData](interfaces/iflowdata.md)
- [IInstanceData](interfaces/iinstancedata.md)
- [IItem](interfaces/iitem.md)
- [IItemData](interfaces/iitemdata.md)
- [ILogger](interfaces/ilogger.md)
- [IModelsDatastore](interfaces/imodelsdatastore.md)
- [INode](interfaces/inode.md)
- [IProcessData](interfaces/iprocessdata.md)
- [ISecureUser](interfaces/isecureuser.md)
- [IServerComponent](interfaces/iservercomponent.md)
- [IToken](interfaces/itoken.md)
- [IUserInfo](interfaces/iuserinfo.md)
- [IUserService](interfaces/iuserservice.md)

### Variables

- [Behaviour\_names](README.md#behaviour_names)
- [SystemUser](README.md#systemuser)
- [defaultConfiguration](README.md#defaultconfiguration)
- [docsFolder](README.md#docsfolder)

### Functions

- [dateDiff](README.md#datediff)

## Variables

### Behaviour\_names

• `Const` **Behaviour\_names**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `CamundaFormData` | `string` |
| `CamundaIO` | `string` |
| `CamundaScript` | `string` |
| `CamundaScript2` | `string` |
| `CamundaScript3` | `string` |
| `CancelEventDefinition` | `string` |
| `CompensateEventDefinition` | `string` |
| `ErrorEventDefinition` | `string` |
| `EscalationEventDefinition` | `string` |
| `IOSpecification` | `string` |
| `LoopCharacteristics` | `string` |
| `MessageEventDefinition` | `string` |
| `SignalEventDefinition` | `string` |
| `TerminateEventDefinition` | `string` |
| `TimerEventDefinition` | `string` |

#### Defined in

[elements/behaviours/BehaviourLoader.ts:16](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/behaviours/BehaviourLoader.ts#L16)

___

### SystemUser

• `Const` **SystemUser**: [`SecureUser`](classes/secureuser.md)

#### Defined in

[API/SecureUser.ts:227](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L227)

___

### defaultConfiguration

• **defaultConfiguration**: [`Configuration`](classes/configuration.md)

#### Defined in

[common/DefaultConfiguration.ts:59](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/DefaultConfiguration.ts#L59)

___

### docsFolder

• `Const` **docsFolder**: `string`

#### Defined in

[index.ts:9](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/index.ts#L9)

## Functions

### dateDiff

▸ **dateDiff**(`dateStr`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `dateStr` | `any` |

#### Returns

`string`

#### Defined in

[common/timer.ts:4](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/common/timer.ts#L4)
