# Dify_for_DB
基于dify开源项目实现在数据库，IT运维领域的AI应用
# 使用说明
## 1 打开dify
<img width="1879" height="492" alt="image" src="https://github.com/user-attachments/assets/d017c7a8-9b63-42c6-9647-526efcd61e63" />

## 2 导入DSL
<img width="1868" height="660" alt="image" src="https://github.com/user-attachments/assets/4ad1a9e2-9020-40ab-bb12-6ec95f215f53" />

## 功能清单

| 名称 | 功能说明 | 价值说明 | 效果展示 | 作者 |
|:----:|:-----|:-----|:-----|:-------|
| sql业务解析 | 根据用户输入的SQL，自动翻译sql业务含义 | 1. 代码可读性与维护性提升 使SQL语句的业务意图显式化并且新团队成员无需逐行分析复杂SQL就能理解业务逻辑<br>2. 开发效率提升，快速定位SQL对应的业务场景，为数据库重构提供业务上下文<br>3. 决策支持 评估SQL变更会影响哪些业务功能，通过SQL反向追踪业务规则演变历史<br>4. 业务价值 自动生成最新、准确的SQL业务文档  跟踪SQL业务逻辑的历史变更 构建可搜索的SQL业务知识库|[sql业务解析](#sql业务解析)| zqf20096327 |
| sql自动注释 | 针对数据库存储过程自动注释 | 1. 代码可读性与维护性提升 后续维护者（包括团队新成员）能快速理解代码逻辑，降低“阅读成本”，尤其在长期维护或跨团队协作中效果显著。<br>2. 开发效率提升 减少重复劳动<br>3. 决策支持<br>4. 业务价值 跨项目复用 SQL 片段时，注释同步携带上下文，避免重复造轮子|[sql自动注释](#sql自动注释)| zqf20096327 |

## 效果展示
### sql业务解析
<details>
<summary>效果展示</summary>
  <img width="582" height="592" alt="image" src="https://github.com/user-attachments/assets/a2c74b06-4978-43ec-bfd6-eabc0496b1ed" />
  <img width="933" height="807" alt="image" src="https://github.com/user-attachments/assets/acc1246c-8d2d-49cb-9a12-ad6a51bbb035" />
  <img width="1015" height="780" alt="image" src="https://github.com/user-attachments/assets/d235b716-67f5-4363-8380-8ae540c0287a" />
  <img width="657" height="277" alt="image" src="https://github.com/user-attachments/assets/82a2117d-4a41-4319-ad63-56090f0c0c3a" />
</details>

### sql自动注释
<details>
<summary>效果展示</summary>
  <img width="555" height="887" alt="image" src="https://github.com/user-attachments/assets/52136cfc-b7b4-4fea-9975-9fec80c46e6c" />
  <img width="1015" height="654" alt="image" src="https://github.com/user-attachments/assets/f1f534de-f170-42e6-ad7e-4a4f2861f544" />
  <img width="1010" height="661" alt="image" src="https://github.com/user-attachments/assets/5eed6145-a079-4dba-9d3d-f2fdb383ccd6" />
  <img width="964" height="907" alt="image" src="https://github.com/user-attachments/assets/da037cac-1d50-4315-ac29-8e045058994f" />
  <img width="952" height="940" alt="image" src="https://github.com/user-attachments/assets/3ba37880-b899-4557-9c8e-b232e2106f5c" />
  <img width="732" height="282" alt="image" src="https://github.com/user-attachments/assets/d2e1b31b-060e-4e64-aafd-aebfc74a6f32" />

</details>
