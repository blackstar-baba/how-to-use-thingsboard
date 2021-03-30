### Thingsboard使用

基于**3.2**分支的使用文档，包含基础、高阶、二开和扩展阅读

#### 准备
- Jdk，11+（因3.2.2版本需要11），用于编译运行
- Maven，3.2.1+，不强制需要，某些IDE也自带
- IDE，推荐Idea，查看代码和运行
- Html5浏览器，推荐使用Chorme，用于页面操作
- 容器引擎，推荐使用Docker，用于初始化环境，比如PG数据库
- Mqtt客户端，推荐使用MqttBox，用于模拟时序数据

### 基础入门

#### 编译

- 编译 [入口](doc/编译.md)


#### 运行

- 运行 [入口](doc/运行.md)


#### 调试

- 后端调试 [入口](doc/后端调试.md)

- 前端调试 [入口](doc/前端调试.md)



#### 使用
-  权限体系 //todo
-  设备
	-  普通设备  [入口](doc/普通设备.md)
	-  智能网关  [入口](doc/智能网关.md)
-  资产 [入口](doc/资产.md)
-  规则引擎 [入口](doc/规则引擎.md)
-  组件
-  仪表盘
-  一个示例


### 高阶使用

#### 源码分析
- 工程结构
- Actor模型
- 规则引擎
- 数据接入 	
  - 设备 [单机]() [分布式]()	
  - 网关 [单机]() [分布式]()
- 反向控制

#### 部署
- 整体部署
- 组件化部署

#### 最佳实践
- 容器集群



### 二次开发
- 组件扩展
- 规则节点扩展
- 白标修改
- 定时任务
- 设备树


### 扩展阅读
- IOT网关








