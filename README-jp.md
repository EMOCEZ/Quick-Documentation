# Quick-Documentation（クイック・ドキュメンテーション）
ドキュメントの作成は、本当に面倒な作業ですよね。

本プロジェクトでは、人工知能（AI）を活用してドキュメント作成をサポートしています。

[プレビュー](https://emocez.github.io/Quick-Documentation/?README)

[GitHubに戻る](https://github.com/EMOCEZ/Quick-Documentation/tree/main)

# ドキュメントの例
[呪われた黄金 (cursed gold)](https://emocez.github.io/Quick-Documentation/?cursedgold)

[円周率 (pi)](https://emocez.github.io/Quick-Documentation/?pi)

# 新しいドキュメントを投稿するには？

1. ページ上部の「Issues」タブをクリックし、「New Issue」（新しい課題）を選択します。

2. タイトル欄に、ドキュメントの短い英語名を入力してください（例: `ender-dragon`。英数字とハイフンのみ使用可能です）。

3. 本文エリアに、Markdown形式のコンテンツを直接貼り付けてください（標準的なMarkdown記法はすべてサポートされています）。

投稿を確認後、こちらで `ender-dragon.md` として保存し、デプロイを行います。完了すると、`?ender-dragon` というURLからそのドキュメントにアクセスできるようになります。

注意：リポジトリを整理された状態に保つため、ドキュメント内に `<script>` タグを含めないようにしてください（技術的には動作する可能性がありますが、削除させていただきます）。テキスト、画像、表のみを使用することをお勧めします。 # パーソナライズ
目次タイトルの横にある太陽と月のアイコンをクリックすると、ダークモードとライトモードを切り替えられます。また、長押しすることで背景画像をアップロードすることも可能です。

# クリエイター向け機能

## カード
```cards
呪われた金塊 | MOD紹介 | ?cursedgold | 🧊
pi | piの紹介 | ?pi | 🧊🧊🧊
```

## 警告

> [!WARNING]
> 「棍母（こんぼ）」襲来

> [!TIP]
> 「棍母（こんぼ）」襲来

> [!NOTE]
> 「棍母（こんぼ）」襲来

> [!DANGER]
> 「棍母（こんぼ）」襲来

> [!INFO]
> 「棍母（こんぼ）」襲来

## 引用
```embed
pi.md
```

## ステップ表示
```steps
依存関係のインストール
APIキーの設定
サンプルスクリプトの実行
ブラウザを開いて確認
```

## インラインバッジとキー表示
現在のバージョン {{badge:666}}

保存は [[Ctrl+S]]、取り消し（アンドゥ）は [[Ctrl+Z]] を押してください。
