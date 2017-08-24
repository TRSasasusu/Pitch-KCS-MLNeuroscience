<h1 style="font-size: 250%;">神経科学と機械学習</h1>
twitter: @TRSasasusu
---
## 自己紹介
---
## 自己紹介
<img src="https://kcs1959.jp/wp-content/uploads/2017/03/Screenshot_2017-02-06-16-46-40.png" style="width: 400px;" align="left" />
<iframe width="400" height="225" src="https://www.youtube.com/embed/zxLMtd7V_m4?ecver=1" frameborder="0" allowfullscreen align="right"></iframe>
<br clear="both" />
- Django はいいぞ
- 神経工学 |
---
<span style="font-size: 40%;">
ある男がハイキングに出かける。道中、この男は不運にも沼のそばで、突然 雷に打たれて死んでしまう。その時、もうひとつ別の雷が、すぐそばの沼へと落ちた。なんという偶然か、この落雷は沼の汚泥と化学反応を引き起こし、死んだ男と全く同一、同質形状の生成物を生み出してしまう。<br />この落雷によって生まれた新しい存在のことを、スワンプマン（沼男）と言う。スワンプマンは原子レベルで、死ぬ直前の男と全く同一の構造を呈しており、見かけも全く同一である。もちろん脳の状態（落雷によって死んだ男の生前の脳の状態）も完全なるコピーであることから、記憶も知識も全く同一であるように見える。沼を後にしたスワンプマンは、死ぬ直前の男の姿でスタスタと街に帰っていく。そして死んだ男がかつて住んでいた部屋のドアを開け、死んだ男の家族に電話をし、死んだ男が読んでいた本の続きを読みふけりながら、眠りにつく。そして翌朝、死んだ男が通っていた職場へと出勤していく。(1)<br />(1) スワンプマン. "[https://ja.wikipedia.org/wiki/スワンプマン](https://ja.wikipedia.org/wiki/%E3%82%B9%E3%83%AF%E3%83%B3%E3%83%97%E3%83%9E%E3%83%B3)". (参照 2017-08-24)
</span>
+++
## 意識
- 哲学的ゾンビ
- 主観とは
- 統合情報理論 |
---
## さて，本題へ
---
<h1 style="font-size: 250%;">神経科学と機械学習</h1>
---
## 目次
- 神経科学の基本的なこと
- 神経科学から見た機械学習
---
## まずは神経科学
---
## 神経細胞
<img src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Complete_neuron_cell_diagram_en.svg" style="width: 50%;" />(2)
  
(2) 神経細胞. "[https://ja.wikipedia.org/wiki/神経細胞](https://ja.wikipedia.org/wiki/%E7%A5%9E%E7%B5%8C%E7%B4%B0%E8%83%9E)". (参照 2017-08-24)
---
## 活動電位
<img src="https://upload.wikimedia.org/wikipedia/commons/4/4a/Action_potential.svg" style="width: 30%;" />(3)
  
(3) Action potential. "[https://en.wikipedia.org/wiki/Action_potential](https://en.wikipedia.org/wiki/Action_potential)". (参照 2017-08-24)
---
## シナプス
<img src="https://upload.wikimedia.org/wikipedia/commons/4/4c/Synapse_diag1.svg" style="width: 30%;" />(4)
  
(4) シナプス. "[https://ja.wikipedia.org/wiki/シナプス](https://ja.wikipedia.org/wiki/%E3%82%B7%E3%83%8A%E3%83%97%E3%82%B9)". (参照 2017-08-24)
---
## 脳
<img src="https://upload.wikimedia.org/wikipedia/commons/b/b5/Brain_diagram_ja.svg" style="width: 50%;" />(5)
  
(5) 脳. "[https://ja.wikipedia.org/wiki/脳](https://ja.wikipedia.org/wiki/%E8%84%B3)". (参照 2017-08-24)
---
## 測定方法
- パッチクランプ法 |
- Optogenetics |
- fMRI |
- EEG |
---
## そもそも神経科学にはどんな分野がある？
---
## 神経科学の分野（私の知っているもの）
- 認知神経科学
- 神経工学
- 理論神経科学
- 神経学
- 分子神経科学
---
## 理論神経科学
---
## 理論神経科学
- 計算論的神経科学
- 数理脳科学
---
## それでは機械学習へ
### 神経科学から見た機械学習
(マサカリがやばそう)
---
## ニューラルネットワーク
---
## ニューラルネットワーク
<img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Multi-Layer_Neural_Network-Vector.svg" style="width: 50%;" />(6)
  
(6) ニューラルネットワーク. "[https://ja.wikipedia.org/wiki/ニューラルネットワーク](https://ja.wikipedia.org/wiki/%E3%83%8B%E3%83%A5%E3%83%BC%E3%83%A9%E3%83%AB%E3%83%8D%E3%83%83%E3%83%88%E3%83%AF%E3%83%BC%E3%82%AF)". (参照 2017-08-25)
---
## プルキンエ細胞
<img src="https://upload.wikimedia.org/wikipedia/commons/d/d4/Gray628.png" style="width: 25%;" />(7)
  
(7) プルキンエ細胞. "[https://ja.wikipedia.org/wiki/プルキンエ細胞](https://ja.wikipedia.org/wiki/%E3%83%97%E3%83%AB%E3%82%AD%E3%83%B3%E3%82%A8%E7%B4%B0%E8%83%9E)". (参照 2017-08-25)
---
## ニューラルネットワークの重み
- 正負の値がある → 興奮性にも抑制性にもできる |
- 学習により変化する → ヘブ則 |
- 誤差逆伝播 → ない？！？！ |
---
## 時間依存シナプス可塑性(STDP)
時間を考慮に入れたヘブ則．  タイミングのおかしいニューロンに対してシナプスの重みを減らすもの．
---
## 強化学習
(おそらくもう時間がないだろう)
---
## 強化学習
ある環境において行動した時に，報酬があったら良くて，罰があったら悪いので改善するという感じのアルゴリズム  
(はしょり過ぎてごめんなさい)
---
## 脳における強化学習
報酬はドーパミンが担っている．  
ある行動をしたときに期待以上だったら多くドーパミンが出る．逆ならば少なくなる．予想通りだったら通常通り．
