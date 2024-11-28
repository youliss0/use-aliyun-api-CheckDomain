## 使用python调用阿里云API查询域名是否可注册
注：调用 CheckDomain 接口时有频率限制，单用户限制为 10QPS，接口总量限制为 100QPS
## 运行环境
+ python 3.7+
## 安装方式
```
 pip install alibabacloud_domain20180129==4.0.0
```
## 运行结果
```
2024-11-28 09:04:00 - 261111.xyz - 不可注册
2024-11-28 09:04:01 - 261111.xyz - 不可注册
2024-11-28 09:04:02 - 261111.xyz - 不可注册
2024-11-28 09:04:03 - 261111.xyz - 不可注册
2024-11-28 09:04:04 - 261111.xyz - 不可注册
```
## 使用方式
填入你自己的RAM账号，修改需要查询的域名。
