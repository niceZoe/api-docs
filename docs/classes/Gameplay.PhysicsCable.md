[Gameplay](../modules/Gameplay.Gameplay.md) / PhysicsCable

# PhysicsCable <Badge type="tip" text="Class" />

**`Description`**

物理绳组件

## Hierarchy

- [`PhysicsConstraintBase`](Gameplay.PhysicsConstraintBase.md)

  ↳ **`PhysicsCable`**

## Table of contents

| Accessors |
| :-----|
| **[collisionEnable](Gameplay.PhysicsCable.md#collisionenable)**(): `boolean` <br> 获取禁用碰撞|
| **[currentLength](Gameplay.PhysicsCable.md#currentlength)**(): `number` <br> 获取绳子当前长度|
| **[maxLength](Gameplay.PhysicsCable.md#maxlength)**(): `number` <br> 获取绳子最大长度|

| Methods |
| :-----|

## Accessors

### collisionEnable

• `get` **collisionEnable**(): `boolean`

**`Description`**

获取禁用碰撞

#### Returns

`boolean`

是否禁用碰撞

• `set` **collisionEnable**(`value`): `void`

**`Description`**

设置禁用碰撞

**`Effect`**

自动同步

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | `boolean` | 是否禁用碰撞 |

#### Returns

`void`


### currentLength

• `get` **currentLength**(): `number`

**`Description`**

获取绳子当前长度

#### Returns

`number`

当前长度


### maxLength

• `get` **maxLength**(): `number`

**`Description`**

获取绳子最大长度

#### Returns

`number`

最大长度

• `set` **maxLength**(`value`): `void`

**`Description`**

设置绳子最大长度

**`Effect`**

自动同步

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | `number` | 最大长度 |

#### Returns

`void`


## Methods