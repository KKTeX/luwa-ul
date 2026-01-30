# luwa-ul

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Advanced Underlining and Highlighting for LuaLaTeX / 縦書き・ルビ対応の下線・ハイライトパッケージ**

---

## Overview / 概要

`luwa-ul` provides robust underlining and highlighting functionality. Unlike standard methods, these decorations remain intact even in vertical writing environments and when used alongside ruby (furigana), math mode, and other complex layouts.
`luwa-ul` は、高度な下線およびハイライト機能を提供します。従来のパッケージとは異なり、縦書き環境や、ルビ（ふりがな）・数式などが混在する複雑なレイアウトでも崩れることなく描画されます。

- **Version**: 1.2.5
- **Date**: 2026-01-30
- **Author**: Kosei Kawaguchi (a.k.a. KKTeX)
- **License**: MIT
- **Repository**: [https://github.com/KKTeX/luwa-ul](https://github.com/KKTeX/luwa-ul)
- **Support**: p.c.aces1056@gmail.com

---

## Key Features / 特徴

- **Vertical Writing Support / 縦書き完全対応**
  - Maintains correct appearance and position in Japanese vertical writing (tate-gaki).
  - 日本語の縦書き環境でも、正しい位置と外観で下線やハイライトを維持します。

- **Compatibility with Ruby and Math / ルビや数式との共存**
  - Works seamlessly even when characters have ruby (furigana) or include mathematical symbols like `\frac, \int etc.`. When you use Auto series, line positions are automatically adjusted based on the depth and height of its argument.
  - ルビ（ふりがな）が付いた文字や、`\frac`・`\int` などの数式記号が含まれている場合でも、問題なく動作します。「Autoシリーズ」を使用すると、引数の高さや深さに応じて、下線の位置が自動的に最適化されます。

- **Flexible Highlighting / 柔軟な装飾**
  - High-quality visual results powered by `lua-ul` and `tikz`.
  - `lua-ul` と `tikz` を活用した、高品質な装飾結果を提供します。

---

## Prerequisites / 前提条件

> This package is **LuaLaTeX-only**.  
> 本パッケージは **LuaLaTeX専用** です。

**Dependencies / 依存パッケージ:**
- `luacolor`, `xcolor`, `lua-ul`, `calc`, `tikz`, `luatexja-adjust`

---

## Usage / 使用方法

For detailed usage and examples, please refer to the documentation file: `luwa-ul-doc.tex`.
具体的な使用方法や例については、ドキュメントファイル `luwa-ul-doc.tex` を参照してください。