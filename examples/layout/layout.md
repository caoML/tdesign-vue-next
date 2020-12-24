:: BASE_DOC ::

### 说明

`<t-layout>`：layout容器、可包裹子组件`<t-header>`、`<t-footer>`、`<t-aside>`、`<t-content>`。当子元素中包含 `<t-aside>` 时，全部子元素会水平排列，否则会垂直排列。

`<t-header>`：顶栏容器。

`<t-footer>`：底栏容器。

`<t-aside>`：侧边栏容器。

`<t-content>`：内容容器。

### 侧边栏导航布局

::: demo demos/aside1
::: 

### 侧边栏导航布局（带header）

::: demo demos/aside2 
::: 

### 侧边栏导航布局（侧栏在右侧）

::: demo demos/aside3 
::: 

### 顶部导航布局

::: demo demos/top 
:::

### 属性配置

### Header Props
名称 | 类型 | 默认值 | 说明 | 必传
-- | -- | -- | -- | --
height | String | - | 顶栏高度。样式表（class）中定义的默认高度为：64px | N


### Footer Props
名称 | 类型 | 默认值 | 说明 | 必传
-- | -- | -- | -- | --
height | String | - | 底栏高度。样式表（class）中定义的默认高度为：24px | N


### Aside Props
名称 | 类型 | 默认值 | 说明 | 必传
-- | -- | -- | -- | --
width | String | - | 侧边栏宽度。样式表（class）中定义的默认宽度为：232px | N