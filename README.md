# Character Chat Avatars

ユーザー指定の4枚の正規顔アイコンを公開配信する静的リポジトリ。
各画像は160×160pxのRGBA PNG。今回提供された画像をそのままコピーし、顔の生成・補正・再設計・反転・再圧縮は行っていません。
元の添付ファイルは変更していません。画像の左右に関する設定や人格Canonを変更するものではありません。

公開先: https://numahikodaze-creator.github.io/character-chat-avatars/
GitHub Pagesはmainブランチのルートを配信元に使用します。APIサービス・DB・有料サービス・常駐サーバーは不要です。
URLは公開後にHTTPと画像内容を検証してください。URLの存在だけでは公開成功やChatGPT内の表示成功を意味しません。

## 出典と対応

2026-10-12の公開基盤作成依頼に添付された4枚を、指定された人物と画像の目視で対応付けました。旧TRPG用画像へ差し替えず、今回提供された円形アイコンを使用します。

|キャラクター|ユーザー添付名|公開画像|SHA-256|
|---|---|---|---|
|時代 雪|1000062785.png|[yuki.png](https://numahikodaze-creator.github.io/character-chat-avatars/avatars/yuki.png)|`b9af5016d27b837692316f800d34271bb214cc79eefbec1229c8b02107420729`|
|時代 夏|1000062786.png|[natsu.png](https://numahikodaze-creator.github.io/character-chat-avatars/avatars/natsu.png)|`4703a3662645eb79780b8fdf02cd93678e305850abee9c2b8b4415a5effacec8`|
|雨月 楓|1000062787.png|[kaede.png](https://numahikodaze-creator.github.io/character-chat-avatars/avatars/kaede.png)|`c4384edf2bb5fc8d62eeedabcbb346659d5ce1ed927d854e8fb9e0a7afb7e085`|
|葉山 桜花|1000062788.png|[ouka.png](https://numahikodaze-creator.github.io/character-chat-avatars/avatars/ouka.png)|`e522161c81b41e3ffacf7d045e3f712b170e0b8c4dda1b923c3def883466b292`|

表示色: 雪 #79D8F5 / 夏 #FFD93D / 楓 #C66A24 / 桜花 #FF80B8。
このリポジトリは画像・名前・公開運用情報のみを含み、PrivateリポジトリのTRPG記録・人物設定・セーブ・認証情報を含みません。

## ChatGPTでの表示試験

ユーザー提供のAsyncImage記法を使用する試験です。queryへ渡すURL文字列は画像検索用であり、URLの直接読込みを保証するものではありません。通常のMarkdownやHTMLとしての対応を保証しません。
Androidでの別画像による成功はユーザーからの報告です。この新規GitHub Pages画像での検索・表示成功は別途確認が必要です。新規画像が検索に現れない場合も、似た顔や生成画像で代用しないでください。
