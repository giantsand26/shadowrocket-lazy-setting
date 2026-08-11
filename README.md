# Shadowrocket Lazy Safe Setting

小火箭懒人配置：国内 App/网站走国内直连，国外 App/网站走代理。

## 扫码打开配置

用手机扫码打开配置链接，然后在 Shadowrocket 里导入或复制使用。

![Shadowrocket 安全配置二维码](https://api.qrserver.com/v1/create-qr-code/?size=360x360&data=https%3A%2F%2Fraw.githubusercontent.com%2Fgiantsand26%2Fshadowrocket-lazy-setting%2Fmain%2Fshadowrocket-lazy-safe.conf)

## 配置链接

- Raw 链接：<https://raw.githubusercontent.com/giantsand26/shadowrocket-lazy-setting/main/shadowrocket-lazy-safe.conf>
- 仓库文件：<https://github.com/giantsand26/shadowrocket-lazy-setting/blob/main/shadowrocket-lazy-safe.conf>

## 安全说明

- 不包含节点、订阅地址、账号或密码。
- 不启用 HTTPS 解密，`[MITM] hostname =` 为空。
- 不启用 URL Rewrite 跳转重写。
- 国内规则优先直连，国外未命中流量最终走 `FINAL,PROXY`。
- 远程规则集保留，便于后续维护。

## 使用提醒

这份文件是规则配置，不自带代理节点。请先在 Shadowrocket 中添加可用节点或订阅，并确认代理策略 `PROXY` 可用。
