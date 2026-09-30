# RR3 165Hz Unlock

适配 Rush Rally 3 满帧率运行（165Hz）的 LSPosed 模块。

## 功能介绍

- 仅针对 Rush Rally 3（`brownmonster.app.game.rushrally3`）。
- 将 GameSpace 对该游戏发出的 60Hz 刷新率请求替换为 165Hz。
- 不修改游戏 APK、系统文件或其他游戏的刷新率设置。
- 停用模块并重启手机即可恢复原状。

## 使用方法

1. 手机需要已安装并可正常使用 LSPosed。
2. 从本仓库的 [Releases](../../releases) 下载正式签名 APK 并安装。
3. 在 LSPosed 中启用 **RR3 165Hz Unlock**。
4. 模块作用域只勾选 **系统框架（android）**。
5. 重启手机。
6. 通过游戏空间启动 Rush Rally 3。

## 适用环境

- 软件版本：1.0.0
- Android 11 及以上。
- 目标游戏：Rush Rally 3，包名 `brownmonster.app.game.rushrally3`。
- 当前实现针对 OnePlus 15 / ColorOS 中已确认的刷新率策略：ID 2 对应 60Hz，ID 7 对应 165Hz。
- 系统 OTA 可能改变内部接口；其他品牌或其他 ColorOS 版本不保证兼容。

## 下载校验

版本 1.0.0 APK 的 SHA-256：

`AACE5026F39E9A9F5F540C38FC77BD0FA9EAE7C59BDBCC5DBA62956D09765F6C`

## 注意事项

- 这是作用于系统框架的 LSPosed 模块，启用前请确认已掌握 LSPosed 安全模式或救砖方法。
- 实际帧率仍可能受到屏幕模式、温度、电量、亮度、游戏性能和系统策略限制。
- 如果启用后出现异常，请立即停用模块并重启手机。

## 卸载与恢复

在 LSPosed 中停用模块并重启手机即可恢复；之后可以按需卸载 APK。
