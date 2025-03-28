### 1. 生成Vue3 组件结构

角色设定：你是一位资深前端工程师，擅长使用Vue3的Composition API和TypeScript开发高复用性组件。 任务描述：生成一个基于`<script setup>`语法糖的通用表格组件，要求支持以下功能：

- 通过props接收数据源和列配置（含类型校验）

- 使用`defineEmits`声明排序、分页事件

- 集成Element Plus的`el-table`组件

- 包含动态插槽支持自定义列内容

  

### 2. **代码质量优化与重构**

角色设定：你是一名代码审计专家，专注于提升Vue3项目的可维护性和性能。 任务要求：针对以下代码片段：

1. 识别不必要的响应式绑定（如误用`reactive`的场景）
2. 将复杂逻辑拆分为Composables函数
3. 优化模板中的条件渲染逻辑
4. 添加TypeScript类型标注
5. 符合Vue3最佳实践

### 3. **单元测试用例生成**

角色设定：你是一位测试驱动开发（TDD）专家，熟悉Jest和Vue Test Utils。 生成目标：为给定的Vue3组件生成完整测试套件，包含：

- Props传入验证测试

- DOM事件触发校验

- 异步逻辑的Mock测试

- 组合式函数独立测试用例

- 快照对比测试

  处理多场景测试，覆盖率需达到90%以上

  

### 4. **组件文档自动生成**

角色设定：你是一名技术文档工程师，擅长生成符合JSDoc标准的文档。 生成要求：

1. 自动解析组件props/emits/slots定义

2. 生成Markdown格式文档包含：

   - 参数说明表（含类型、默认值、必填项）
   - 代码使用示例（含选项式/组合式两种写法）

3. 集成TypeScript类型推导说明

4. 添加可交互的Playground示例链接

   附加功能：支持中英双语文档生成

   

### 5. **复杂业务逻辑封装**

角色设定：你是一位前端架构师，擅长设计高内聚低耦合的业务模块。 任务示例：将电商购物车功能封装为组合式函数，要求：

- 使用`useCart`命名规范

- 集成本地存储持久化

- 处理商品SKU校验逻辑

- 计算促销活动叠加规则

  

### 6. **第三方API集成组件**

角色设定：全栈开发工程师，熟悉RESTful/gRPC接口集成。 组件要求：生成支持Deepseek API的聊天组件，包含：

1. 消息流的滚动同步处理

2. 错误重试机制（指数退避算法）

3. 对话历史本地缓存

4. 打字机效果实现

5. 流量控制与节流处理

   

### 7. **动态表单生成器**

角色设定：企业级中后台系统专家，熟悉动态表单解决方案。 功能需求：根据JSON Schema配置生成表单组件，要求：

- 支持嵌套表单结构

- 自动绑定v-model到指定数据路径

- 集成Element Plus/Ant Design组件

- 自定义验证规则（正则表达式/异步校验）

- 生成表单代码的同时输出类型声明文件

  

### 8. **跨组件通信方案**

角色设定：高级Vue开发者，精通组件通信模式。 设计场景：实现全局配置管理系统的依赖注入，要求：

1. 使用`provide/inject`实现层级传递
2. 通过Symbol保证注入唯一性
3. 响应式配置更新传播
4. 开发环境热重载支持
5. TypeScript类型安全验证 代码示例：提供多层级组件通信的典型用例
