[UI](../modules/UI.UI.md) / UserWidget

# UserWidget <Badge type="tip" text="Class" />

**`Description`**

UI 控件的集合,预制体 UI

## Hierarchy

- [`Widget`](UI.UI.Widget.md)

  ↳ **`UserWidget`**

  ↳↳ [`UserWidgetPrefab`](UI.UI.UserWidgetPrefab.md)

## Table of contents

| Accessors                                                                                                                                             |
| :---------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[autoSizeEnable](UI.UI.UserWidget.md#autosizeenable)**(): `boolean` <br> 获取是否自动设置大小                                                       |
| **[cachedGeometry](UI.UI.UserWidget.md#cachedgeometry)**(): [`Geometry`](UI.UI.Geometry.md) <br> 获取上一次的 GetTickSpaceGeometry                    |
| **[constraints](UI.UI.UserWidget.md#constraints)**(): `Readonly`<[`UIConstraintAnchors`](UI.UI.UIConstraintAnchors.md)\> <br> 获取控件的布局          |
| **[desiredSize](UI.UI.UserWidget.md#desiredsize)**(): [`Vector2`](Type.Type.Vector2.md) <br> 获取期望大小                                             |
| **[enable](UI.UI.UserWidget.md#enable)**(): `boolean` <br> 是否可用                                                                                   |
| **[focusable](UI.UI.UserWidget.md#focusable)**(): `boolean` <br> 获取是否响应键盘焦点事件                                                             |
| **[guid](UI.UI.UserWidget.md#guid)**(): `string` <br> 获取控件 GUID                                                                                   |
| **[isHovered](UI.UI.UserWidget.md#ishovered)**(): `boolean` <br> 是否是 hovered                                                                       |
| **[name](UI.UI.UserWidget.md#name)**(): `string` <br> 获取名字                                                                                        |
| **[paintSpaceGeometry](UI.UI.UserWidget.md#paintspacegeometry)**(): [`Geometry`](UI.UI.Geometry.md) <br> 获取最后一次用于渲染 Widget 的几何信息       |
| **[parent](UI.UI.UserWidget.md#parent)**(): [`Widget`](UI.UI.Widget.md) <br> 获取父节点                                                               |
| **[position](UI.UI.UserWidget.md#position)**(): `Readonly`<[`Vector2`](Type.Type.Vector2.md)\> <br> 获取控件的位置                                    |
| **[renderOpacity](UI.UI.UserWidget.md#renderopacity)**(): `number` <br> 获取渲染透明度                                                                |
| **[renderScale](UI.UI.UserWidget.md#renderscale)**(): [`Vector2`](Type.Type.Vector2.md) <br> 获取渲染缩放                                             |
| **[renderShear](UI.UI.UserWidget.md#rendershear)**(): [`Vector2`](Type.Type.Vector2.md) <br> 获取渲染错切形变                                         |
| **[renderTransformAngle](UI.UI.UserWidget.md#rendertransformangle)**(): `number` <br> 获取渲染的角度                                                  |
| **[renderTransformPivot](UI.UI.UserWidget.md#rendertransformpivot)**(): [`Vector2`](Type.Type.Vector2.md) <br> 获取渲染锚点                           |
| **[rootContent](UI.UI.UserWidget.md#rootcontent)**(): [`Canvas`](UI.UI.Canvas.md) <br> 获取根 Canvas                                                  |
| **[size](UI.UI.UserWidget.md#size)**(): [`Vector2`](Type.Type.Vector2.md) <br> 获取大小                                                               |
| **[slot](UI.UI.UserWidget.md#slot)**(): [`UISlot`](UI.UI.UISlot.md) <br> since:v0.20.0.0 reason:底层方案修改 replacement:直接使用控件获取设置相关信息 |
| **[tickSpaceGeometry](UI.UI.UserWidget.md#tickspacegeometry)**(): [`Geometry`](UI.UI.Geometry.md) <br> 获取最后一次用于驱动 Widget Tick 的几何信息    |
| **[transform](UI.UI.UserWidget.md#transform)**(): `Readonly`<[`UITransform`](UI.UI.UITransform.md)\> <br> 得到控件的大小和位置                        |
| **[visibility](UI.UI.UserWidget.md#visibility)**(): [`SlateVisibility`](../enums/UI.UI.SlateVisibility.md) <br> 获取可见性                            |
| **[visible](UI.UI.UserWidget.md#visible)**(): `boolean` <br> 是否可见                                                                                 |
| **[zOrder](UI.UI.UserWidget.md#zorder)**(): `number` <br> 获取 zorder                                                                                 |

| Methods                                                                                                                                    |
| :----------------------------------------------------------------------------------------------------------------------------------------- |
| **[addToViewport](UI.UI.UserWidget.md#addtoviewport)**(`number`): `void` <br> 添加到屏幕上                                                 |
| **[destroyObject](UI.UI.UserWidget.md#destroyobject)**(): `void` <br> 立刻移除并销毁 不可以在使用                                          |
| **[equal](UI.UI.UserWidget.md#equal)**([`Widget`](UI.UI.Widget.md)): `boolean` <br> 判断是不是同一个对象                                   |
| **[findChildByPath](UI.UI.UserWidget.md#findchildbypath)**(`string`): [`Widget`](UI.UI.Widget.md) <br> 通过相对路径查找节点                |
| **[invalidateLayoutAndVolatility](UI.UI.UserWidget.md#invalidatelayoutandvolatility)**(): `void` <br> 立刻触发重新渲染的和排布计算         |
| **[removeRootContent](UI.UI.UserWidget.md#removerootcontent)**(): `void` <br> 移除根 Canvas,会销毁根 Canvas，无法再次使用                  |
| **[newObject](UI.UI.UserWidget.md#newobject)**([`Canvas`](UI.UI.Canvas.md)): [`UserWidget`](UI.UI.UserWidget.md) <br> 创建 UserWidget 控件 |

## Accessors

### autoSizeEnable

• `get` **autoSizeEnable**(): `boolean`

**`Description`**

获取是否自动设置大小

**`Effect`**

只在客户端调用生效

#### Returns

`boolean`

是否自动设置大小

• `set` **autoSizeEnable**(`autoSize`): `void`

**`Description`**

设置是否自动设置大小

**`Effect`**

只在客户端调用生效

#### Parameters

| Name       | Type      | Description      |
| :--------- | :-------- | :--------------- |
| `autoSize` | `boolean` | 是否自动设置大小 |

#### Returns

`void`

---

### cachedGeometry

• `get` **cachedGeometry**(): [`Geometry`](UI.UI.Geometry.md)

**`Description`**

获取上一次的 GetTickSpaceGeometry

**`Effect`**

只在客户端调用生效

#### Returns

[`Geometry`](UI.UI.Geometry.md)

返回上一次的 GetTickSpaceGeometry

---

### constraints

• `get` **constraints**(): `Readonly`<[`UIConstraintAnchors`](UI.UI.UIConstraintAnchors.md)\>

**`Description`**

获取控件的布局

**`Effect`**

只在客户端调用生效

#### Returns

`Readonly`<[`UIConstraintAnchors`](UI.UI.UIConstraintAnchors.md)\>

控件的布局

• `set` **constraints**(`ininconstraints`): `void`

**`Description`**

设置控件的布局

**`Effect`**

只在客户端调用生效

#### Parameters

| Name              | Type                                                  | Description |
| :---------------- | :---------------------------------------------------- | :---------- |
| `ininconstraints` | [`UIConstraintAnchors`](UI.UI.UIConstraintAnchors.md) | 控件的布局  |

#### Returns

`void`

---

### desiredSize

• `get` **desiredSize**(): [`Vector2`](Type.Type.Vector2.md)

**`Description`**

获取期望大小

**`Effect`**

只在客户端调用生效

#### Returns

[`Vector2`](Type.Type.Vector2.md)

返回期望大小

---

### enable

• `get` **enable**(): `boolean`

**`Description`**

是否可用

**`Effect`**

只在客户端调用生效

#### Returns

`boolean`

boolean

• `set` **enable**(`isEnable`): `void`

**`Description`**

设置可用性

**`Effect`**

只在客户端调用生效

#### Parameters

| Name       | Type      | Description    |
| :--------- | :-------- | :------------- |
| `isEnable` | `boolean` | 可用性 boolean |

#### Returns

`void`

返回设置结果

---

### focusable

• `get` **focusable**(): `boolean`

**`Description`**

获取是否响应键盘焦点事件

**`Effect`**

只在客户端调用生效

#### Returns

`boolean`

返回相应键盘的焦点事件

• `set` **focusable**(`isFocus`): `void`

**`Description`**

设置是否响应键盘焦点事件

**`Effect`**

只在客户端调用生效

#### Parameters

| Name      | Type      | Description |
| :-------- | :-------- | :---------- |
| `isFocus` | `boolean` | 是否相应    |

#### Returns

`void`

---

### guid

• `get` **guid**(): `string`

**`Description`**

获取控件 GUID

**`Effect`**

只在客户端调用生效

#### Returns

`string`

控件 GUID

---

### isHovered

• `get` **isHovered**(): `boolean`

**`Description`**

是否是 hovered

**`Effect`**

只在客户端调用生效

#### Returns

`boolean`

boolean

---

### name

• `get` **name**(): `string`

**`Description`**

获取名字

**`Effect`**

只在客户端调用生效

#### Returns

`string`

返回名字

• `set` **name**(`name`): `void`

**`Description`**

设定名字

**`Effect`**

只在客户端调用生效

#### Parameters

| Name   | Type     | Description |
| :----- | :------- | :---------- |
| `name` | `string` | 名字        |

#### Returns

`void`

---

### paintSpaceGeometry

• `get` **paintSpaceGeometry**(): [`Geometry`](UI.UI.Geometry.md)

**`Description`**

获取最后一次用于渲染 Widget 的几何信息

**`Effect`**

只在客户端调用生效

#### Returns

[`Geometry`](UI.UI.Geometry.md)

返回最后一次用于渲染 Widget 的几何信息

---

### parent

• `get` **parent**(): [`Widget`](UI.UI.Widget.md)

**`Description`**

获取父节点

**`Effect`**

只在客户端调用生效

#### Returns

[`Widget`](UI.UI.Widget.md)

返回父节点

---

### position

• `get` **position**(): `Readonly`<[`Vector2`](Type.Type.Vector2.md)\>

**`Description`**

获取控件的位置

**`Effect`**

只在客户端调用生效

#### Returns

`Readonly`<[`Vector2`](Type.Type.Vector2.md)\>

控件的位置

• `set` **position**(`inFigmaPosition`): `void`

**`Description`**

设置控件的位置

**`Effect`**

只在客户端调用生效

#### Parameters

| Name              | Type                              | Description |
| :---------------- | :-------------------------------- | :---------- |
| `inFigmaPosition` | [`Vector2`](Type.Type.Vector2.md) | 控件的位置  |

#### Returns

`void`

---

### renderOpacity

• `get` **renderOpacity**(): `number`

**`Description`**

获取渲染透明度

**`Effect`**

只在客户端调用生效

#### Returns

`number`

返回渲染透明度

• `set` **renderOpacity**(`InOpacity`): `void`

**`Description`**

设置渲染透明度 0 ~ 1

**`Effect`**

只在客户端调用生效

#### Parameters

| Name        | Type     | Description |
| :---------- | :------- | :---------- |
| `InOpacity` | `number` | 透明度      |

#### Returns

`void`

---

### renderScale

• `get` **renderScale**(): [`Vector2`](Type.Type.Vector2.md)

**`Description`**

获取渲染缩放

**`Effect`**

只在客户端调用生效

#### Returns

[`Vector2`](Type.Type.Vector2.md)

返回渲染缩放

• `set` **renderScale**(`scale`): `void`

**`Description`**

设置渲染缩放

**`Effect`**

只在客户端调用生效

#### Parameters

| Name    | Type                              | Description |
| :------ | :-------------------------------- | :---------- |
| `scale` | [`Vector2`](Type.Type.Vector2.md) | 渲染缩放    |

#### Returns

`void`

---

### renderShear

• `get` **renderShear**(): [`Vector2`](Type.Type.Vector2.md)

**`Description`**

获取渲染错切形变

**`Effect`**

只在客户端调用生效

#### Returns

[`Vector2`](Type.Type.Vector2.md)

返回渲染错切形变

• `set` **renderShear**(`shear`): `void`

**`Description`**

设置渲染错切形变

**`Effect`**

只在客户端调用生效

#### Parameters

| Name    | Type                              | Description  |
| :------ | :-------------------------------- | :----------- |
| `shear` | [`Vector2`](Type.Type.Vector2.md) | 渲染错切形变 |

#### Returns

`void`

---

### renderTransformAngle

• `get` **renderTransformAngle**(): `number`

**`Description`**

获取渲染的角度

**`Effect`**

只在客户端调用生效

#### Returns

`number`

返回渲染角度

• `set` **renderTransformAngle**(`o`): `void`

**`Description`**

设置渲染的角度

**`Effect`**

只在客户端调用生效

#### Parameters

| Name | Type     | Description |
| :--- | :------- | :---------- |
| `o`  | `number` | 渲染角度    |

#### Returns

`void`

---

### renderTransformPivot

• `get` **renderTransformPivot**(): [`Vector2`](Type.Type.Vector2.md)

**`Description`**

获取渲染锚点

**`Effect`**

只在客户端调用生效

#### Returns

[`Vector2`](Type.Type.Vector2.md)

返回渲染锚点

• `set` **renderTransformPivot**(`Pivot`): `void`

**`Description`**

设置渲染锚点

**`Effect`**

只在客户端调用生效

#### Parameters

| Name    | Type                              | Description |
| :------ | :-------------------------------- | :---------- |
| `Pivot` | [`Vector2`](Type.Type.Vector2.md) | 渲染锚点    |

#### Returns

`void`

---

### rootContent

• `get` **rootContent**(): [`Canvas`](UI.UI.Canvas.md)

**`Description`**

获取根 Canvas

**`Effect`**

只在客户端调用生效

#### Returns

[`Canvas`](UI.UI.Canvas.md)

返回根 Canvas

• `set` **rootContent**(`content`): `void`

**`Description`**

设置 UI 的根 Canvas

**`Effect`**

只在客户端调用生效

#### Parameters

| Name      | Type                        | Description  |
| :-------- | :-------------------------- | :----------- |
| `content` | [`Canvas`](UI.UI.Canvas.md) | 根 UI 的内容 |

#### Returns

`void`

---

### size

• `get` **size**(): [`Vector2`](Type.Type.Vector2.md)

**`Description`**

获取大小

**`Effect`**

只在客户端调用生效

#### Returns

[`Vector2`](Type.Type.Vector2.md)

FVector2D

• `set` **size**(`inSize`): `void`

**`Description`**

设置控件的大小

**`Effect`**

只在客户端调用生效

#### Parameters

| Name     | Type                              | Description |
| :------- | :-------------------------------- | :---------- |
| `inSize` | [`Vector2`](Type.Type.Vector2.md) | 输入大小    |

#### Returns

`void`

---

### slot

• `get` **slot**(): [`UISlot`](UI.UI.UISlot.md)

**`Deprecated`**

since:v0.20.0.0 reason:底层方案修改 replacement:直接使用控件获取设置相关信息

**`Description`**

获取插槽

**`Effect`**

只在客户端调用生效

#### Returns

[`UISlot`](UI.UI.UISlot.md)

返回插槽

---

### tickSpaceGeometry

• `get` **tickSpaceGeometry**(): [`Geometry`](UI.UI.Geometry.md)

**`Description`**

获取最后一次用于驱动 Widget Tick 的几何信息

**`Effect`**

只在客户端调用生效

#### Returns

[`Geometry`](UI.UI.Geometry.md)

返回最后一次用于驱动 Widget Tick 的几何信息

---

### transform

• `get` **transform**(): `Readonly`<[`UITransform`](UI.UI.UITransform.md)\>

**`Description`**

得到控件的大小和位置

**`Effect`**

只在客户端调用生效

#### Returns

`Readonly`<[`UITransform`](UI.UI.UITransform.md)\>

控件的大小和位置

• `set` **transform**(`inTransform`): `void`

**`Description`**

设置控件的大小和位置

**`Effect`**

只在客户端调用生效

#### Parameters

| Name          | Type                                  | Description |
| :------------ | :------------------------------------ | :---------- |
| `inTransform` | [`UITransform`](UI.UI.UITransform.md) | 大小位置    |

#### Returns

`void`

---

### visibility

• `get` **visibility**(): [`SlateVisibility`](../enums/UI.UI.SlateVisibility.md)

**`Description`**

获取可见性

**`Effect`**

只在客户端调用生效

#### Returns

[`SlateVisibility`](../enums/UI.UI.SlateVisibility.md)

返回可见性

• `set` **visibility**(`Visibility`): `void`

**`Description`**

设置可见性

**`Effect`**

只在客户端调用生效

#### Parameters

| Name         | Type                                                   | Description |
| :----------- | :----------------------------------------------------- | :---------- |
| `Visibility` | [`SlateVisibility`](../enums/UI.UI.SlateVisibility.md) | 可见性      |

#### Returns

`void`

---

### visible

• `get` **visible**(): `boolean`

**`Description`**

是否可见

**`Effect`**

只在客户端调用生效

#### Returns

`boolean`

boolean

---

### zOrder

• `get` **zOrder**(): `number`

**`Description`**

获取 zorder

**`Effect`**

只在客户端调用生效

#### Returns

`number`

zorder

• `set` **zOrder**(`InZOrder`): `void`

**`Description`**

设置 zoder

**`Effect`**

只在客户端调用生效

#### Parameters

| Name       | Type     | Description    |
| :--------- | :------- | :------------- |
| `InZOrder` | `number` | 值越大在越上层 |

#### Returns

`void`

## Methods

### addToViewport

▸ **addToViewport**(`zOrder`): `void`

**`Description`**

添加到屏幕上

**`Effect`**

只在客户端调用生效

#### Parameters

| Name     | Type     | Description          |
| :------- | :------- | :------------------- |
| `zOrder` | `number` | 添加到屏幕的层级关系 |

#### Returns

`void`

---

### destroyObject

▸ **destroyObject**(): `void`

**`Description`**

立刻移除并销毁 不可以在使用

**`Effect`**

只在客户端调用生效

#### Returns

`void`

---

### equal

▸ **equal**(`that`): `boolean`

**`Description`**

判断是不是同一个对象

**`Effect`**

只在客户端调用生效

#### Parameters

| Name   | Type                        | Description            |
| :----- | :-------------------------- | :--------------------- |
| `that` | [`Widget`](UI.UI.Widget.md) | 需要比较的另外一个对象 |

#### Returns

`boolean`

boolean

---

### findChildByPath

▸ **findChildByPath**(`inPath`): [`Widget`](UI.UI.Widget.md)

**`Description`**

通过相对路径查找节点

**`Effect`**

只在客户端调用生效

#### Parameters

| Name     | Type     | Description |
| :------- | :------- | :---------- |
| `inPath` | `string` | 路径        |

#### Returns

[`Widget`](UI.UI.Widget.md)

返回查找节点结果

---

### invalidateLayoutAndVolatility

▸ **invalidateLayoutAndVolatility**(): `void`

**`Description`**

立刻触发重新渲染的和排布计算

**`Effect`**

只在客户端调用生效

#### Returns

`void`

---

### removeRootContent

▸ **removeRootContent**(): `void`

**`Description`**

移除根 Canvas,会销毁根 Canvas，无法再次使用

**`Effect`**

只在客户端调用生效

#### Returns

`void`

---

### newObject

▸ `Static` **newObject**(`parent?`): [`UserWidget`](UI.UI.UserWidget.md)

**`Description`**

创建 UserWidget 控件

**`Effect`**

只在客户端调用生效

#### Parameters

| Name      | Type                        | Description                          |
| :-------- | :-------------------------- | :----------------------------------- |
| `parent?` | [`Canvas`](UI.UI.Canvas.md) | 创建控件的外 Outer 对象 default:null |

#### Returns

[`UserWidget`](UI.UI.UserWidget.md)

返回创建的控件