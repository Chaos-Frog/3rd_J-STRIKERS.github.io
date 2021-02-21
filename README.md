# 3rd J-STRIKERS
Webで動く3Dグラフィック弾幕シューティング  
Three.jsを使用  
公開ページ => https://freegame-mugen.jp/shooting/game_8488.html
デモ動画 => https://youtu.be/rLIN28-TdCY

# 目次
* [概要](#概要)
* [システム](#システム)
* [製作](#製作)

# 概要
タイトル：3rd J-STRIKERS  
ジャンル：弾幕シューティング  
怒首領蜂シリーズ等のCAVEシューティングを参考に製作  
Gダライアス、レイディアントシルバーガン、斑鳩のような3DグラフィックSTG

# システム
## [ゲームルール]
基本的なシステムはアーケード弾幕シューテングと同じ  
道中の敵を倒しつつ進み、最後のボスを倒すとゲームクリア  
自機中心の判定に被弾すると、残機が一つ減る  
残機が全てなくなり、コンテニューしなければゲームオーバー  
コンテニューすれば、スコアがリセットされて再開できる

## [操作]
* [移動]  
上下左右と斜めに移動可能  
* [拡散ショット]  
広範囲のショット 弾数は集中ショットよりも少なめ  
* [集中ショット]  
集中的なショット 撃っている最中は移動速度が遅くなる  
* [ボンバー]  
撃った瞬間、画面上の敵弾を消してスコアに変換  
効果時間中は無敵となりショットが撃てなくなる

## [スコア]
* 敵に弾を当てる   
自機の撃つ弾は、赤→橙→黄と３段階に色が変化していき、  
色によって与えるダメージと得られるスコアが異なる  
より早い段階で当てれば高いスコアを狙うことができる  
また、敵を倒す、硬い敵に弾を当て続けるとコンボを増加させることができる
* スコアスターを取る  
スコアスターを取ることで、「スターの得点　× コンボ」のスコアを得ることができる  
集中ショット中は周りのスターを引き寄せることができる
* ボスを倒す  
ボスを倒した際に、「ボスの得点 × コンボ」のスコアを得ることができる


# 製作
### 混沌の蛙 F-Rog [[Twitter]](https://twitter.com/CF_Frog)  
### クレジット:
* [背景画像]
    * Neuro!Image 様
* [フォント]
    * けしのみ工房 様
* [効果音]
    * On-Jin 様
    * 効果音ラボ 様
    * フリー効果音・無料効果音（小森平） 様
    * フリー効果音素材 くらげ工匠 様
* [ジングル]
    * フリーBGM・音楽素材MusMus 様
* [BGM]
    * DOVA-SYNDROME 様
        * RAIN & Co II (ISAo)
        * LAST GUARDIAN (MAKOOTO)
