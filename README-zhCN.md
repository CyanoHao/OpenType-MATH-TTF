[English](README.md) **简体中文**

# 数学字体 TTF

来自 TeX 社区的 OpenType 数学字体。

所有字体使用 [AFDKO](https://github.com/adobe-type-tools/afdko) 的 `otf2ttf` 工具转换成 TrueType 曲线格式，适合 Microsoft Word。

## 查看样张

[XeLaTeX PDF](specimen/xelatex.pdf)

[Microsoft Word PDF](specimen/msword.pdf)

## 下载方式

### 1. 下载单个字体文件

在 [`font/`](font/) 目录中选择需要的字体并下载。

### 2. 从发布页下载

[点击此链接](https://github.com/CyanoHao/OpenType-MATH-TTF/releases)

### 3. 用 Git 克隆此仓库

```bash
git clone https://github.com/CyanoHao/OpenType-MATH-TTF.git --branch=master --depth=1
```

## 字体列表

| 字体名                     | 版本号及更新时间   | 授权协议 |
| -------------------------- | ------------------ | -------- |
| Asana Math                 | 000.958 2019-04-14 | SIL OFL  |
| Erewhon Math               | 0.47 2021-09-26    | SIL OFL  |
| Fira Math                  | 0.3.4 2020-10-15   | SIL OFL  |
| Garamond-Math              | 2019-08-16         | SIL OFL  |
| GFS Neohellenic Math       | 1.0.1 2018-03-08   | SIL OFL  |
| KpMath 家族                | 0.40 2021-10-04    | SIL OFL  |
| Libertinus Math            | 7.040 2021-02-26   | SIL OFL  |
| STIX Math                  | 1.1.3 2018-04-17   | SIL OFL  |
| STIX Two Math              | 2.12 2021-03-26    | SIL OFL  |
| XITS Math 家族             | 1.302 2020-07-02   | SIL OFL  |

| 字体名                     | 版本号及更新时间   | 授权协议 |
| -------------------------- | ------------------ | -------- |
| Latin Modern Math          | 1.959 2014-09-05   | GFL      |
| NewComputerModernMath 家族 | 3.93 2021-10-20    | GFL      |
| TeX Gyre Bonum Math        | 1.005 2014-09-05   | GFL      |
| TeX Gyre DejaVu Math       | 1.106 2016-05-19   | GFL      |
| TeX Gyre Pagella Math      | 1.632 2018-06-15   | GFL      |
| TeX Gyre Schola Math       | 1.533 2014-09-05   | GFL      |
| TeX Gyre Termes Math       | 1.543 2014-09-15   | GFL      |

说明：

1. 如果格式要求 “公式使用 Times New Roman 字体”，可以选这几个 Times 风格的字体（按与 Times New Roman 的相似程度排序）：
   * XITS Math / STIX Math（质量较好，其中 XITS 字符集更完整）
   * TeX Gyre Termes（没有什么特别的优势）
   * STIX Two（全方位的优化版本，但细节上的差异稍大）
1. KpMath 和 XITS Math 有独立的粗体。如要要对整个公式使用粗体，请选择 “KpMath Bold” 或 “XITS Math Bold” 字体；如果只对个别符号使用粗体，请选择常规字体，用 “加粗” 按钮。
1. NewComputerModern 的 Book 字重比默认的 Regular 字重略粗一点，很适合补偿 Computer Modern 系列偏细的特性。

## 更新记录

### 2022 年 5 月 19 日

从 [Gitee](https://gitee.com/cyano/OpenType-MATH-TTF) 迁移到 GitHub。

### 2021 年 10 月 31 日

新增 KpMath 家族。
* KpMath Light
* KpMath Regular
* KpMath Semibold
* KpMath Bold
* KpMath Sans

随 CTAN 更新以下字体版本：

* Erewhon Math
* Fira Math
* Libertinus Math
* NewComputerModernMath
  * 增加 Book 字重
* STIX Two Math
* XITS Math

STEP 开发者移除了数学字体支持，本仓库也随之移除，建议换用 XITS Math。

### 2020 年 5 月 22 日

初次发布。
