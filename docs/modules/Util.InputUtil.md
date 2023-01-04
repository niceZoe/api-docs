[Util](Util.Util.md) / InputUtil

# InputUtil <Badge type="tip" text="Namespace" />

## Table of contents

| Functions |
| :-----|
| **[convertScreenLocationToWorldSpace](Util.InputUtil.md#convertscreenlocationtoworldspace)**(`number`, `number`): [`ConvertScreenResult`](../classes/Type.ConvertScreenResult.md) <br> 将二维屏幕位置转换为世界空间三维位置和方向|
| **[enableCursorInteractWithUI](Util.InputUtil.md#enablecursorinteractwithui)**(`boolean`): `void` <br> 设置鼠标指针是否能与UI交互|
| **[enableCursorLock](Util.InputUtil.md#enablecursorlock)**(`boolean`): `void` <br> 设置是开启光标锁功能，开启后可以按shift键切换光标是否显示。|
| **[isCursorInteractiveWithUI](Util.InputUtil.md#iscursorinteractivewithui)**(): `boolean` <br> 获取鼠标指针是否能与UI交互|
| **[isCursorLockEnabled](Util.InputUtil.md#iscursorlockenabled)**(): `boolean` <br> 获取是否允许通过快捷方式切换鼠标的使用组合模式|
| **[isCursorLocked](Util.InputUtil.md#iscursorlocked)**(): `boolean` <br> 获取鼠标指针是否锁定|
| **[isCursorVisible](Util.InputUtil.md#iscursorvisible)**(): `boolean` <br> 获取鼠标指针是否可见|
| **[onKeyDown](Util.InputUtil.md#onkeydown)**([`Keys`](../enums/Type.Keys.md), (...`params`: `unknown`[]) => `void`): [`EventListener`](../classes/Events.EventListener.md) <br> 键盘输入事件-点击|
| **[onKeyPress](Util.InputUtil.md#onkeypress)**([`Keys`](../enums/Type.Keys.md), (...`params`: `unknown`[]) => `void`): [`EventListener`](../classes/Events.EventListener.md) <br> 键盘输入事件-按压|
| **[onKeyUp](Util.InputUtil.md#onkeyup)**([`Keys`](../enums/Type.Keys.md), (...`params`: `unknown`[]) => `void`): [`EventListener`](../classes/Events.EventListener.md) <br> 键盘输入事件-抬起|
| **[projectWorldLocationToWidgetPosition](Util.InputUtil.md#projectworldlocationtowidgetposition)**([`Vector`](../classes/Type.Vector.md), `boolean`): [`ConvertScreenResult`](../classes/Type.ConvertScreenResult.md) <br> 获取角色在世界中的位置，投射到屏幕上|
| **[setCursorLocked](Util.InputUtil.md#setcursorlocked)**(`boolean`): `void` <br> 设置鼠标指针是否锁定|
| **[setCursorVisible](Util.InputUtil.md#setcursorvisible)**(`boolean`): `void` <br> 设置鼠标指针是否可见|

## Functions

### convertScreenLocationToWorldSpace

▸ **convertScreenLocationToWorldSpace**(`screenX`, `screenY`): [`ConvertScreenResult`](../classes/Type.ConvertScreenResult.md)

**`Description`**

将二维屏幕位置转换为世界空间三维位置和方向

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `screenX` | `number` |  屏幕X轴坐标值 default: |
| `screenY` | `number` |  屏幕Y轴坐标值 |

#### Returns

[`ConvertScreenResult`](../classes/Type.ConvertScreenResult.md)

屏幕坐标转换结果

___

### enableCursorInteractWithUI

▸ **enableCursorInteractWithUI**(`canInteract`): `void`

**`Description`**

设置鼠标指针是否能与UI交互

**`Effect`**

客户端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `canInteract` | `boolean` | 可交互 |

#### Returns

`void`

___

### enableCursorLock

▸ **enableCursorLock**(`isEnableMouseLock`): `void`

**`Description`**

设置是开启光标锁功能，开启后可以按shift键切换光标是否显示。

**`Effect`**

客户端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `isEnableMouseLock` | `boolean` | 是否可切换 |

#### Returns

`void`

___

### isCursorInteractiveWithUI

▸ **isCursorInteractiveWithUI**(): `boolean`

**`Description`**

获取鼠标指针是否能与UI交互

**`Effect`**

客户端生效

#### Returns

`boolean`

是否能与UI交互

___

### isCursorLockEnabled

▸ **isCursorLockEnabled**(): `boolean`

**`Description`**

获取是否允许通过快捷方式切换鼠标的使用组合模式

**`Effect`**

客户端生效

#### Returns

`boolean`

是否可切换

___

### isCursorLocked

▸ **isCursorLocked**(): `boolean`

**`Description`**

获取鼠标指针是否锁定

**`Effect`**

客户端生效

#### Returns

`boolean`

是否锁定

___

### isCursorVisible

▸ **isCursorVisible**(): `boolean`

**`Description`**

获取鼠标指针是否可见

**`Effect`**

客户端生效

#### Returns

`boolean`

是否可见

___

### onKeyDown

▸ **onKeyDown**(`Key`, `listener`): [`EventListener`](../classes/Events.EventListener.md)

**`Description`**

键盘输入事件-点击

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `Key` | [`Keys`](../enums/Type.Keys.md) | 按键值 |
| `listener` | (...`params`: `unknown`[]) => `void` | 监听回调 |

#### Returns

[`EventListener`](../classes/Events.EventListener.md)

返回一个事件监听器

___

### onKeyPress

▸ **onKeyPress**(`Key`, `listener`): [`EventListener`](../classes/Events.EventListener.md)

**`Description`**

键盘输入事件-按压

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `Key` | [`Keys`](../enums/Type.Keys.md) | 按键值 |
| `listener` | (...`params`: `unknown`[]) => `void` | 监听回调 |

#### Returns

[`EventListener`](../classes/Events.EventListener.md)

返回一个事件监听器

___

### onKeyUp

▸ **onKeyUp**(`Key`, `listener`): [`EventListener`](../classes/Events.EventListener.md)

**`Description`**

键盘输入事件-抬起

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `Key` | [`Keys`](../enums/Type.Keys.md) | 按键值 |
| `listener` | (...`params`: `unknown`[]) => `void` | 监听回调 |

#### Returns

[`EventListener`](../classes/Events.EventListener.md)

返回一个事件监听器

___

### projectWorldLocationToWidgetPosition

▸ **projectWorldLocationToWidgetPosition**(`worldLocation`, `playerViewportRelative?`): [`ConvertScreenResult`](../classes/Type.ConvertScreenResult.md)

**`Description`**

获取角色在世界中的位置，投射到屏幕上

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `worldLocation` | [`Vector`](../classes/Type.Vector.md) |  世界坐标 |
| `playerViewportRelative?` | `boolean` |  这是否应该相对于播放器视口子区域（在分割屏幕中使用播放器附加的小部件或纵横比受限时有用）default:false |

#### Returns

[`ConvertScreenResult`](../classes/Type.ConvertScreenResult.md)

屏幕坐标转换结果，无WorldDirection，为默认值Type.Vector.ZERO

___

### setCursorLocked

▸ **setCursorLocked**(`isLock`): `void`

**`Description`**

设置鼠标指针是否锁定

**`Effect`**

客户端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `isLock` | `boolean` | 是否锁定 |

#### Returns

`void`

___

### setCursorVisible

▸ **setCursorVisible**(`isVisible`): `void`

**`Description`**

设置鼠标指针是否可见

**`Effect`**

客户端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `isVisible` | `boolean` | 是否可见 |

#### Returns

`void`