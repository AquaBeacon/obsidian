# AquaBeacon ナレッジベース

思いつきをため、調べたことをつなぎ、設計・実験・説明に再利用するためのObsidianノートです。

- [ホーム](ホーム.md)：分野別の入口、知識一覧、関係図。
- [使い方](使い方.md)：短いメモから育てる方法、テンプレート、検索。
- [リポジトリ一覧](リポジトリ一覧.md)：19プロジェクトの役割と設計元。
- `maps/`：分野別の索引。
- `notes/`：出典付きの再利用できる知識。
- `templates/`：メモ・知識・調査・実験・判断・日誌の型。
- `views/知識一覧.base`：メモを状態・種類別に探す一覧。
- `知識マップ.canvas`：分野の関係を自由に配置できる図。
- `private/`：自由メモ・資料・実験記録・日誌・添付。Git公開対象外。

## 初めて開く

親の `AquaBeacon-OSS` で次を実行します。

```sh
python workspace-tools/obsidian.py configure
python workspace-tools/obsidian.py check
```

Obsidianの「保管庫としてフォルダを開く」で、**親の `AquaBeacon-OSS` フォルダ全体**を選び、`obsidian/knowledge/ホーム.md` を開きます。このobsidianリポジトリだけを保管庫にすると、兄弟リポジトリへのリンクは解決しません。配置は [workspace-toolsの台帳](https://github.com/AquaBeacon/workspace-tools) に従います。

設定は親の `.obsidian/` に生成され、既存の個人設定は保持します。標準機能のTemplates、Daily notes、Bases、Canvasなどを使用します。追加プラグインは不要です。通常の新規ノート・日誌・添付の保存先は `private/` です。

`private/` のGit除外は公開リポジトリへの混入を防ぐための設定です。Obsidian Syncや別のクラウド同期の公開範囲・バックアップ設定には連動しません。個人メモのバックアップ先は別途選んでください。

設計・実装の正本は各プロジェクトに残します。共有する知識は `notes/` にまとめ、出典と適用条件を記載します。既存の設計書を自動で書き換えたり、メモを自動公開したりする仕組みはありません。
