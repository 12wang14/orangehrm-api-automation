# orangehrm-api-automation
OrangeHRM API testing project based on Postman
# OrangeHRM Postman API Test Project

## 项目介绍

基于 OrangeHRM 开源人事管理系统，使用 Postman
完成接口调试、环境变量配置和接口自动化断言。

## 测试内容

- 登录成功测试
- 错误密码登录测试
- 员工列表查询
- 新增员工
- 员工详情查询
- HTTP 状态码断言
- 响应字段断言
- 响应时间断言
- 动态 CSRF Token 获取
- 接口间变量传递

## 技术工具

- Postman
- JavaScript
- HTTP/HTTPS
- REST API
- GitHub

## 项目地址

测试环境：

https://opensource-demo.orangehrmlive.com/web/index.php/auth/login

## 运行说明

1. 导入 `OrangeHRM-API-Test.postman_collection.json`
2. 创建并选择 OrangeHRM 测试环境
3. 配置 `base_url`、`username`、`password`
4. 先执行登录接口
5. 再执行员工查询、新增和详情接口
