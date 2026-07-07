# Twitch Vertical View

縦長モニター向けの自分用 Twitch 同時視聴ページです。

レイアウト:

```text
┌──────────────────────┐
│      Twitch ①        │
│       大きめ         │
├──────────┬───────────┤
│ Twitch②  │ Twitch③   │
├──────────┼───────────┤
│ Chat A   │ Chat B    │
└──────────┴───────────┘
```

## GitHub Pages で公開

1. GitHub で新しいリポジトリを作成
2. このフォルダの `index.html` をアップロード
3. リポジトリの **Settings** → **Pages**
4. **Build and deployment** の Source を **Deploy from a branch**
5. Branch を **main**、Folder を **/(root)** にして Save
6. 表示された `https://ユーザー名.github.io/リポジトリ名/` を開く

## 機能

- 上段にメイン配信①
- 中段に配信②・③
- 下段にコメント2列
- 左右コメントは①②③から選択
- 設定をブラウザに保存
- ①↔② / ①↔③ の入れ替え
- 全画面表示
- Twitch URL入力にも対応

## 注意

Twitch埋め込みは HTTPS と `parent` ドメイン指定が必要です。このページは公開先のホスト名を自動で `parent` に使うため、GitHub Pages 上で利用してください。
