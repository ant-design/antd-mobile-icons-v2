### 介绍

antd-mobile 自 1.0 后由之前的的 iconfont 改为 svg，`Icon` 组件目前只内置了部分必须的 svg icon

该仓库存放同之前 iconfont 对应的 svg 图标，方便大家直接取之使用；

### 使用方法

- 找到你想用的 svg icon, 保存下来；
- 使用代码: `<Icon type={require('path/to/svg')} />`;
- 配置 webpack 以支持自定义 svg icon，具体可参见 [Icon 文档](https://github.com/ant-design/ant-design-mobile/blob/master/components/icon/index.zh-CN.md#如何使用-web)
