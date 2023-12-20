# WordTest
こちらはWeb版の単語練習ソフトウェアです。

## 実装
### 実装済み
- 単語練習機能
  - データ読み込み:サンプルデータ(.json)
  - データ読み込み:ローカルデータ(.csv/.txt)
  - データ一覧の表示
- ローカルデータのサンプルのダウンロード
### 実装予定
- 単語練習機能
  - 問題・答え入れ替え機能

- ホームディレクトリ以外でリロードをすると404エラーになる→どこでリロードしてもエラーにならないように修正

## 開発者向け情報
### 開発環境
- プログラム言語: C#
- フレームワーク: Blazor wasm / .NET7.0

### 公開環境
- 公開場所: GitHub Pages

## 再現
### コマンドで動かす場合
1. .net7.0 sdk(dotnet)をダウンロードする。
2. 作業ファイルに移動
```shell
$ cd wordtest
```
3. watch runで実行する
```shell
$ dotnet watch run --pathbase=/wordtest
```
4. local hostで起動されます。
```shell
# http://localhost:5074/wordtest にブラウザでアクセス
```
