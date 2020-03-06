# BASE64格式訂閱連結編輯器 (小火箭訂閱鏈接編輯器)
一個可以生成和修改ShadowRocket (iOS)、v2rayNG (Android)訂閱連結的工具。

## 網址
<https://www.phlinhng.com/b64-url-editor>

## 支持的協議
+ v2Ray (`vmess://...`)：支持TCP、WS、KCP三種連接方式
+ Trojan-GFW (`trojan://...`)
+ Shadowsocks (`ss://...`)：支持所有加密方式

## 功能
1. 導入格式：訂閱連結、節點列表、BASE64 Cipher
2. 修改節點名稱、服務器地址、加密方式(ss)、密碼(ss,trojan)、連接方式(v2ray)、TLS(v2ray)、WS域名與路徑(v2ray)等
3. 新增、刪除節點
4. 合併節點列表

## 用法
### 手動導入訂閱鏈接
只能導入一個訂閱鏈接
### 手動添加節點列表
支持添加多個節點，不同節點間使用換行(`\n`)、逗號(`,`)或分號(`;`)隔開。
### 手動添加BASE64密文
### URL Query導入訂閱鏈接
```
https://www.phlinhng.com/b64-url-editor?sub=[your subscrption links]
```
設置`qrcode=yes`可以自動顯示二維碼
```
https://www.phlinhng.com/b64-url-editor?sub=[your subscrption links]&qrcode=yes
```

## todo
+ [x] 新增節點
+ [x] 生成QR Code
+ [ ] 生成訂閱鏈接 (需要api與服務器)
+ [x] 完善URL Query
+ [ ] 完善一鍵粘貼
+ [ ] 調換節點順序
+ [ ] 多個訂閱連結合併
+ [ ] 完成README.md
+ [ ] 寫一篇博客文章
