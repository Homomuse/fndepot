# Homomuse 官方 fnOS 应用源

Homomuse 只做一件事——分享：把手机里的照片和视频生成一个链接，家人点开微信卡片就能看原图原视频。文件在离开手机前已上锁（本地加密），存在你自己的 NAS 上。

在飞牛 fnOS 的 FnDepot 客户端中添加源：

```
https://github.com/Homomuse/fndepot
```

即可看到并安装 **Momo · 回忆宝箱节点**。官网：https://homomuse.com

## 源内应用

| 应用 | 说明 |
| --- | --- |
| Momo · 回忆宝箱节点 | 把 Momo 养进你的 NAS，替你守着宝箱（谁也看不懂的密文）；支持 ARM64 与 x86_64（x86_64 灰度中，详见应用简介） |

## 维护提示

每次发布新版 Momo 后，需同步更新 `fnpack.json` 中对应版本的下载地址、SHA256 与文件大小（字节数）。
