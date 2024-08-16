<h1 align="center">TiebaSign-贴吧签到助手</h1>

# 使用

自动化执行任务: 百度贴吧每日签到
自动化运行时间: 北京时间 **凌晨02点** 以及 **下午18点**（可修改 时间差为+8）

❶  [Fork 仓库](https://github.com/yife68/TiebaSign)

❷  `仓库` → `Settings` → `Secrets` → `New repository secret`, 添加`Secrets`变量如下:

| Name  | Value                                                                                   |
|-------|-----------------------------------------------------------------------------------------|
| BDUSS | 百度贴吧BDUSS, 打开浏览器，登录 [百度贴吧](https://tieba.baidu.com/), 打开控制台 → 应用 → Cookie，复制 `BDUSS` 的值 |

❸  邮箱通知配置 `仓库` → `Settings` → `Secrets` → `New repository secret`, 添加`Secrets`变量如下:

| Name | Value                          |
|------|--------------------------------|
| HOST | SMTP服务器的主机地址                   |
| FROM | 发件人的邮箱地址                       |
| TO   | 收件人的邮箱地址，可以同时发送给多个收件人，用"#"进行分隔 |
| AUTH | 发件人的邮箱授权码或密码                   |

❹  `仓库` → `Actions`, 检查`Workflows`并启用

# 如何获取Cookie
百度贴吧BDUSS, 打开浏览器，登录 [百度贴吧](https://tieba.baidu.com/), 打开控制台 → 应用 → Cookie，复制 `BDUSS` 的值

# GitHub地址
项目直达链接：https://github.com/yife68/TiebaSign/
