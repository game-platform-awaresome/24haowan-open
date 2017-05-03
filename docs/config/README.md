# 配置表

## 起点

配置表是一切的起点，工作台的界面渲染、值的校验等等都由此而来，因此必须熟读配置表编写的相关要求。

## 开始

配置表文件为json格式。<br>
配置表主要分为三部分：static, dist, workbench，形式如下：

```json
{
    "static": {...},
    "dist": {...},
    "workbench": {...}
}
```

每部分主要内容如下，详情请参考后续文档：

- static：静态配置
- dist：运行配置
- workbench：工作台配置

## 完整示例：

[下载完整示例](./example.json)

[import](./example.json)