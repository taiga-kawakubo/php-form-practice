# php-form-practice

## 概要
COACHTECH 教材 Tutorial 7-4「フォームとデータ受け渡し ハンズオン演習」で作成した成果物です。
ユーザーの名前、メールアドレス、年齢の送信フォーム、送信内容確認画面、登録完了画面の作成。

## 使用技術
- PHP 8.2
- HTML5（フォーム要素）

## 学んだこと
- フォームで入力された情報を次の画面に引き継ぐための方法。具体的には、actionでデータの引き継ぎ先のファイルを指定すること、methodを使用してgetなのかpostなのかを指定すること。
- 前の情報を引き継ぐためには、変数を使用すること。変数の定義は、$_method名(”name名”)となる。
- onclickの使用方法。JavaScriptの実行の際に使用。ex:onclick="history.back()"
- input.phpのラベルタグを最初は<br>で改行していたが、<p>タグで一つにすることで適切なスペースが入るようになった。画面に応じたタグの考え方が必要である。

## 動作確認
- Docker環境が起動していることを確認（docker compose up -d）
ブラウザで [http://localhost:8000/7-4-3_hands-on/practice/input.php](http://localhost:8000/7-4-3_hands-on/practice/input.php) を開く
- 入力→確認→完了の流れを確認
- 入力画面で名前・メールアドレス・年齢を入力
- 確認画面で入力内容が正しく表示される
- 完了画面に名前とメールアドレスが表示される

## 詰まったポイントと解決方法
- HTMLの内容で忘れている箇所があった。tebleの作成方法など
- htmlspecialchars()の使い方について、変数を使用する際に記載する必要があるということが理解不足だった。解決方法は教材の確認。


## 開発の工夫
- htmlspecialchars()を用いてセキュリティを高めたこと。
- 年齢の入力の際に最小値と最大値を設けたこと。

## 動作確認のスクショ

https://github.com/user-attachments/assets/8e4393c4-ebdb-4f01-9bc9-22f53f9cfd3e

https://github.com/user-attachments/assets/34072834-ee9b-4a73-96be-e14a4e9b97bf" /

https://github.com/user-attachments/assets/51e00a8b-03b3-4122-aa1e-cddaef5fb7ba" /

