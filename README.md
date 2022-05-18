**English** [简体中文](README-zhCN.md)

# OpenType Math Fonts (TTF)

OpenType math fonts from the TeX community.

Converted to TrueType outline with `otf2ttf` from [AFDKO](https://github.com/adobe-type-tools/afdko). The fonts work perfectly with Microsoft Word.

## Specimen

[XeLaTeX PDF](specimen/xelatex.pdf)

[Microsoft Word PDF](specimen/msword.pdf)

## Download

### 1. Download a Single Font

Download from [`font/`](font/).

### 2. Download from the Release Page

[Click here](https://github.com/CyanoHao/OpenType-MATH-TTF/releases)

### 3. Clone the Repository with Git

```bash
git clone https://github.com/CyanoHao/OpenType-MATH-TTF.git --branch=master --depth=1
```

## Font List

| Font name                      | Version & Date     | License  |
| ------------------------------ | ------------------ | -------- |
| Asana Math                     | 000.958 2019-04-14 | SIL OFL  |
| Erewhon Math                   | 0.47 2021-09-26    | SIL OFL  |
| Fira Math                      | 0.3.4 2020-10-15   | SIL OFL  |
| Garamond-Math                  | 2019-08-16         | SIL OFL  |
| GFS Neohellenic Math           | 1.0.1 2018-03-08   | SIL OFL  |
| KpMath (Family)                | 0.40 2021-10-04    | SIL OFL  |
| Libertinus Math                | 7.040 2021-02-26   | SIL OFL  |
| STIX Math                      | 1.1.3 2018-04-17   | SIL OFL  |
| STIX Two Math                  | 2.12 2021-03-26    | SIL OFL  |
| XITS Math (Family)             | 1.302 2020-07-02   | SIL OFL  |

| Font name                      | Version & Date     | License  |
| ------------------------------ | ------------------ | -------- |
| Latin Modern Math              | 1.959 2014-09-05   | GFL      |
| NewComputerModernMath (Family) | 3.93 2021-10-20    | GFL      |
| TeX Gyre Bonum Math            | 1.005 2014-09-05   | GFL      |
| TeX Gyre DejaVu Math           | 1.106 2016-05-19   | GFL      |
| TeX Gyre Pagella Math          | 1.632 2018-06-15   | GFL      |
| TeX Gyre Schola Math           | 1.533 2014-09-05   | GFL      |
| TeX Gyre Termes Math           | 1.543 2014-09-15   | GFL      |

Notes:

1. Times-like math fonts (ordered by similarity to Times New Roman)：
   * XITS Math / STIX Math (high quality; XITS covers larger character set)
   * TeX Gyre Termes
   * STIX Two (fully optimised, but slightly different)
1. KpMath and XITS Math have standalone Bold style. To embolden the entire equation, choose “KpMath Bold” or “XITS Math Bold”; to embolden some symbols, choose the regular style and click the “B” (embolden) button.
1. NewComputerModern’s Book style is slightly bolder than Regular.

## Changelog

### 2022-05-19

Initial public release on GitHub.
