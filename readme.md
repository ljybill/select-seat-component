# 需要具备的功能

目前能力有限，这个计划在2018年6月开始开发，先挖个坑

移动端选座组件开发

## 基本要求 

1. 正确渲染场馆底图和座位等元素
2. 点击座位会切换座位状态（正常、已售、选中）
3. 支持手势拖动和缩放
4. 支持鹰眼图(区域缩略图), 鹰眼图座位状态与区域内座位状态保持一致, 鹰眼图红框位置与用户可视区域保持一致
5. 显示行号，行号状态与用户拖动/缩放操作保持一致

## 开发要求

1. 代码结构清晰，具备OOP思想
2. 最后代码使用webpack打包，将体积降低

## 性能要求
1. 支持10万座位的极端情况
2. 绘制时间低于1秒, 从打开页面到用户可操作时间低于2秒
