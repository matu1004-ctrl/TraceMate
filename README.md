# Trace Mate

Maya 向けアニメーション学習ヘルパー（Windows）。

ソースコードは非公開です。配布物はコンパイル済みの `.pyc` とインストーラのみです。

![作業画面の例](docs/images/03_overview_dual.jpg)

## マニュアル

👉 **[使い方マニュアル（第1稿）](docs/manual.md)**

## ダウンロード（必須）

> **緑の Code → Download ZIP は使わないでください。**  
> あれは説明用リポジトリの一式で、Maya 年号別の本体ではありません。  
> **必ず [Releases](https://github.com/matu1004-ctrl/TraceMate/releases/latest) から、自分の Maya 年の zip を取ってください。**

| Maya | ダウンロード |
|------|----------------|
| 2025 | [TraceMate_Maya2025_Windows.zip](https://github.com/matu1004-ctrl/TraceMate/releases/latest/download/TraceMate_Maya2025_Windows.zip) |
| 2026 | [TraceMate_Maya2026_Windows.zip](https://github.com/matu1004-ctrl/TraceMate/releases/latest/download/TraceMate_Maya2026_Windows.zip) |
| 2027 | [TraceMate_Maya2027_Windows.zip](https://github.com/matu1004-ctrl/TraceMate/releases/latest/download/TraceMate_Maya2027_Windows.zip) |

`.pyc` はバージョン専用です。違う年の zip では `bad magic number` などで動きません。

Maya の年が分からないときは、Script Editor（Python）で次を実行してください。

```python
import sys
print(sys.version)
```

- `3.11...` → 2025 または 2026  
- `3.13...` → 2027  

## インストール

1. 上記の **年別 zip** を解凍する  
2. フォルダ内の **`install.mel` を Maya のビューポートへドラッグ＆ドロップ**  
3. シェルフに **TM** ボタンが追加される  
4. ボタンを押して起動  

![シェルフの TM](docs/images/01_shelf_tm.png)

コピー先の例:

`Documents\maya\<バージョン>\ja_JP\scripts\TraceMate\`

## 注意

- 改変したものを再配布しないでください（[LICENSE](LICENSE) 参照）  
- アンインストール: 上記 `TraceMate` フォルダを削除し、シェルフの TM ボタンを削除  

## ライセンス

[LICENSE](LICENSE) を参照してください。個人・商用の利用は可。ソースの公開・改変版の配布は不可です。
