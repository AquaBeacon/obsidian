# 開発と検証

親フォルダにworkspace-toolsと関連リポジトリを配置し、親全体を保管庫として使用します。

```sh
python workspace-tools/obsidian.py configure
python workspace-tools/obsidian.py check
python workspace-tools/workspace.py check
```

リンク検証は共有MarkdownとCanvasを対象にします。個人メモ・テンプレート内の未作成リンクは対象外です。Obsidianの画面描画は別に確認してください。

公開前にgit diff --cachedとgit ls-filesで公開対象を確認します。knowledge/private/や個人設定を強制追加しないでください。
