[bpmn-server](../README.md) / Definition

# Class: Definition

## Implements

- [`IDefinition`](../interfaces/idefinition.md)

## Table of contents

### Constructors

- [constructor](definition.md#constructor)

### Properties

- [accessRules](definition.md#accessrules)
- [flows](definition.md#flows)
- [logger](definition.md#logger)
- [moddle](definition.md#moddle)
- [name](definition.md#name)
- [nodes](definition.md#nodes)
- [processes](definition.md#processes)
- [rootElements](definition.md#rootelements)
- [server](definition.md#server)
- [source](definition.md#source)

### Methods

- [getDefinition](definition.md#getdefinition)
- [getFields](definition.md#getfields)
- [getJson](definition.md#getjson)
- [getNodeById](definition.md#getnodebyid)
- [getStartNode](definition.md#getstartnode)
- [getStartNodes](definition.md#getstartnodes)
- [load](definition.md#load)
- [loadProcess](definition.md#loadprocess)

## Constructors

### constructor

• **new Definition**(`name`, `source`, `server`): [`Definition`](definition.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `source` | `string` |
| `server` | [`BPMNServer`](bpmnserver.md) |

#### Returns

[`Definition`](definition.md)

#### Defined in

[elements/Definition.ts:34](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L34)

## Properties

### accessRules

• **accessRules**: `any`[] = `[]`

#### Implementation of

[IDefinition](../interfaces/idefinition.md).[accessRules](../interfaces/idefinition.md#accessrules)

#### Defined in

[elements/Definition.ts:33](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L33)

___

### flows

• **flows**: `any`[] = `[]`

#### Implementation of

[IDefinition](../interfaces/idefinition.md).[flows](../interfaces/idefinition.md#flows)

#### Defined in

[elements/Definition.ts:28](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L28)

___

### logger

• **logger**: `any`

#### Implementation of

[IDefinition](../interfaces/idefinition.md).[logger](../interfaces/idefinition.md#logger)

#### Defined in

[elements/Definition.ts:30](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L30)

___

### moddle

• **moddle**: `any`

#### Defined in

[elements/Definition.ts:32](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L32)

___

### name

• **name**: `any`

#### Implementation of

[IDefinition](../interfaces/idefinition.md).[name](../interfaces/idefinition.md#name)

#### Defined in

[elements/Definition.ts:24](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L24)

___

### nodes

• **nodes**: `Map`\<`any`, `any`\>

#### Implementation of

[IDefinition](../interfaces/idefinition.md).[nodes](../interfaces/idefinition.md#nodes)

#### Defined in

[elements/Definition.ts:27](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L27)

___

### processes

• **processes**: `Map`\<`any`, `any`\>

#### Implementation of

[IDefinition](../interfaces/idefinition.md).[processes](../interfaces/idefinition.md#processes)

#### Defined in

[elements/Definition.ts:25](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L25)

___

### rootElements

• **rootElements**: `any`

#### Implementation of

[IDefinition](../interfaces/idefinition.md).[rootElements](../interfaces/idefinition.md#rootelements)

#### Defined in

[elements/Definition.ts:26](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L26)

___

### server

• **server**: `any`

#### Defined in

[elements/Definition.ts:31](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L31)

___

### source

• **source**: `any`

#### Implementation of

[IDefinition](../interfaces/idefinition.md).[source](../interfaces/idefinition.md#source)

#### Defined in

[elements/Definition.ts:29](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L29)

## Methods

### getDefinition

▸ **getDefinition**(`source`, `logger`): `Promise`\<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `source` | `any` |
| `logger` | `any` |

#### Returns

`Promise`\<`any`\>

#### Implementation of

[IDefinition](../interfaces/idefinition.md).[getDefinition](../interfaces/idefinition.md#getdefinition)

#### Defined in

[elements/Definition.ts:297](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L297)

___

### getFields

▸ **getFields**(`elementId`): `Promise`\<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `elementId` | `any` |

#### Returns

`Promise`\<`any`\>

#### Defined in

[elements/Definition.ts:310](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L310)

___

### getJson

▸ **getJson**(): `string`

#### Returns

`string`

#### Implementation of

[IDefinition](../interfaces/idefinition.md).[getJson](../interfaces/idefinition.md#getjson)

#### Defined in

[elements/Definition.ts:275](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L275)

___

### getNodeById

▸ **getNodeById**(`id`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `any` |

#### Returns

`any`

#### Implementation of

[IDefinition](../interfaces/idefinition.md).[getNodeById](../interfaces/idefinition.md#getnodebyid)

#### Defined in

[elements/Definition.ts:335](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L335)

___

### getStartNode

▸ **getStartNode**(): `any`

#### Returns

`any`

#### Implementation of

[IDefinition](../interfaces/idefinition.md).[getStartNode](../interfaces/idefinition.md#getstartnode)

#### Defined in

[elements/Definition.ts:332](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L332)

___

### getStartNodes

▸ **getStartNodes**(`userInvokable?`): `any`[]

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `userInvokable` | `boolean` | `false` |

#### Returns

`any`[]

#### Defined in

[elements/Definition.ts:321](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L321)

___

### load

▸ **load**(): `Promise`\<`any`\>

#### Returns

`Promise`\<`any`\>

#### Implementation of

[IDefinition](../interfaces/idefinition.md).[load](../interfaces/idefinition.md#load)

#### Defined in

[elements/Definition.ts:134](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L134)

___

### loadProcess

▸ **loadProcess**(`definition`, `processElement`, `parentProcess`): [`Process`](process.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `definition` | `any` |
| `processElement` | `any` |
| `parentProcess` | `any` |

#### Returns

[`Process`](process.md)

#### Defined in

[elements/Definition.ts:44](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/elements/Definition.ts#L44)
