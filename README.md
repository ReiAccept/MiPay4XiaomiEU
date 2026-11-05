# MiPay4XiaomiEU

这是一个 KernelSU 模块，用于在各种 HyperOS 修改版中安装国行 HyperOS 的 NFC 服务

也就是 门卡 交通卡 车钥匙

注意，本应用还会恢复国行应用商店，如果不要的话可处以直接删除 module/system/app 中的 MIUISuperMarket

Tips: 为什么要恢复国行应用商店?
- 安装"钱包"应用
- 银联组件需要更新

若您移除了应用商店, 请手工安装以上两个应用

二进制文件提取于小米完整更新包

## 测试环境
 - 设备：小米14
 - 系统版本: OS3.0.5.0.WNCCNXM (xiaomi.eu)
 - KernelSU版本: 32179
 - KernelSU元模块: OverlayFS MetaModule
