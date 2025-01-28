# WoodQ-OJ
一个oj在线判题项目
## 项目介绍
基于go fiber后端+vue前端+Docker的编程题目评测系统，系统可以根据预设的题目用例对用户的代码进行执行和评测

### 后端技术栈
fiber框架+viper配置管理+air热更新+jwt鉴权+gorm数据库orm+goswag接口文档管理+postgreSQl数据库

### 前端技术栈
arco design组件库+vue框架+vue router路由管理+Manaco Editor开源代码编辑器+ByteMD Markdown文本编辑器

### 代码沙箱判题
用开源项目go-judge [地址](<https://github.com/criyle/go-judge>)

## 使用
### docker compose直接使用
拉取代码到本地后直接
```
docker-compose up --build
```
