# Kronb

Kronb 是基于 Krona One 的独立、非官方字重扩展。它保留了原作宽阔的字形和较小的笔画粗细对比，提供从 300 到 700 的五档静态字重。

Kronb is an independent, unofficial weight extension of Krona One. It brings this wide, low-contrast sans-serif to five static weights, from 300 to 700. [Krona One on Google Fonts](https://fonts.google.com/specimen/Krona+One)

<a name="preview"></a>

## 预览 / Preview

https://github.com/user-attachments/assets/f1d15b11-8c71-47c9-988e-e6039ce9c193

[宣传片 / Film (MP4, 11.5 s)](media/kronb-five-weights.mp4) · [查看全部 8 张字符对照图 / Browse all eight character sheets](specimens/README.md)

## 为什么叫 Kronb？ / Why Kronb?

原作的许可证将 **Krona** 和 **Krona One** 列为保留字体名称，因此这套独立扩展以 **Kronb** 发布。新名字保留了 `Kro` 开头，安装后在字体菜单里输入 `kro` 就能找到。

The original font’s license reserves the names **Krona** and **Krona One**, so this independent extension is released as **Kronb**. The name keeps the `Kro` prefix so you can find it by typing `kro` in your font menu. [原作许可证 / Original license](https://github.com/google/fonts/blob/main/ofl/kronaone/OFL.txt)

<a name="selected-glyphs"></a>

## 代表字符 / Selected glyphs

每一行都是同一个字符，从左到右由细到粗。带底色的 600 一栏是原版 Krona One 的字形。

Each row shows the same glyph from Light 300 to Bold 700. The shaded 600 column shows the original Krona One drawing.

<a href="specimens/selected-glyphs.png"><img src="specimens/selected-glyphs.png" width="580" alt="15 个代表字符在五档字重下的对照 / Fifteen letters, numerals, ligatures and symbols in five weights"></a>

<a name="weights"></a>

## 字重 / Weights

| 字重 / Weight | 样式 / Style |
| --- | --- |
| 300 | 细体 / Light |
| 400 | 常规 / Regular |
| 500 | 中等 / Medium |
| 600 | 半粗 / SemiBold |
| 700 | 粗体 / Bold |

Krona One 原本只有 Regular（400）一款。Kronb 把原作字形放在 **SemiBold 600** 这一档，沿用它的轮廓、字距和渲染数据，并调整了字体名称和字重标记，让它在菜单中归入 Kronb 家族。300、400、500 和 700 是基于原作设计的四档新字重。

Krona One originally came in a single Regular (400) style. Kronb uses that drawing for **SemiBold 600**, preserving its outlines, spacing and rendering tables. The installation name and weight metadata place it in the Kronb family. Light, Regular, Medium and Bold are the four new weights based on the original.

<a name="install"></a>

## 安装与使用 / Installation

**桌面 / Desktop**

安装 [TTF 文件夹](ttf)中的五个文件，在设计软件的字体菜单里选择 **Kronb**。部分较旧的软件会将 Light、Medium 和 SemiBold 显示为单独的字体家族。

Install all five files in the [TTF folder](ttf), then choose **Kronb** in your app’s font menu. Some older apps list Light, Medium and SemiBold as separate families.

**网页 / Web**

使用 [WOFF2 文件夹](woff2)中的文件，每个文件对应一条 `@font-face` 声明，`font-weight` 取上表中对应的数值。以下是 400 的写法。

Use one `@font-face` rule for each file in the [WOFF2 folder](woff2), with the weight from the table above. Here’s the rule for Regular 400.

```css
@font-face {
  font-family: Kronb;
  src: url("woff2/Kronb-Regular.woff2") format("woff2");
  font-style: normal;
  font-weight: 400;
  font-display: swap;
}
```

[下载字体包 / Download the font package](https://github.com/BakalaStudio/kronb-font/releases/latest)（TTF + WOFF2）

如需整个仓库，请选择 **Code → Download ZIP**。To download the whole repository, choose **Code → Download ZIP**.

<a name="credits-and-license"></a>

## 署名与许可 / Credits and license

- **Krona One** 由 Yvonne Schüttler 设计，Eben Sorkin 负责字距和字体成品制作。Designed by Yvonne Schüttler, with spacing and mastering by Eben Sorkin. © 2011 Sorkin Type Co. [原作与许可 / Upstream source and license](https://github.com/google/fonts/tree/main/ofl/kronaone)
- **Kronb** 的新增字重由 Ma Rui 设计。New weight design by Ma Rui.
- **许可证 / License**　Kronb 采用 SIL 开放字体许可证 1.1。Kronb is licensed under the [SIL Open Font License 1.1](OFL.txt).
