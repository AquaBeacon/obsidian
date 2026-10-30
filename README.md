# AquaBeacon Obsidian

設計・実験・解析の知識を蓄積し、関連資料につなぐ共有ナレッジベースです。

- [知識のホーム](knowledge/ホーム.md)
- [使い方](knowledge/使い方.md)
- [ノート構成](knowledge/README.md)
- [分野別索引](knowledge/maps/)
- [出典付き知識](knowledge/notes/)
- [一覧](knowledge/views/知識一覧.base)・[関係図](knowledge/知識マップ.canvas)

## Obsidianで開く

各リポジトリを同じ親フォルダに配置します。取得方法と配置は[workspace-tools](https://github.com/AquaBeacon/workspace-tools)を参照してください。

```sh
git clone https://github.com/AquaBeacon/obsidian.git
python workspace-tools/obsidian.py configure
python workspace-tools/obsidian.py check
```

Obsidianで親のAquaBeacon-OSS全体を保管庫として開き、obsidian/knowledge/ホーム.mdへ進みます。このリポジトリだけを開くと、兄弟プロジェクトへのリンクは解決しません。標準機能のみ使用し、追加プラグインは不要です。

共有ノート・テンプレート・Bases・Canvasはこのリポジトリで管理します。個人メモ・日誌・添付の保存先knowledge/private/と親の.obsidian/はGit公開対象外です。個人メモのバックアップ・クラウド同期は別途管理してください。

2026-10-31にdocs/knowledgeから分離しました。設計・実装の正本は各プロジェクトに残します。リンク先のローカル解析結果や生データは、このリポジトリに含みません。

[開発・検証](DEVELOPMENT.md)・[Apache-2.0](LICENSE)・[第三者の権利](THIRD_PARTY.md)
