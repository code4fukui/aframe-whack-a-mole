# aframe-whack-a-mole

VRモグラたたきゲームです。

## デモ
[こちらのリンクからゲームをお試しいただけます](https://acodedoer.github.io/aframe-whack-a-mole/)

## 特徴
- シンプルなVR（バーチャルリアリティ）モグラたたきゲーム
- 操作にカーソルを使用するため、コントローラーは不要
- ゲームの制限時間と難易度を設定可能

## 使い方

### インストールと実行
1. リポジトリのクローン
   ```sh
   git clone https://github.com/acodedoer/aframe-whack-a-mole.git
   ```
2. ゲームの設定
   `control`コンポーネントの`gameDuration`プロパティを使用して、ゲームの制限時間を設定できます（"short"は30秒、"long"は45秒です）。また、`control`コンポーネントの`popMultiple`プロパティを使用して、ゲームの難易度を調整できます（`true`にすると複数のモグラが同時に出現し、`false`にすると1匹ずつ出現します）。

## ライセンス
ライセンス情報は提供されていません。
