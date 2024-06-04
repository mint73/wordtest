# WordTest
こちらは Web 版の単語練習ソフトウェアです。

## 実装
### 実装済み
- データ読み込み
  - サンプルデータ(`.json`)
  - ローカルデータ(`.csv`/`.txt`)
- データ一覧の表示
### 実装予定
- 問題・答え入れ替え機能

## 開発者向け情報
### 開発環境
- プログラム言語: C#
- フレームワーク: Blazor wasm / .NET8.0

### 公開環境
- 公開場所: GitHub Pages

## 再現
### コマンドで動かす場合
1. .net8.0 SDK をダウンロードする。
2. 作業ファイルに移動
```shell
$ cd wordtest
```
3. watch run で実行する
```shell
$ dotnet watch run --pathbase=/wordtest
```
4. local host で起動されます。
```shell
# http://localhost:5074/wordtest にブラウザでアクセス
```
