# ETL

生产环境 ---ETL---> ODS ---ETL---> DW

## ETL 任务
* 数据转换工具要能从各种不同的数据源中读取数据。
* 合并多个数据源的数据：ODS -> DW
* 数据脱敏
  - 敏感信息处理：电话号码/地址
  - 属性筛选：选择需要的字段
* 数据清洗
  - 数据类型
  - 字符集
  - 粒度：生成衍生字段
* 数据质量
 - 脏数据
* 数据断档
* 增量 ETL
* 工作流


# 调度工具
* CTM(Control-M)


BA


PL/SQL
缓慢变化维度




# 工具
* DataStage
* Kettle



* JDK1.8
* Maven
* Eclipse
* PL/SQL & Oracle Client & PL/SQL Developer
* IQ数据库
* Sybase PowerDesigner



# CI: 持续集成
* jenkins


# ETL是什么
1. 抽取：从不同的数据源（MySQL/Oracle/CSV）获取数据，为转换提供数据。
2. 转换：在抽取和加载之间，任何对数据的处理过程都是转换。常见的操作：
 * 数据质量：根据规则验证数据（数据类型/值域/编码）
 * 数据内容和数据结构的修改
 * 集成多个数据源的数据
 * 根据处理后的数据计算派生值和聚集值
3. 加载：将数据加载到目标系统

# 分表

表名_yyyymm

log_201901
log_201902

视图

# 参考文献
* [ETL](https://baike.baidu.com/item/ETL/1251949)
