# 24好玩开放平台

## 愿景
让H5开发者不再担心没有后端的支持，平台将提供完备的接口以及管理、测试、部署一站式服务。除可以快速部署H5项目外，还提供精准清晰的数据统计，还能轻松地将项目改写成模板，供更多的人使用。

## 项目总览

#### 24好玩开放平台（open.24haowan.com）（参考微信开放平台）
- 资源中心（提供帮助文档、开发文档、示例代码等资源，以支持开发者接入）
- 管理中心（管理自己的应用，包括创建、删除、编辑等）
- 数据中心（查看应用的统计数据）
- 账号中心（管理开发者账号，包含查看appKey、修改密码等）
- 信息中心（查看系统通知）

#### 开发接入相关（每一项都必须提供详细的文档）
- HWSDK（使用开发者appKey初始化，提供与平台进行数据交互接口，以及提供一些基础服务）
- API服务（各功能模块服务端接口，主要通过Ajax与客户端进行数据的交互，主要与HWSDK对接）
- 配置表生成器（开发者勾选需要接入的功能，填写表单，即可自动生成配置表，随后开发者可修改配置表以进一步自定义）
- 代码上传系统（开发者按说明编写配置表，随代码上传，即可自动进行部署）
- 在线测试沙箱（开发者可在沙箱中测试平台的功能接口，如排行榜等功能将设有预设数据）
- 可视化配置表编辑界面（即工作台，根据配置表中信息进行界面的渲染，能够按开发者要求实现对配置表的编辑）

## 项目内容（以用例来描述）
#### 24好玩开放平台
- 资源中心
 - 开放平台帮助文档
 - 开发接入文档
 - 示例代码
 - 常见问题
- 管理中心
 - 应用列表
 - 创建应用
 - 管理应用
 - 删除应用
- 数据中心
 - 数据统计
 - 数据分析
 - 数据对比
- 账号中心
 - 查看appKey
 - 修改密码
 - 修改资料
 - 余额（可能涉及分成）
- 信息中心
 - 查看系统通知
 - 删除系统通知
- 公共部分
 - 登录、注册
 - 联系客服
 - 官网介绍
 
#### 开发接入相关
- HWSDK
 - 获取用户信息
 - 获取模板信息
 - 获取游戏信息
 - 调用营销接口（提交报名信息、提交分数、抽奖等）
 - 提供页面模板（加载页、开始页、结束页等）
 - 常用辅助工具
- API服务
 - 对接HWSDK的接口
 - 营销接口逻辑实现
 - 数据库操作
 - 开放平台数据中心的支撑
- 配置表生成器
 - 提供所有工作台控件以供选择
 - 提供所有营销接口以供选择
 - 模板静态信息表单
- 代码上传系统
 - 根据配置表自动识别对应资源，上传到CDN和服务器
 - 创建模板记录
 - 创建模板沙箱
- 在线测试沙箱
 - 独立运行环境
 - 需要大量数据的接口将提供预设数据
 - 测试期间产生数据在退出沙箱时自动清除
 - 完整的功能测试
- 可视化配置表编辑界面
 - 根据配置表进行界面渲染
 - 数据验证机制（第一层-工作台，第二层-开发者编写测试流程，第三层-服务端）
 - 即时预览机制（开发者实现）
 - 配置变动通知机制（工作台通知开发者的游戏）
 - 素材库（图片、音频）
 - 奖品库（普通奖品、红包）
