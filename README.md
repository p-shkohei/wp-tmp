# WordPress開発テンプレート

## 使用方法
###
### コマンド
開発環境モード：npm run dev

本番環境ファイルの出力：npm run build

### パスのエイリアス
@scss：'src/scss'

@image: 'src/images'

※CSSで背景画像を使用する際は、エイリアスを使用しないとコンパイルエラーが発生する場合があります。

## 実装処理
* CSSファイルの圧縮・ベンタープレフィックスの付与
* Babelで古いブラウザでも動作する「package.jsonのbrowserslistで変更可能」
* jQueryやGSAPなどの外部ライブラリを別ファイルとして出力
* 画像圧縮
* src/imagesディレクトリに画像をアップすると自動でpublicフォルダにコピーされる