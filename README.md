# STS2 Mod Manager

Slay the Spire 2（Steam版）のMODを、追加・有効/無効の切り替え・削除・更新できるツールの配布用リポジトリです。

## 入手

[最新リリース](https://github.com/Meltne/Sts2ModManager-Releases/releases/latest) から `Sts2ModManager.exe` を落として、そのまま起動してください。インストールは要りません。

一度起動すれば、次の版が出たときはソフトの中から更新できます。

## できること

- Nexus Mods で落とした ZIP / 7z / RAR をドラッグ＆ドロップで追加
- 有効 / 無効の切り替え（無効にしたMODは `mods_disabled` に移動）
- 削除（ごみ箱へ）
- MODの更新の確認と、ボタン一つでの更新
- MODの詳細表示（Nexus Mods の画像・説明・リンク）
- 前提MODの不足やバージョン不一致の注意表示

## 注意

- 署名していない exe なので、初回は「Windows によって PC が保護されました」と出ることがあります。「詳細情報」→「実行」で起動できます
- `SHA256SUMS.txt` は exe の中身の確認用です
