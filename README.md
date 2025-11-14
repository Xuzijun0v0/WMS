# 仓库管理系统 (Warehouse Management System)

一个基于 **Java + Spring Boot + HTML/JS + MySQL**
开发的轻量级仓库管理系统，实现仓库的入库、出库、库存统计与数据管理等核心功能。

## 功能列表

-   用户管理（登录、权限）
-   商品管理（增删改查、分类）
-   入库管理（入库单、记录查询）
-   出库管理（出库流程、记录）
-   库存管理（实时库存、预警、流水）
-   报表统计（入库、出库、库存报表导出）
-   系统日志（操作日志、登录日志）

## 技术栈

-   后端：Java 17、Spring Boot
-   前端：HTML、CSS、JavaScript、jQuery
-   数据库：MySQL 8.0
-   构建工具：Maven

## 环境要求

-   JDK 17+
-   Maven 3.8+
-   MySQL 8.0+

## 运行步骤

``` bash
git clone <your-repo-url>
cd warehouse-system
mvn spring-boot:run
```

浏览器访问：`http://localhost:8080`
