[bpmn-server](../README.md) / Token

# Class: Token

## Implements

- [`IToken`](../interfaces/itoken.md)

## Table of contents

### Constructors

- [constructor](token.md#constructor)

### Properties

- [currentNode](token.md#currentnode)
- [dataPath](token.md#datapath)
- [execution](token.md#execution)
- [id](token.md#id)
- [input](token.md#input)
- [loop](token.md#loop)
- [messageMatchingKey](token.md#messagematchingkey)
- [originItem](token.md#originitem)
- [output](token.md#output)
- [parentToken](token.md#parenttoken)
- [path](token.md#path)
- [processId](token.md#processid)
- [startNodeId](token.md#startnodeid)
- [status](token.md#status)
- [type](token.md#type)

### Accessors

- [childrenTokens](token.md#childrentokens)
- [currentItem](token.md#currentitem)
- [data](token.md#data)
- [firstItem](token.md#firstitem)
- [lastItem](token.md#lastitem)

### Methods

- [appendData](token.md#appenddata)
- [continue](token.md#continue)
- [end](token.md#end)
- [error](token.md#error)
- [execute](token.md#execute)
- [getChildrenTokens](token.md#getchildrentokens)
- [getFullPath](token.md#getfullpath)
- [getSubProcessToken](token.md#getsubprocesstoken)
- [goNext](token.md#gonext)
- [hasNode](token.md#hasnode)
- [log](token.md#log)
- [preExecute](token.md#preexecute)
- [preNext](token.md#prenext)
- [processError](token.md#processerror)
- [processEscalation](token.md#processescalation)
- [restored](token.md#restored)
- [resume](token.md#resume)
- [save](token.md#save)
- [setCurrentNode](token.md#setcurrentnode)
- [signal](token.md#signal)
- [stop](token.md#stop)
- [terminate](token.md#terminate)
- [load](token.md#load)
- [startNewToken](token.md#startnewtoken)

## Constructors

### constructor

• **new Token**(`type`, `execution`, `startNode`, `dataPath?`, `parentToken?`, `originItem?`): [`Token`](token.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | [`TOKEN_TYPE`](../enums/token_type.md) |
| `execution` | [`Execution`](execution.md) |
| `startNode` | [`Node`](node.md) |
| `dataPath?` | `any` |
| `parentToken?` | [`Token`](token.md) |
| `originItem?` | [`Item`](item.md) |

#### Returns

[`Token`](token.md)

#### Defined in

[engine/Token.ts:115](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L115)

## Properties

### currentNode

• **currentNode**: [`Node`](node.md)

#### Implementation of

[IToken](../interfaces/itoken.md).[currentNode](../interfaces/itoken.md#currentnode)

#### Defined in

[engine/Token.ts:68](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L68)

___

### dataPath

• **dataPath**: `string`

#### Implementation of

[IToken](../interfaces/itoken.md).[dataPath](../interfaces/itoken.md#datapath)

#### Defined in

[engine/Token.ts:61](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L61)

___

### execution

• **execution**: [`IExecution`](../interfaces/iexecution.md)

#### Implementation of

[IToken](../interfaces/itoken.md).[execution](../interfaces/itoken.md#execution)

#### Defined in

[engine/Token.ts:60](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L60)

___

### id

• **id**: `any`

#### Implementation of

[IToken](../interfaces/itoken.md).[id](../interfaces/itoken.md#id)

#### Defined in

[engine/Token.ts:58](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L58)

___

### input

• **input**: `Object`

#### Defined in

[engine/Token.ts:71](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L71)

___

### loop

• **loop**: [`Loop`](loop.md)

#### Implementation of

[IToken](../interfaces/itoken.md).[loop](../interfaces/itoken.md#loop)

#### Defined in

[engine/Token.ts:67](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L67)

___

### messageMatchingKey

• **messageMatchingKey**: `Object`

#### Defined in

[engine/Token.ts:73](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L73)

___

### originItem

• **originItem**: [`Item`](item.md)

#### Implementation of

[IToken](../interfaces/itoken.md).[originItem](../interfaces/itoken.md#originitem)

#### Defined in

[engine/Token.ts:65](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L65)

___

### output

• **output**: `Object`

#### Defined in

[engine/Token.ts:72](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L72)

___

### parentToken

• `Optional` **parentToken**: [`Token`](token.md)

#### Implementation of

[IToken](../interfaces/itoken.md).[parentToken](../interfaces/itoken.md#parenttoken)

#### Defined in

[engine/Token.ts:63](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L63)

___

### path

• **path**: [`Item`](item.md)[]

#### Implementation of

[IToken](../interfaces/itoken.md).[path](../interfaces/itoken.md#path)

#### Defined in

[engine/Token.ts:66](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L66)

___

### processId

• **processId**: `any`

#### Implementation of

[IToken](../interfaces/itoken.md).[processId](../interfaces/itoken.md#processid)

#### Defined in

[engine/Token.ts:69](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L69)

___

### startNodeId

• **startNodeId**: `any`

#### Implementation of

[IToken](../interfaces/itoken.md).[startNodeId](../interfaces/itoken.md#startnodeid)

#### Defined in

[engine/Token.ts:62](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L62)

___

### status

• **status**: [`TOKEN_STATUS`](../enums/token_status.md)

#### Implementation of

[IToken](../interfaces/itoken.md).[status](../interfaces/itoken.md#status)

#### Defined in

[engine/Token.ts:70](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L70)

___

### type

• **type**: [`TOKEN_TYPE`](../enums/token_type.md)

#### Implementation of

[IToken](../interfaces/itoken.md).[type](../interfaces/itoken.md#type)

#### Defined in

[engine/Token.ts:59](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L59)

## Accessors

### childrenTokens

• `get` **childrenTokens**(): [`Token`](token.md)[]

#### Returns

[`Token`](token.md)[]

#### Implementation of

[IToken](../interfaces/itoken.md).[childrenTokens](../interfaces/itoken.md#childrentokens)

#### Defined in

[engine/Token.ts:103](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L103)

___

### currentItem

• `get` **currentItem**(): [`Item`](item.md)

#### Returns

[`Item`](item.md)

#### Implementation of

[IToken](../interfaces/itoken.md).[currentItem](../interfaces/itoken.md#currentitem)

#### Defined in

[engine/Token.ts:78](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L78)

___

### data

• `get` **data**(): `any`

#### Returns

`any`

#### Implementation of

[IToken](../interfaces/itoken.md).[data](../interfaces/itoken.md#data)

#### Defined in

[engine/Token.ts:75](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L75)

___

### firstItem

• `get` **firstItem**(): [`Item`](item.md)

#### Returns

[`Item`](item.md)

#### Implementation of

[IToken](../interfaces/itoken.md).[firstItem](../interfaces/itoken.md#firstitem)

#### Defined in

[engine/Token.ts:81](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L81)

___

### lastItem

• `get` **lastItem**(): [`Item`](item.md)

#### Returns

[`Item`](item.md)

#### Implementation of

[IToken](../interfaces/itoken.md).[lastItem](../interfaces/itoken.md#lastitem)

#### Defined in

[engine/Token.ts:93](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L93)

## Methods

### appendData

▸ **appendData**(`inputData`, `item`): `void`

renamed from applyInput to appendData

#### Parameters

| Name | Type |
| :------ | :------ |
| `inputData` | `any` |
| `item` | `any` |

#### Returns

`void`

#### Implementation of

[IToken](../interfaces/itoken.md).[appendData](../interfaces/itoken.md#appenddata)

#### Defined in

[engine/Token.ts:358](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L358)

___

### continue

▸ **continue**(): `Promise`\<`void`\>

is called by events to cancel current token

#### Returns

`Promise`\<`void`\>

#### Defined in

[engine/Token.ts:375](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L375)

___

### end

▸ **end**(`cancel?`): `Promise`\<`void`\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `cancel` | `Boolean` | `false` |

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IToken](../interfaces/itoken.md).[end](../interfaces/itoken.md#end)

#### Defined in

[engine/Token.ts:416](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L416)

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

[IToken](../interfaces/itoken.md).[error](../interfaces/itoken.md#error)

#### Defined in

[engine/Token.ts:526](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L526)

___

### execute

▸ **execute**(`input`): `Promise`\<`void`\>

this is the primary exectuion method for a token
Pre-Conditions:
     currentNode is set 
     status!= end

#### Parameters

| Name | Type |
| :------ | :------ |
| `input` | `any` |

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IToken](../interfaces/itoken.md).[execute](../interfaces/itoken.md#execute)

#### Defined in

[engine/Token.ts:238](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L238)

___

### getChildrenTokens

▸ **getChildrenTokens**(): `any`[]

#### Returns

`any`[]

#### Implementation of

[IToken](../interfaces/itoken.md).[getChildrenTokens](../interfaces/itoken.md#getchildrentokens)

#### Defined in

[engine/Token.ts:208](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L208)

___

### getFullPath

▸ **getFullPath**(`path?`): [`Item`](item.md)[]

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `path` | `any`[] | `[]` |

#### Returns

[`Item`](item.md)[]

#### Implementation of

[IToken](../interfaces/itoken.md).[getFullPath](../interfaces/itoken.md#getfullpath)

#### Defined in

[engine/Token.ts:109](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L109)

___

### getSubProcessToken

▸ **getSubProcessToken**(): [`Token`](token.md)

#### Returns

[`Token`](token.md)

#### Implementation of

[IToken](../interfaces/itoken.md).[getSubProcessToken](../interfaces/itoken.md#getsubprocesstoken)

#### Defined in

[engine/Token.ts:199](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L199)

___

### goNext

▸ **goNext**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IToken](../interfaces/itoken.md).[goNext](../interfaces/itoken.md#gonext)

#### Defined in

[engine/Token.ts:454](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L454)

___

### hasNode

▸ **hasNode**(`nodeId`): `Boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `nodeId` | `any` |

#### Returns

`Boolean`

#### Defined in

[engine/Token.ts:85](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L85)

___

### log

▸ **log**(`msg`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `msg` | `any` |

#### Returns

`void`

#### Implementation of

[IToken](../interfaces/itoken.md).[log](../interfaces/itoken.md#log)

#### Defined in

[engine/Token.ts:523](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L523)

___

### preExecute

▸ **preExecute**(): `Promise`\<`boolean`\>

#### Returns

`Promise`\<`boolean`\>

#### Implementation of

[IToken](../interfaces/itoken.md).[preExecute](../interfaces/itoken.md#preexecute)

#### Defined in

[engine/Token.ts:220](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L220)

___

### preNext

▸ **preNext**(): `Promise`\<`boolean`\>

#### Returns

`Promise`\<`boolean`\>

#### Implementation of

[IToken](../interfaces/itoken.md).[preNext](../interfaces/itoken.md#prenext)

#### Defined in

[engine/Token.ts:227](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L227)

___

### processError

▸ **processError**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IToken](../interfaces/itoken.md).[processError](../interfaces/itoken.md#processerror)

#### Defined in

[engine/Token.ts:300](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L300)

___

### processEscalation

▸ **processEscalation**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

#### Defined in

[engine/Token.ts:330](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L330)

___

### restored

▸ **restored**(): `void`

#### Returns

`void`

#### Implementation of

[IToken](../interfaces/itoken.md).[restored](../interfaces/itoken.md#restored)

#### Defined in

[engine/Token.ts:194](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L194)

___

### resume

▸ **resume**(): `void`

#### Returns

`void`

#### Implementation of

[IToken](../interfaces/itoken.md).[resume](../interfaces/itoken.md#resume)

#### Defined in

[engine/Token.ts:190](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L190)

___

### save

▸ **save**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `currentNode` | `any` |
| `dataPath` | `string` |
| `id` | `any` |
| `loopId` | `any` |
| `originItem` | `any` |
| `parentToken` | `any` |
| `startNodeId` | `any` |
| `status` | [`TOKEN_STATUS`](../enums/token_status.md) |
| `type` | [`TOKEN_TYPE`](../enums/token_type.md) |

#### Implementation of

[IToken](../interfaces/itoken.md).[save](../interfaces/itoken.md#save)

#### Defined in

[engine/Token.ts:153](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L153)

___

### setCurrentNode

▸ **setCurrentNode**(`newCurrentNode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `newCurrentNode` | [`Node`](node.md) |

#### Returns

`void`

#### Defined in

[engine/Token.ts:444](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L444)

___

### signal

▸ **signal**(`data`, `options?`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |
| `options` | `Object` |

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IToken](../interfaces/itoken.md).[signal](../interfaces/itoken.md#signal)

#### Defined in

[engine/Token.ts:384](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L384)

___

### stop

▸ **stop**(): `void`

#### Returns

`void`

#### Implementation of

[IToken](../interfaces/itoken.md).[stop](../interfaces/itoken.md#stop)

#### Defined in

[engine/Token.ts:181](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L181)

___

### terminate

▸ **terminate**(): `Promise`\<`void`\>

is called by Gateways to cancel current token

#### Returns

`Promise`\<`void`\>

#### Implementation of

[IToken](../interfaces/itoken.md).[terminate](../interfaces/itoken.md#terminate)

#### Defined in

[engine/Token.ts:365](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L365)

___

### load

▸ **load**(`execution`, `da`): [`Token`](token.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `execution` | [`Execution`](execution.md) |
| `da` | `any` |

#### Returns

[`Token`](token.md)

#### Defined in

[engine/Token.ts:168](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L168)

___

### startNewToken

▸ **startNewToken**(`type`, `execution`, `startNode`, `dataPath`, `parentToken`, `originItem`, `loop`, `data?`, `noExecute?`): `Promise`\<[`Token`](token.md)\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `type` | [`TOKEN_TYPE`](../enums/token_type.md) | `undefined` |
| `execution` | `any` | `undefined` |
| `startNode` | `any` | `undefined` |
| `dataPath` | `any` | `undefined` |
| `parentToken` | [`Token`](token.md) | `undefined` |
| `originItem` | [`Item`](item.md) | `undefined` |
| `loop` | [`Loop`](loop.md) | `undefined` |
| `data` | `any` | `null` |
| `noExecute` | `boolean` | `false` |

#### Returns

`Promise`\<[`Token`](token.md)\>

#### Defined in

[engine/Token.ts:141](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/engine/Token.ts#L141)
