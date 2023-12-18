[bpmn-server](../README.md) / ISecureUser

# Interface: ISecureUser

## Hierarchy

- [`IUserInfo`](iuserinfo.md)

  ↳ **`ISecureUser`**

## Implemented by

- [`SecureUser`](../classes/secureuser.md)

## Table of contents

### Properties

- [modelsOwner](isecureuser.md#modelsowner)
- [tenantId](isecureuser.md#tenantid)
- [userGroups](isecureuser.md#usergroups)
- [userName](isecureuser.md#username)

### Methods

- [canAssign](isecureuser.md#canassign)
- [canDeleteModel](isecureuser.md#candeletemodel)
- [canInvoke](isecureuser.md#caninvoke)
- [canModifyModel](isecureuser.md#canmodifymodel)
- [canStart](isecureuser.md#canstart)
- [inGroup](isecureuser.md#ingroup)
- [isAdmin](isecureuser.md#isadmin)
- [isSystem](isecureuser.md#issystem)
- [qualifyDeleteInstances](isecureuser.md#qualifydeleteinstances)
- [qualifyInstances](isecureuser.md#qualifyinstances)
- [qualifyItems](isecureuser.md#qualifyitems)
- [qualifyModels](isecureuser.md#qualifymodels)
- [qualifyStartEvents](isecureuser.md#qualifystartevents)
- [qualifyViewItems](isecureuser.md#qualifyviewitems)

## Properties

### modelsOwner

• `Optional` **modelsOwner**: `string`

#### Inherited from

[IUserInfo](iuserinfo.md).[modelsOwner](iuserinfo.md#modelsowner)

#### Defined in

[interfaces/User.ts:6](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L6)

___

### tenantId

• `Optional` **tenantId**: `string`

#### Inherited from

[IUserInfo](iuserinfo.md).[tenantId](iuserinfo.md#tenantid)

#### Defined in

[interfaces/User.ts:5](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L5)

___

### userGroups

• **userGroups**: `string`[]

#### Inherited from

[IUserInfo](iuserinfo.md).[userGroups](iuserinfo.md#usergroups)

#### Defined in

[interfaces/User.ts:4](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L4)

___

### userName

• **userName**: `string`

#### Inherited from

[IUserInfo](iuserinfo.md).[userName](iuserinfo.md#username)

#### Defined in

[interfaces/User.ts:3](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L3)

## Methods

### canAssign

▸ **canAssign**(`item`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |

#### Returns

`any`

#### Defined in

[interfaces/User.ts:58](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L58)

___

### canDeleteModel

▸ **canDeleteModel**(`name`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `any` |

#### Returns

`any`

#### Defined in

[interfaces/User.ts:50](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L50)

___

### canInvoke

▸ **canInvoke**(`item`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |

#### Returns

`any`

#### Defined in

[interfaces/User.ts:57](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L57)

___

### canModifyModel

▸ **canModifyModel**(`name`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `any` |

#### Returns

`any`

#### Defined in

[interfaces/User.ts:47](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L47)

___

### canStart

▸ **canStart**(`name`, `startNodeId`, `user`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `any` |
| `startNodeId` | `any` |
| `user` | `any` |

#### Returns

`any`

#### Defined in

[interfaces/User.ts:59](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L59)

___

### inGroup

▸ **inGroup**(`userGroup`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `userGroup` | `any` |

#### Returns

`boolean`

#### Defined in

[interfaces/User.ts:12](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L12)

___

### isAdmin

▸ **isAdmin**(): `boolean`

#### Returns

`boolean`

#### Defined in

[interfaces/User.ts:10](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L10)

___

### isSystem

▸ **isSystem**(): `boolean`

#### Returns

`boolean`

#### Defined in

[interfaces/User.ts:11](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L11)

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

#### Defined in

[interfaces/User.ts:38](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L38)

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

#### Defined in

[interfaces/User.ts:18](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L18)

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

#### Defined in

[interfaces/User.ts:25](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L25)

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

#### Defined in

[interfaces/User.ts:44](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L44)

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

#### Defined in

[interfaces/User.ts:32](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L32)

___

### qualifyViewItems

▸ **qualifyViewItems**(`query`): `any`

alters the query adding conditions based on security rules

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | `any` |

#### Returns

`any`

query

#### Defined in

[interfaces/User.ts:56](https://github.com/bpmnServer/bpmn-server/blob/b56411b/src/interfaces/User.ts#L56)
