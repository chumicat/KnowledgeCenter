# 遠端瀏覽隔離 (RBI: Remote Browser Isolation)
- [官網](https://www.forcepoint.com/zh-hant/product/remote-browser-isolation)

### 情境 (Scenario)
使用者想要上網，又想要減少衝浪時的風險。使用者知道一些網站是可信任的 (白名單)；也知道一些惡名昭彰的網站 (黑名單)。然而，更多的是位於模糊地帶，未能歸類的網站。這些網站有著未知的風險，也充滿了重要的資訊，因此我們需要一套能在這種情況下提供保戶的方案，這就是 RBI。

### Pixel Mode / Crystal Mode
RBI 有 Pixel Mode 跟 Crystal Mode 兩種

#### Pixel Mode
該怎麼避免網站上的惡意攻擊、同時又能看到網站上的資訊？截圖！單純的圖片無法造成傷害。這就是 Pixel Mode 的原理

#### Crystal Mode
該怎麼避免網站上的惡意攻擊、同時又能看到網站上的資訊？話說，網站上能進行惡意攻擊的是什麼？Java Script！那麼把它停用吧。這就是 Pixel Mode 的原理

| | Pixel | Crystal
| --- | --- |
| 原理 | 截圖 | 停用/移除 JS |
| 速度 | 慢 | 快 |
| 問題 | 單純圖片,畫面中連結之類的東西能使用嗎？ | 有使用 JS 做 TAB 網站，內容還看得到嗎？ |

