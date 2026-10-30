# Agent

## Agent 运行模式

### 1. ReAct 模式（Reasoning and Acting)

#### 1. React 模式的运行流程

![](.\photos\react_1.png)

#### 2. React 系统提示词（模型角色，运行规则，环境信息）

![](.\photos\react_2.png)

#### 3. React 时序图角色

![](./photos/react_3.png)

#### 4. React 运行时序图

![](./photos/react_4.png)

### 2. Plan-and-Execute 模式（先规划，再执行）

#### 1. Plan-and-Execute 时序图角色

![](./photos/plan-and-execute_1.png)

#### 2. Plan-and-Execute 运行时序图

![](./photos/plan-and-execute_2.png)

##### 1. 三轮循环（执行 Agent -> Re-Plan 计划）

###### 1. 第一轮

1. 执行 Agent

![](./photos/plan-and-execute_turn1(1).png)

2. Re-Plan 计划

![](./photos/plan-and-execute_turn1(2).png)

###### 2. 第二轮

1. 执行 Agent

![](./photos/plan-and-execute_turn2(1).png)

2. Re-Plan 计划

![](./photos/plan-and-execute_turn2(2).png)

###### 3. 第三轮

1. 执行 Agent

![](./photos/plan-and-execute_turn3(1).png)

2. Re-Plan 计划

![](./photos/plan-and-execute_turn3(2).png)