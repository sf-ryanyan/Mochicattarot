# 团子猫塔罗 · Mochi Cat Tarot

一个可爱的中英双语线上塔罗网站。完整 78 张塔罗牌，全部由一只圆滚滚的团子猫演出。

A cute, bilingual (Chinese / English) online tarot site. All 78 cards are drawn with one round, friendly mochi cat.


---

## 功能 Features

| 中文 | English |
|---|---|
| 完整 78 张牌：22 张大阿卡纳 + 56 张小阿卡纳，每张都有独立插画 | Full 78-card deck: 22 Major and 56 Minor Arcana, each with its own picture |
| 每张牌都有详细解读：画面说明、正位 / 逆位、感情 / 事业 / 金钱、3 条行动建议 | Detailed meaning for every card: the picture, upright and reversed, love, career, money, and 3 action tips |
| 不用打字：先选方面（综合、感情、事业学业、金钱），再选牌阵（一张牌、三张牌、二选一） | No typing: pick a topic (General, Love, Career & study, Money), then a spread (One card, Three cards, Two options) |
| 牌阵位置会跟着方面变，例如感情是「你 / 对方 / 关系」 | Card positions follow the topic, for example Love uses You / Them / The bond |
| 仪式感流程：洗牌 → 切牌 → 从展开的牌扇中选牌 → 自动翻牌 | Real ritual: shuffle, cut, pick from a card fan, and the cards turn over by themselves |
| 整体解读：把每张牌串起来看，并给出接下来可以做的事 | Overall reading that connects the cards and suggests next steps |
| 今日一牌：每天翻一张 | Card of the day |
| 塔罗图鉴：按大阿卡纳和四种花色浏览全部牌 | Card library by Major Arcana and the four suits |
| 认识塔罗：给新手的入门说明 | Tarot basics for beginners |
| 左上角一键切换中文 / 英文 | One-tap Chinese / English switch at the top left |
| 洗牌、切牌、选牌、翻牌都有动画；系统开启“减少动态效果”时会自动关闭 | Animations for every step, turned off automatically when the device asks for reduced motion |
| 手机和电脑都能用 | Works on phones and computers |

不需要注册、没有后台服务器、不收集个人资料。整个网站就是一个 HTML 文件。

No sign-up, no server, no tracking. The whole site is one HTML file.

---

## 部署到 GitHub Pages

1. 在 GitHub 新建一个仓库（Repository），名称填 `mochi-cat-tarot`，选择 **Public**。
2. 进入仓库，点 **Add file → Upload files**，上传 `index.html` 和 `README.md`，然后点 **Commit changes**。
3. 打开 **Settings → Pages**。
4. 在 **Build and deployment** 下：Source 选 **Deploy from a branch**，Branch 选 **main**，文件夹选 **/ (root)**，点 **Save**。
5. 等 1–2 分钟，网站就会出现在：`https://sf-ryanyan.github.io/mochi-cat-tarot/`

以后要更新网站，只需要重新上传新的 `index.html` 覆盖旧文件即可。

## Deploy to GitHub Pages

1. Create a new repository named `mochi-cat-tarot` and set it to **Public**.
2. Click **Add file → Upload files**, upload `index.html` and `README.md`, then click **Commit changes**.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, folder to **/ (root)**, then click **Save**.
5. Wait 1–2 minutes. Your site will be live at `https://sf-ryanyan.github.io/mochi-cat-tarot/`

To update the site later, upload a new `index.html` to replace the old one.

---

## 文件结构 Files

```
mochi-cat-tarot/
├── index.html   # 整个网站：页面、样式、程序、78 张牌的插画和解读
│                # The whole site: page, styles, code, all 78 card pictures and meanings
└── README.md    # 说明文件 This file
```

## 技术说明 Tech notes

- 纯 HTML / CSS / JavaScript，不用框架，不需要编译。Plain HTML, CSS and JavaScript. No framework, no build step.
- 所有牌面插画都是用代码画的 SVG，放大也清晰。All card art is SVG drawn in code, so it stays sharp at any size.
- 字体来自 Google Fonts：Fredoka、Nunito、ZCOOL KuaiLe。Fonts from Google Fonts: Fredoka, Nunito, ZCOOL KuaiLe.
- 浏览器只保存两样东西：你选的语言和今日一牌。The browser only saves your language choice and your card of the day.

## 怎么修改 How to edit

- **牌的解读文字**：在 `index.html` 里搜索牌名（例如 `圣杯三` 或 `Three of Cups`），直接修改文字即可。
  **Card text:** search for a card name in `index.html` (for example `Three of Cups`) and edit the text.
- **颜色**：在 `index.html` 最上面的 `<style>` 里，修改 `:root` 中的颜色变量（例如 `--gold`、`--night`）。
  **Colors:** change the color variables in `:root` at the top of the `<style>` block (for example `--gold`, `--night`).

---

## 免责声明 Disclaimer

团子猫塔罗仅供娱乐和自我反思参考，不能预测未来，也不能代替医疗、法律、财务等专业意见。遇到重大决定，请咨询专业人士。

Mochi Cat Tarot is for fun and self-reflection only. It cannot predict the future and does not replace medical, legal, or financial advice. For big decisions, please talk to a professional.

---

## 作者 Author

**Ryan Yan** · sfryanyan@gmail.com

© 2026 Ryan Yan. All rights reserved.
