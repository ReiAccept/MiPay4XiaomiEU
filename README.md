# MiPay4XiaomiEU

这是一个 KernelSU 模块，用于在各种 HyperOS 修改版中安装国行 HyperOS 的 NFC 服务

也就是 门卡 交通卡 车钥匙

注意，本应用还会恢复国行应用商店，如果不要的话可处以直接删除 module/system/app 中的 MIUISuperMarket

Tips: 为什么要恢复国行应用商店?
- 安装"钱包"应用
- 银联组件需要更新

若您移除了应用商店, 请手工安装以上两个应用

二进制文件提取于小米完整更新包

## 下载

Release 中的模块包按「提取的固件版本」命名，即 `MiPay4XiaomiEU-<固件版本>.zip`，例如：

- `MiPay4XiaomiEU-OS3.0.5.0.WNCCNXM.zip` (小米14)
- `MiPay4XiaomiEU-OS3.0.319.0.WBLCNXM.zip` (小米17 Pro)

Tips: 不一定需要严格对应版本和型号
- 有应用商店的情况下, 可以将应用更新到需要的版本, 提取应用此时更多是一个（包名对应+签名对应的占坑包）
- 不同包里面的组件其实都是一样的, 硬件差异在驱动层和固件层被封装了
- 如果不知道下什么版本, 建议下载小米14的包

## 提取ROM的机型

| 机型 | 代号 | 提取的固件版本 |
| --- | --- | --- |
| 小米14 | houji | OS3.0.5.0.WNCCNXM |
| 小米17 | pudding | OS3.0.319.0.WPCCNXM |
| 小米17 Pro | pandora | OS3.0.319.0.WBLCNXM |
| 小米17 Pro Max | popsicle | OS3.0.319.0.WPBCNXM |
| 小米17 Ultra | nezha | OS3.0.312.0.WPACNXM |


## 测试环境
 - 设备：小米14
 - 系统版本: OS3.0.5.0.WNCCNXM (xiaomi.eu)
 - KernelSU版本: 32179
 - KernelSU元模块: OverlayFS MetaModule
