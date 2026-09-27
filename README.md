# NEON RECLAIMER — WebGL

[ブラウザで遊ぶ](https://blueberry1001.github.io/neon-reclaimer-play/)

敵を倒してコインを集め、装備を強化する3Dアクション。3ステージとボス、銃・支援ドローンの解放、周回強化があります。

PCのキーボードとマウスで遊べます。WASDで移動、左クリックで剣（近くの敵へ自動で向きます）、Shiftでダッシュ、右ドラッグで視点回転、ホイールで距離、Eで強化、Escで一時停止。銃・支援ドローン・パルスは自動発動。パルスは5撃破で解放されます。
進行はブラウザに保存されます。サイトデータを削除すると保存も消えます。

このリポジトリは配布用WebGLのみです。Unity・Blenderの制作ソースは別の非公開リポジトリで管理しています。

## 素材

- コンクリート: [ambientCG Concrete034](https://ambientcg.com/view?id=Concrete034) — CC0
- 金属: [ambientCG Metal030](https://ambientcg.com/view?id=Metal030) — CC0
- 反射環境: [Poly Haven Kloofendal 48d Partly Cloudy (Pure Sky)](https://polyhaven.com/a/kloofendal_48d_partly_cloudy_puresky) — CC0; Greg Zaal / Jarod Guest
- フォント: Zen Kaku Gothic New — SIL Open Font License 1.1（Licenses参照）
- Noto Sans JP — SIL Open Font License 1.1（同梱フォント、Licenses参照）

ゲーム独自のモデル・画像・コードに、外部素材のCC0ライセンスが適用されるわけではありません。

同梱TextMesh Pro標準フォント Liberation Sans: SIL Open Font License 1.1（Licenses参照）。


## 空中駅・パルス更新
Blender製の駅舎・高架・サービス基壇を追加し、ステージの構図と配色を再構成しました。自動パルスで周囲を攻撃し、弾を消せます。9秒の待ち時間は撃破ごとに0.6秒短縮。


## 操作・戦闘更新
移動攻撃の脚アニメーション、自由カメラ、自動攻撃、強化可能通知を改善。序盤から距離を取る射撃敵が登場します。坂で上がれるデッキと弾を遮る設備、撃破・被弾の演出を追加しました。

