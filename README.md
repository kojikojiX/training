# 新人研修 3回目(CARAVAN)
## 始めに
- **当研修課題についての質問はNGです。ご了承お願いします。**
  - 特に、エラーの1個目が「サーバーが起動できない」というものですが、きちんとご自身で解決に努めて下さい。

## 研修内容について
- このアプリケーションは、CARAVANにいくつかのエラーを仕込んだものです。
  - 下に示されている計8個のエラーが起こりますので、
    - どういうエラーか
    - どこに解決の糸口が書いてあるのか
    - どこを修正すれば良いのか
  - を説明できるよう、実際に動かしてしっかり確認して下さい。
- 加えて、以下の内容を説明できるようにしておいてください。
  - ストロングパラメーター
  - private, protectedの意味
  - `〇〇_path`について 
    - `rails routes`の見方
    - 引数()が必要なのはどんなときか、なぜ必要なのか

## エラー箇所
### サーバー起動時
1. `rails s -b 0.0.0.0`が出来ない

### /blogs
2. SyntaxError
3. NoMethodError
4. ActionController::UrlGenerationError

### /blogs/new
5. SyntaxError
6. 投稿後、NameError

### /blogs/1/edit
7. ActionController::UnknownFormat
8. ArgumentError