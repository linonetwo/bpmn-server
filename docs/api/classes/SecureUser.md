[bpmn-server](../README.md) / SecureUser

# Class: SecureUser

## Implements

- [`ISecureUser`](../interfaces/isecureuser.md)

## Table of contents

### Constructors

- [constructor](secureuser.md#constructor)

### Properties

- [modelsOwner](secureuser.md#modelsowner)
- [tenantId](secureuser.md#tenantid)
- [userGroups](secureuser.md#usergroups)
- [userName](secureuser.md#username)

### Methods

- [canAssign](secureuser.md#canassign)
- [canDeleteModel](secureuser.md#candeletemodel)
- [canInvoke](secureuser.md#caninvoke)
- [canModifyModel](secureuser.md#canmodifymodel)
- [canStart](secureuser.md#canstart)
- [inGroup](secureuser.md#ingroup)
- [isAdmin](secureuser.md#isadmin)
- [isSystem](secureuser.md#issystem)
- [qualifyDeleteInstances](secureuser.md#qualifydeleteinstances)
- [qualifyInstances](secureuser.md#qualifyinstances)
- [qualifyItems](secureuser.md#qualifyitems)
- [qualifyModels](secureuser.md#qualifymodels)
- [qualifyStartEvents](secureuser.md#qualifystartevents)
- [qualifyViewItems](secureuser.md#qualifyviewitems)
- [SystemUser](secureuser.md#systemuser)

## Constructors

### constructor

• **new SecureUser**(`params`): [`SecureUser`](secureuser.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `params` | [`IUserInfo`](../interfaces/iuserinfo.md) |

#### Returns

[`SecureUser`](secureuser.md)

#### Defined in

[API/SecureUser.ts:37](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L37)

## Properties

### modelsOwner

• `Optional` **modelsOwner**: `any`

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[modelsOwner](../interfaces/isecureuser.md#modelsowner)

#### Defined in

[API/SecureUser.ts:36](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L36)

___

### tenantId

• `Optional` **tenantId**: `any`

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[tenantId](../interfaces/isecureuser.md#tenantid)

#### Defined in

[API/SecureUser.ts:35](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L35)

___

### userGroups

• **userGroups**: `any`

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[userGroups](../interfaces/isecureuser.md#usergroups)

#### Defined in

[API/SecureUser.ts:34](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L34)

___

### userName

• **userName**: `any`

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[userName](../interfaces/isecureuser.md#username)

#### Defined in

[API/SecureUser.ts:33](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L33)

## Methods

### canAssign

▸ **canAssign**(`item`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |

#### Returns

`boolean`

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[canAssign](../interfaces/isecureuser.md#canassign)

#### Defined in

[API/SecureUser.ts:198](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L198)

___

### canDeleteModel

▸ **canDeleteModel**(`name`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `any` |

#### Returns

`boolean`

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[canDeleteModel](../interfaces/isecureuser.md#candeletemodel)

#### Defined in

[API/SecureUser.ts:175](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L175)

___

### canInvoke

▸ **canInvoke**(`item`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |

#### Returns

`boolean`

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[canInvoke](../interfaces/isecureuser.md#caninvoke)

#### Defined in

[API/SecureUser.ts:189](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L189)

___

### canModifyModel

▸ **canModifyModel**(`name`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `any` |

#### Returns

`boolean`

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[canModifyModel](../interfaces/isecureuser.md#canmodifymodel)

#### Defined in

[API/SecureUser.ts:167](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L167)

___

### canStart

▸ **canStart**(`name`, `startNodeId`, `user`): `Promise`\<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `any` |
| `startNodeId` | `any` |
| `user` | `any` |

#### Returns

`Promise`\<`void`\>

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[canStart](../interfaces/isecureuser.md#canstart)

#### Defined in

[API/SecureUser.ts:225](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L225)

___

### inGroup

▸ **inGroup**(`userGroup`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `userGroup` | `any` |

#### Returns

`boolean`

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[inGroup](../interfaces/isecureuser.md#ingroup)

#### Defined in

[API/SecureUser.ts:63](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L63)

___

### isAdmin

▸ **isAdmin**(): `boolean`

#### Returns

`boolean`

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[isAdmin](../interfaces/isecureuser.md#isadmin)

#### Defined in

[API/SecureUser.ts:53](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L53)

___

### isSystem

▸ **isSystem**(): `boolean`

#### Returns

`boolean`

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[isSystem](../interfaces/isecureuser.md#issystem)

#### Defined in

[API/SecureUser.ts:58](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L58)

___

### qualifyDeleteInstances

▸ **qualifyDeleteInstances**(`query`): `any`

alters the query adding conditions based on security rules

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | `any` |

#### Returns

`any`

query

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[qualifyDeleteInstances](../interfaces/isecureuser.md#qualifydeleteinstances)

#### Defined in

[API/SecureUser.ts:146](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L146)

___

### qualifyInstances

▸ **qualifyInstances**(`query`): `any`

alters the query adding conditions based on security rules

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | `any` |

#### Returns

`any`

query

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[qualifyInstances](../interfaces/isecureuser.md#qualifyinstances)

#### Defined in

[API/SecureUser.ts:73](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L73)

___

### qualifyItems

▸ **qualifyItems**(`query`): `any`

alters the query adding conditions based on security rules

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | `any` |

#### Returns

`any`

query

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[qualifyItems](../interfaces/isecureuser.md#qualifyitems)

#### Defined in

[API/SecureUser.ts:112](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L112)

___

### qualifyModels

▸ **qualifyModels**(`query`): `any`

alters the query adding conditions based on security rules

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | `any` |

#### Returns

`any`

query

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[qualifyModels](../interfaces/isecureuser.md#qualifymodels)

#### Defined in

[API/SecureUser.ts:157](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L157)

___

### qualifyStartEvents

▸ **qualifyStartEvents**(`query`): `any`

alters the query adding conditions based on security rules

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | `any` |

#### Returns

`any`

query

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[qualifyStartEvents](../interfaces/isecureuser.md#qualifystartevents)

#### Defined in

[API/SecureUser.ts:124](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L124)

___

### qualifyViewItems

▸ **qualifyViewItems**(`query`): `Promise`\<`void`\>

alters the query adding conditions based on security rules

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | `any` |

#### Returns

`Promise`\<`void`\>

query

#### Implementation of

[ISecureUser](../interfaces/isecureuser.md).[qualifyViewItems](../interfaces/isecureuser.md#qualifyviewitems)

#### Defined in

[API/SecureUser.ts:186](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L186)

___

### SystemUser

▸ **SystemUser**(): [`SecureUser`](secureuser.md)

#### Returns

[`SecureUser`](secureuser.md)

#### Defined in

[API/SecureUser.ts:50](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/API/SecureUser.ts#L50)
