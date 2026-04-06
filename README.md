# GLM Coding Plan

这是 FamilyClaw 的 GLM Coding Plan AI Provider 插件。

它的作用很直接：把家庭里的 AI Provider 接到 GLM Coding Plan，让代码规划、快速问答和结构化文本回复可以直接走 GLM 的专用 Coding 接口。

## 适合什么场景

- 想在 FamilyClaw 里接入 GLM Coding Plan 作为 AI Provider
- 希望优先使用 GLM 的 Coding 专用接口，而不是普通聊天接口
- 需要更偏稳定、快速的短文本和快任务响应

## 插件特点

- 默认提供 GLM Coding Plan 的中国站和国际站地址选项
- 对快任务自动收紧上下文，并关闭不必要的 thinking 开销
- 支持配置显示名称、模型名、温度、最大输出长度等常用参数

## 配置时需要准备什么

- 一个可用的 GLM Coding Plan API Key
- 你希望在 FamilyClaw 里展示的提供方名称
- 根据账号所属站点选择正确的 Base URL

## 基本使用方式

1. 安装并启用插件
2. 填写 `API Key`
3. 选择中国站或国际站 `Base URL`

## 已知限制

- 当前主要面向文本能力
- 默认不做模型自动发现
- 插件本身不提供额外的远程执行能力，只负责 Provider 接入

## 兼容性

- 插件版本：`0.2.2`
- 最低宿主版本：`0.1.2`
