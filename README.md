# 插件市场插件说明文档  

## 1. 插件基本信息  
- **插件名称**：AstrBot 插件市场  
- **插件标识**：astrbot_plugins_market  
- **作者**：长安某
- **功能描述**：提供插件市场浏览、搜索和一键安装功能，支持安装后自动加载插件  


## 2. 核心功能列表  
### 2.1 插件市场浏览  
- 分页展示官方插件市场中的所有插件（默认10个/页）  
- 显示插件名称、作者、功能描述及安装指令  
- 支持页码切换，如查看第2页：`/插件市场 2`  

### 2.2 关键词搜索  
- 支持按插件名称、作者、描述进行模糊搜索  
- 搜索结果分页展示，如：`/插件搜索 天气 2`（搜索"天气"并查看第2页）  

### 2.3 插件安装与加载  
- 管理员专属指令：`/安装插件 [编号/名称]`  
- 安装后自动触发插件加载，无需手动重载  

## 3. 指令使用说明  
### 3.1 浏览插件市场  
- **指令格式**：`/插件市场 [页码]`  
- **示例**：
-  ` / 插件市场 `# 查看第 1 页
-  ` / 插件市场 3 ` # 查看第 3 页




##  注意事项  
###  权限限制  
- 安装插件仅管理员可执行
- 所有指令均需@或前缀

##  更新
- 1.0 基础功能实现

##  更新计划
根据不同要求进行排序 例如：最近更新时间，star数
