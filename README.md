<!--
> [!IMPORTANT]
> 本字体已经放弃维护。请您选用原版「思源黑体」或其他作者基于思源黑体衍生的字体。
-->
# 975 圆体 / 975 Yuan
A Chinese Font Derived from Source Han Sans, Swei Gothic, Chiron Go Round TC and WenYuan Rounded.   
一款基于「思源黑体」「狮尾圆体」「昭源环方」「文渊圆体」的中文字体。

## 简介
本字体最初在 [狮尾圆体](https://github.com/max32002/swei-gothic) 的基础上调整。在保持原有字符宽度的同时，缩小字面至 97.5%，并做少许加粗，使其更适合手机屏幕阅读。

2026 年 6 月，该字体汉字部分重制，以 [昭源环方](https://github.com/chiron-fonts/chiron-go-round-tc) 为主，[文渊圆体](https://github.com/takushun-wu/WenYuanFonts) 为辅。

西文搭配经过调整处理的 [Baloo 2](https://github.com/EkType/Baloo2) 字体。

目前只有简体中文（SC）版本。包含基本区和扩展 A 区所有汉字，以及扩展 B～E 区《通用规范汉字表》汉字（扩展区可能还包含一部分与增补部首区字符同形的字），满足 GB 18030-2022 实现级别 2 的收字范围。

## 预览
![](./documentation/975YUAN1.PNG)
![](./documentation/975YUAN2.PNG)
![](./documentation/975YUAN3.PNG)
![](./documentation/975YUAN4.PNG)
![](./documentation/975YUAN5.PNG)

## 注意事项
- 这不是一个专业的字体项目。
- 由于本字体西文部分原型 [Baloo 2](https://github.com/EkType/Baloo2) 只有从 Regular 到 Black 的较粗字重，因此本字体也只做较粗字重。
- 700W 作为 400W 的粗体，在 Office 等软件中需将字体切换到 400W 再点击「**Ｂ**」按钮切换到粗体调用（当然也可在字体名称框内直接输入「霞鹜975圆体SC 700W」）。
- 已知问题：
  - 在中文和西文合并的过程中，思源黑体原有的 OpenType 特性丢失，会导致纵向排版特性无法正常体现。 *（2020 年 9 月 2 日上传的版本已增加一部分符号的竖排特性。）*
  - ~字形（glyph）有偏左的问题。~  *（2020 年 9 月 2 日上传的版本已尝试解决。）*
  - 由于是两个不同标准写法字体的混合字体，因此会存在同一部件设计不统一的情况（如「釒」「心」「欠」等部件），本字体保留这些设计差异，统一部件设计工作量较大。
  - 对于引号、省略号、1 em 横线等中英文共用标点的取舍问题尚未解决。本字体引号采用 Unicode 16.0 标准化变体序列（Standardized Variation Sequences, SVS）在西文引号  `“‘’”` 和中文引号 `“︁‘︁’︁”︁` 之间选择，省略号和 1 em 横线（半破折号）使用西文字体的字符。
  - 在 Word（Microsoft 365）中，400 字重可能无法正常调用，~~「975 黑体」无此问题。~~ 该问题与字体的安装先后顺序有关，如果先安装 700W，再安装 400W，在 Word 中则只会调用先安装的粗体，「975 黑体」亦然。因此在安装过程中，需注意先安装 400W 常规体，后安装 700W 粗体和其他字重。

## 授权信息
本字体是基于开源字体 [思源黑体](https://github.com/Adobe-fonts/Source-han-sans) 及其衍生字体改造而成的衍生项目，遵循 [SIL Open Font License 1.1](https://openfontlicense.org/open-font-license-official-text/) 开源协议。
> [猫啃网](https://www.maoken.com/)提供 SIL Open Font License 1.1 非官方[简体中文译本](https://www.maoken.com/ofl)便于理解，仅供参考。

### 许可
- 这款字体无论是个人还是企业都可以自由使用，包括商用，无需付费，也无需另行知会原作者。（但如果告知，我会很感激。🫶）
- 这款字体可以自由传播、分享，或者将字体安装于系统、嵌入于软件或 APP 中也是允许的，可以与任何软件捆绑再分发以及／或一并销售。
- 这款字体可以自由修改、改造，制作衍生字体。修改或改造后的字体也必须同样遵守 [SIL Open Font License 1.1](https://openfontlicense.org/open-font-license-official-text/) 所规定的条款与条件。

### 限制
- 根据 OFL 1.1「许可与条件」中第 1 条的规定，**禁止单独出售字体文件**（OTF/TTF 格式文件）。
- 根据 OFL 1.1「许可与条件」中第 3 条的规定，在制作衍生字体时，未经作者明确的书面授权，字体名称不可使用原有字体的「保留名称」。本字体保留名称为：**霞鹜**（霞鶩）、**落霞孤鹜**（落霞孤鶩）、**LXGW**。基于本字体衍生的字体，未经作者（@lxgw）明确书面授权，名称不可出现上述字样。而在没有对字体源代码进行修改的情况下，重新编译的字体，可作为特例继续使用本字体保留名称；仅为网页端渲染优化（Web Font）之目的而对本字体进行子集化（Subsetting）或格式转换（如 WOFF/WOFF2），且不将其作为可安装的桌面字体文件提供给公众下载的情况下，同样适用该特例〔如 [Google Fonts](https://fonts.google.com) 等主流网页字体托管平台，或者 [ZSFT](https://fonts.zeoseven.com/) 等由作者（@lxgw）认可的第三方公益平台；其他平台如需适用此特例，请联系作者（@lxgw）确认〕。同时，根据第 4 条，未经作者（@lxgw）明确书面授权，本字体的任何衍生字体不得以作者（@lxgw）的名义推广、背书或宣传。
- 根据 OFL 1.1「许可与条件」中第 5 条的规定，该字体不可在 OFL 1.1 以外的授权许可下发行，亦不可将该字体与可能造成许可证冲突的其他协议字体（如 GNU GPL、IPA 等）混合至同一字体文件。

## 字体下载
1. 点击【Clone or download】->【Download ZIP】下载 ZIP 格式压缩包，或者在文件列表中选择想要的字体文件进行下载。
2. 进入 [Releases 页面](https://github.com/lxgw/975Yuan/releases) 下载。
3. 进入 [猫啃网](https://www.maoken.com/freefonts/6339.html) 下载，GitHub 项目更新后，会联系猫啃网站长进行同步更新。 **注意：** 其它收录免费商用字体的网站上可能也收录了本字体，但可能不是最新版。
4. [蓝奏云下载 ~~Magisk 模块~~，密码 axme](https://www.lanzoux.com/b0cqi47ng)

## 鸣谢
- [思源黑体 / Source Han Sans](https://github.com/adobe-fonts/source-han-sans) *by Adobe*
- [Noto Sans CJK](https://github.com/googlefonts/noto-cjk) *by Google*
- [狮尾圆体 / Swei Gothic](https://github.com/max32002/swei-gothic) *by Max Yao*
- [Baloo 2](https://github.com/EkType/Baloo2) *by EkType*
- [昭源环方](https://github.com/chiron-fonts/chiron-go-round-tc) *by tamcy*
- [文渊圆体](https://github.com/takushun-wu/WenYuanFonts) *by takushun*

## 相关项目
### 975 系列
- [975 黑体 / 975 Hei](https://github.com/lxgw/975hei)
### 更多开源字体
- [点击此处 / Click Here](https://github.com/lxgw/lxgw/blob/main/fonts.md)

## 联系作者

- **Telegram：** @lxgwtg
- **微信公众号：** 霞鹜 *（ID: lxgwshare）*
- **酷安：** [@落霞孤鹜lxgw](https://www.coolapk.com/u/633884)
- **微博：** [@孤鹜先森](https://weibo.com/6624339726)

