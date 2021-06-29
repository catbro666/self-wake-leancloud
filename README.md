# self-wake-leancloud

解决**因流控原因，通过定时任务唤醒体验版实例失败，建议升级至标准版云引擎实例避免休眠**。

操作步骤非常简单，你只需要轻点几次鼠标即可。

# 操作步骤

1. fork 本仓库
2. 然后在 `Settings-Secrets`里面添加一个秘密变量，取名`LEADCLOUDSITE`，值为你的leancloud部署环境的地址，也即`ADMIN_URL`。
3. star 自己的仓库，触发第一次workflow
