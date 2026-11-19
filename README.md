# Trace Mate

Maya 向けアニメーション支援ツール（Windows）。

ソースコードは非公開です。配布物はコンパイル済みの `.pyc` とインストーラのみです。

## 対応環境（このパッケージ）

| 項目 | 内容 |
|------|------|
| OS | Windows |
| Maya | **2026 / 2027** |
| その他 | 動かない場合は [Releases](../../releases) の説明を確認してください |

## インストール

1. このリポジトリを Clone / Download、または Releases の zip を解凍する  
2. フォルダ内の **`install.mel` を Maya のビューポートへドラッグ＆ドロップ**  
3. シェルフに **TraceMate** ボタンが追加される  
4. ボタンを押して起動

コピー先の例:

`Documents\maya\2026\ja_JP\scripts\TraceMate\`  
（Maya 2027 の場合はパス内の `2026` が `2027` になります）

## 使い方

シェルフの **TraceMate** を押すと UI が開きます。

## 注意

- `.pyc` は **ビルドした Maya のメジャーバージョン専用**です  
- 改変したものを再配布しないでください（[LICENSE](LICENSE) 参照）  
- アンインストール: 上記 `TraceMate` フォルダを削除し、シェルフの TraceMate ボタンを削除

## ライセンス

[LICENSE](LICENSE) を参照してください。個人・商用の利用は可。ソースの公開・改変版の配布は不可です。
