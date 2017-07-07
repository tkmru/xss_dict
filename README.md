# xss辞書

Google 日本語入力用のXSS辞書。

## インストール方法
Google 日本語入力 辞書ツールを開いて新規辞書にインポートを選択してインポートする。

![image](./screenshot.png)

## 使い方
全角でｘ[数字]を打つとxssが変換候補が出る。

- ｘ１: 普通のやつ

- ｘ２: XSS Auditor Bypass

- ｘ３: XSS Auditor Bypass(Safari only)

- ｘ４: IE/Edge XSS Filter Bypass

- ｘ５: IE限定(vbs, CSSXSS)

ｘ２、ｘ３、ｘ４のBrowser's XSS Filter Bypassは [Browser's XSS Filter Bypass Cheat Sheet](https://github.com/masatokinugawa/filterbypass/wiki/Browser's-XSS-Filter-Bypass-Cheat-Sheet)のものを使っています。
