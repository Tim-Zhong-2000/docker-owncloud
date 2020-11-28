# owncloud一键部署
## 环境要求
docker
docker-compose

## 部署说明
1. 启动服务
```docker-compose up -d```

2. 进入owncloud面板，首次进入需要进行设置，新建管理员，数据库选择mysql，数据库用户`root`，数据库密码`password` **默认值，强烈建议修改**，数据库名`owncloud`，localhost替换成`db:3306`。

3. 安装完成

## 自定义
修改自定义内容请修改.env内容，不要直接修改docker-compose.yml。

owncloud外部访问端口:`OWNCLOUD_PORT` 默认值：8087
数据库密码:`MYSQL_ROOT_PASSWORD` 默认值：password
