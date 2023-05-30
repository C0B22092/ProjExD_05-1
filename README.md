# ハコツミツミ(仮称)

## 実行環境の必要条件

- python >= 3.10
- pygame >= 2.1

## ゲームの概要

ブロックや穴を避け、敵を爆破し、箱を積み上げ進み続けるアクションゲーム

## ゲームの実装

### 共通基本機能

- プレイヤーに関するクラス
- ブロックに関するクラス

### 担当追加機能

- プレイヤーの加速度運動
- プレイヤーとブロックの衝突
- レベル(マップ)の生成と保持
- スクロール

### TODO

- [ ] ゲームオーバー処理

### メモ

- 各クラスのメンバ変数は隠蔽してあるため, 変更が必要な場合は用意されているGetterやaddから始まる関数を用いること
- 読み取り利用ならば@propertyデコレータを用いてGetterを作成してあるため, メンバ変数名でアクセスできる
  - この際, 戻り値に代入してもインスタンス変数は更新されないことに注意すること
