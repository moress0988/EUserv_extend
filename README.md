# EUserv_extend
使用Github Action自动续期EUserv免费IPv6 VPS脚本

## 说明

自动获取账号内所有的VPS项目，并检测是否需要续期，需要续期会自动续期。

## 使用说明


1、Fork 本仓库，然后点击你的仓库右上角的 Settings，找到 Secrets 这一项，添加两个秘密环境变量`USERNAME`和`PASSWORD`。支持同时添加多个帐户，数据之间用单个空格 ` ` 隔开即可，帐户名和帐户密码需一一对应。**之前是用半角逗号分割的，更换成空格后，更新脚本后记得修改原变量的值**

```
USERNAME: 你的EUserv账户邮箱或Customer ID 第二个账户
PASSWORD: 第一个账户密码 第二个账户密码
```

