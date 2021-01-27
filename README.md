## 快速开发平台
> 人过留名，雁过留声。工作十余年，如果哪天不再写代码了，也能留个纪念。

### 计划目标
***
1. 网关鉴权
2. 通用开发
3. 通用查询
4. 自定义表单
5. 规则引擎
6. BPM
7. APS
### 实现思路
***
#### 通用开发
1. Spring boot 提供RequestMappingHandlerMapping.registerMapping及unregisterMapping实现动态注册RequestMapping
2. 前端编写后台服务代码，运行调试参考 [Debug Adapter Protocol](https://microsoft.github.io/debug-adapter-protocol/)
#### 通用查询
1. 前端使用raphael、G6、mxGraph设置查询编辑器，直接生成sql语句或者生成json格式后台进行解析。
#### 自定义表单
1. JSON Schema

### 实现功能
