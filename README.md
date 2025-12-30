# luwa-ul

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Advanced Underlining and Highlighting for LuaLaTeX / 縦書き・ルビ対応の下線・ハイライトパッケージ**

---

## Overview / 概要

`luwa-ul` provides robust underlining and highlighting functionality. Unlike standard methods, these decorations remain intact even in vertical writing environments and when used alongside ruby (furigana), math mode, and other complex layouts.
`luwa-ul` は、高度な下線およびハイライト機能を提供します。従来のパッケージとは異なり、縦書き環境や、ルビ（ふりがな）・数式などが混在する複雑なレイアウトでも崩れることなく描画されます。

- **Version**: 1.2.1
- **Date**: 2025-12-28
- **Author**: Kosei Kawaguchi (a.k.a. KKTeX)
- **License**: MIT（LPPL 1.3c から変更）
- **Repository**: [https://github.com/KKTeX/luwa-ul](https://github.com/KKTeX/luwa-ul)
- **Support**: p.c.aces1056@gmail.com

---

## Key Features / 特徴

- **Vertical Writing Support / 縦書き完全対応**
  - Maintains correct appearance and position in Japanese vertical writing (tate-gaki).
  - 日本語の縦書き環境でも、正しい位置と外観で下線やハイライトを維持します。

- **Compatibility with Ruby and Math / ルビや数式との共存**
  - Works seamlessly even when characters have ruby (furigana) or include mathematical symbols.
  - ルビが付いた文字や、数式モードが含まれる箇所でもシームレスに動作します。

- **Flexible Highlighting / 柔軟な装飾**
  - High-quality visual results powered by `lua-ul` and `tikz`.
  - `lua-ul` と `tikz` を活用した、高品質な装飾結果を提供します。

---

## Prerequisites / 前提条件

> This package is **LuaLaTeX-only**.  
> 本パッケージは **LuaLaTeX専用** です。

**Dependencies / 依存パッケージ:**
- `luacolor`, `xcolor`, `lua-ul`, `calc`, `tikz`

---

## Usage / 使用方法

For detailed usage and examples, please refer to the documentation file: `luwa-ul-doc.tex`.
具体的な使用方法や例については、ドキュメントファイル `luwa-ul-doc.tex` を参照してください。

---

## License / ライセンス

This package is licensed under the **MIT License**.
本パッケージは **MITライセンス** のもとで公開されています。

```text
Copyright (c) 2025 Kosei Kawaguchi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.