# Oversea-saw / 跷跷板

> 本项目系基于Android平台的软件工程课程设计  
> **截止日期：2020-1-3**  
> An Android based project for Software Engineering course design.  

## 要求

本项目是一个针对海外留学生的分类信息网站，留学生在其中发布租房、买车、交友等信息

### 主要功能

+ [ ] 1. 信息分类管理
+ [ ] 2. 学校管理
+ [ ] 3. 信息发布（文本、图片）
+ [ ] 4. 根据地理位置信息综合管理
+ [ ] 5. 信息审核
+ [ ] 6. 信息搜索
+ [ ] 7. 学校周边资源介绍管理（小区、餐厅、医院、酒吧等）
+ [ ] 8. 资源评论（用户针对不同资源进行点评、评论、打分）
+ [ ] 9. 身份认证
+ [ ] 10. 统计分析功能（学校统计信息的发布量、不同类别信息的发布量）
+ [ ] 11. 登录
+ [ ] 12. 注册

> 简单来说就是留学生门户网站

### 项目要求

1. 以团队为单位
2. 自行选择IDE和DB
3. 指定开发计划、明确分工
4. 应当完成
 + [ ] 需求分析
 + [ ] 概要设计
 + [ ] 详细设计
 + [ ] 编码
 + [ ] 测试
5. **全体**提交一份**课设报告**
6. **每人**各提交一份**课设总结**

# 目前进度

> 设计并构建数据库设施（MySQL）

首先需要设计出所需要的数据模式概念模型，然后根据模型设计数据库  
**目前聚焦的数据模式：** ***身份认证***

+ **使用的数据库名：** `oversea_saw`
+ **数据库地址：** `ip待定:3306`
+ **连接字符串：** 尚未提供


+ **关系模式：** **信息分类（学校信息，租房信息，购车信息，交友信息）
+ **学校信息（学校名，学校地址，学校周边资源，学校联系电话）
+ **学校周边资源（学校名，小区，餐厅，医院，酒吧）
+ **留学生身份（学校名，国籍，学号，姓名，年龄，性别，联系电话）
+ **购房信息 （租房地址，租房价格，租房户型，租房时长，联系电话）
+ **购车信息 （购车地址，车辆价格，车型，性能，联系电话）
+ **交友信息 （联系电话，姓名，性别，年龄，职业，爱好）

