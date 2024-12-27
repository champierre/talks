# 機械学習 - 猪木顔ってどんな顔?

<kbd>←</kbd> で戻る。<kbd>→</kbd> で進む。
---

# 自己紹介

石原淳也 [@jishiha](https://twitter.com/jishiha)

株式会社まちクエスト 代表取締役社長 <small v-click>兼ソフトウェアエンジニア</small>

合同会社つくる社 代表社員 <small v-after>兼ソフトウェアエンジニア</small>

青山学院大学 総合文化政策学部プロジェクト准教授

---

# まちクエスト

「スマホを持って謎解きにでかけよう！」がコンセプトのスマートフォン向けフィールドゲーム

https://machique.st

---

# 青学つくまなラボ

https://sites.google.com/view/tukumanalab/

青山学院のすべてのひとたちに「創ることで学ぶ」場を提供

<div class="flex justify-center">
　<img src="https://lh5.googleusercontent.com/ZLF9heFLHdA9AMyPmiv9siotgy87f1nA-9PARkWksrYfa68pMz9Rd8wYkK2Aoo3mvtPOie5Qqti-tLsNOCJ1SAE=w16383" style="width: 80%">
</div>

---

# 3Dペン

<div class="flex justify-center">
　<img src="/IMG_3949.jpg" style="width: 50%">
　<img src="/IMG_3950.jpg" style="width: 50%">
</div>

---

# 3Dプリンタ

https://youtube.com/shorts/YrbXPIzkOOw?si=G7biHPYxkKttivcn

<div class="flex justify-center">
　<img src="/IMG_3323.jpg" style="width: 50%;height:50%">
　<img src="/IMG_3586.jpg" style="width: 50%;height:50%">
</div>

---

# Scratch & 機械学習

<div class="flex justify-center">
　<img src="https://m.media-amazon.com/images/I/71cbs2r7Y6L._SY385_.jpg" style="width: 30%">
　<img src="https://m.media-amazon.com/images/I/51ZcTxl-u0L._SX342_SY445_.jpg" style="width: 30%">
</div>

---

# 機械学習とAIは同じものですか？

<div v-click>AI: 人工的な知能を作ろうとする研究分野</div>
<div v-after>機械学習: データーを使って<strong>学習</strong>し、<strong>機械</strong>（コンピューター）を使って特定の問題を解決する</div>

<div class="flex justify-center">
　<img src="/ai_ml.png" style="width: 30%">
</div>

出典: Scratchではじめる機械学習 第2版 p.102

---

# Scratch

<div class="flex justify-center">
　<img src="/genetic_algorithm.png" style="width: 40%">
</div>

遺伝的アルゴリズムを使って障害物をよけるネコ: https://scratch.mit.edu/projects/225025926/

ノーコードツールは、<span v-mark.strike-through.red>プログラミングの知識やスキルがなくても、</span>直感的な操作でWebアプリケーションなどのソフトウェア（業務アプリや業務システム）を開発できるツール

出典: https://kintone.cybozu.co.jp/what_is_kintone/no_code/

---

# ライブコーディング

Scratchを改造して独自の拡張機能を利用できる[Stretch3](https://stretch3.github.io/)を使います。

---

# Facemesh2Scratch

<div class="flex justify-center">
　<img src="/facemesh2scratch.png" style="width: 80%">
</div>

---

# 猪木顔とは？猪木とは？

猪木顔とは？猪木とは？　<span v-click>あご</span>

あごが伸びたら猪木に変身したい。

---

# Facemeshとは？

顔の部位468ヶ所の座標を推定できる。

あご: 153

鼻下: 165

右目尻: 134

左目尻: 363

---

# あごの長さを求める

あごの長さとは？

<span v-click>鼻下のy座標 - あごのy座標</span>

---

# あごの長さがいつもより長くなったらで良いか？

<span v-mark.strike-through.red>鼻下のy座標 - あごのy座標 > 40</span>

顔をカメラに近づけたらどうなるか？

<span v-click>長さが変わらない顔の他の部分と比較するのが良い。</span>

---

# 長さが変わらない顔の他の部分

長さが変わらない顔の他の部分とは？

<span v-click>目の間隔</span>

<span v-click>目の間隔 = 右目尻のx座標 - 左目尻のx座標</span>

---

# あごの長さ/目の間隔

<span v-click>あごの長さ/目の間隔 > 2 (僕の場合)</span>

<span v-click>になったら猪木に変身する。</span>
