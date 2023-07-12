# docker-VSCService

### 版本说明

| 版本      | CPU架构 |
| :-------- | :----- |
| koray2021/code-server:4.14.1-arm64 | arm64 |



### 目录结构

```shell
docker-VSCService/
├── .env     # 传参文件
├── docker-compose.yml    
└── README.md
```



### Compose传参说明

| 参数项       | 说明        | 传参方式          |
| ------------ | ----------- | ----------------- |
| \${password} | web登录密码 | \.env文件形式传参 |



