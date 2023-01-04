[Gameplay](../modules/Gameplay.Gameplay.md) / PhysicsPrism

# PhysicsPrism <Badge type="tip" text="Class" />

**`Description`**

物理棱柱组件

## Hierarchy

- [`PhysicsConstraintBase`](Gameplay.PhysicsConstraintBase.md)

  ↳ **`PhysicsPrism`**

## Table of contents

| Accessors |
| :-----|
| **[enable](Gameplay.PhysicsPrism.md#enable)**(): `boolean` <br> 获取激活状态|
| **[linearLimit](Gameplay.PhysicsPrism.md#linearlimit)**(): `number` <br> 获取限制距离|
| **[linearVelocity](Gameplay.PhysicsPrism.md#linearvelocity)**(): [`Vector`](Type.Vector.md) <br> 获取最大速度|
| **[restitution](Gameplay.PhysicsPrism.md#restitution)**(): `number` <br> 获取反弹力|
| **[strength](Gameplay.PhysicsPrism.md#strength)**(): `number` <br> 获取加速度|

| Methods |
| :-----|
| **[getAxisXLinearType](Gameplay.PhysicsPrism.md#getaxisxlineartype)**(): [`LimitType`](../enums/Gameplay.LimitType.md) <br> 获取X轴滑动类型|
| **[getAxisYLinearType](Gameplay.PhysicsPrism.md#getaxisylineartype)**(): [`LimitType`](../enums/Gameplay.LimitType.md) <br> 获取Y轴滑动类型|
| **[getAxisZLinearType](Gameplay.PhysicsPrism.md#getaxiszlineartype)**(): [`LimitType`](../enums/Gameplay.LimitType.md) <br> 获取Z轴滑动类型|
| **[setAxisXLinearType](Gameplay.PhysicsPrism.md#setaxisxlineartype)**([`LimitType`](../enums/Gameplay.LimitType.md)): `void` <br> 设置X轴滑动类型|
| **[setAxisYLinearType](Gameplay.PhysicsPrism.md#setaxisylineartype)**([`LimitType`](../enums/Gameplay.LimitType.md)): `void` <br> 设置Y轴滑动类型|
| **[setAxisZLinearType](Gameplay.PhysicsPrism.md#setaxiszlineartype)**([`LimitType`](../enums/Gameplay.LimitType.md)): `void` <br> 设置Z轴滑动类型|

## Accessors

### enable

• `get` **enable**(): `boolean`

**`Description`**

获取激活状态

#### Returns

`boolean`

激活状态

• `set` **enable**(`EnableState`): `void`

**`Description`**

设置激活状态

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `EnableState` | `boolean` | 激活状态 |

#### Returns

`void`


### linearLimit

• `get` **linearLimit**(): `number`

**`Description`**

获取限制距离

#### Returns

`number`

限制距离

• `set` **linearLimit**(`Limit`): `void`

**`Description`**

设置限制距离

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `Limit` | `number` | 限制距离 |

#### Returns

`void`

___

### linearVelocity

• `get` **linearVelocity**(): [`Vector`](Type.Vector.md)

**`Description`**

获取最大速度

#### Returns

[`Vector`](Type.Vector.md)

最大速度

• `set` **linearVelocity**(`Velocity`): `void`

**`Description`**

设置最大速度

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `Velocity` | [`Vector`](Type.Vector.md) | 最大速度 |

#### Returns

`void`


### restitution

• `get` **restitution**(): `number`

**`Description`**

获取反弹力

#### Returns

`number`

反弹力

• `set` **restitution**(`restitution`): `void`

**`Description`**

设置反弹力

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `restitution` | `number` | 反弹力 |

#### Returns

`void`


### strength

• `get` **strength**(): `number`

**`Description`**

获取加速度

#### Returns

`number`

加速度

• `set` **strength**(`strength`): `void`

**`Description`**

设置加速度

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `strength` | `number` | 加速度 |

#### Returns

`void`


## Methods

### getAxisXLinearType

▸ **getAxisXLinearType**(): [`LimitType`](../enums/Gameplay.LimitType.md)

**`Description`**

获取X轴滑动类型

**`Effect`**

调用端生效

#### Returns

[`LimitType`](../enums/Gameplay.LimitType.md)

X轴滑动类型

___

### getAxisYLinearType

▸ **getAxisYLinearType**(): [`LimitType`](../enums/Gameplay.LimitType.md)

**`Description`**

获取Y轴滑动类型

**`Effect`**

调用端生效

#### Returns

[`LimitType`](../enums/Gameplay.LimitType.md)

Y轴滑动类型

___

### getAxisZLinearType

▸ **getAxisZLinearType**(): [`LimitType`](../enums/Gameplay.LimitType.md)

**`Description`**

获取Z轴滑动类型

**`Effect`**

调用端生效

#### Returns

[`LimitType`](../enums/Gameplay.LimitType.md)

Z轴滑动类型


### setAxisXLinearType

▸ **setAxisXLinearType**(`LimitType`): `void`

**`Description`**

设置X轴滑动类型

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `LimitType` | [`LimitType`](../enums/Gameplay.LimitType.md) | X轴滑动类型 |

#### Returns

`void`

___

### setAxisYLinearType

▸ **setAxisYLinearType**(`LimitType`): `void`

**`Description`**

设置Y轴滑动类型

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `LimitType` | [`LimitType`](../enums/Gameplay.LimitType.md) | Y轴滑动类型 |

#### Returns

`void`

___

### setAxisZLinearType

▸ **setAxisZLinearType**(`LimitType`): `void`

**`Description`**

设置Z轴滑动类型

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `LimitType` | [`LimitType`](../enums/Gameplay.LimitType.md) | Z轴滑动类型 |

#### Returns

`void`