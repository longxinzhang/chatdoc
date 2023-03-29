# ChatDoc

一个使用 `openai` 与文档对话的例子, 目前支持的文档类型 `.pdf`, `.epub`, `.md`, `.txt`, `.docx`, `web`

![preview](./preview.png)

## 启动后端

```shell
# my local python version 3.9.7
cd server
./start {OPEN_AI_KEY}

# 请在start文件中替换自己的api key
```

## 启动前端

```shell
# my local node version v16.11.0
# 需安装pnpm。mac用户使用 sudo npm install -g pnpm
# 局域网访问时如果无法加载pdf.js，请修改fastapi的跨域地址。

cd client
./start
```

## Docker

```shell
# 请先替换 docker-compose.yml 中的 OPEN_AI_KEY
docker-compose up
```
