#  HIT-BLOW-ver2

これは「Hit & Blow」（3桁の数字当てゲーム）を攻略するためのWebアプリです。  
エントロピーを使って、次に最適な推測を自動で提案してくれます。  
シンプルなUIで誰でもすぐ使えます  
🔗 [デモを見る](https://sho7772987.github.io/HIT-BLOW-2/)

---

##  主な機能

-  3桁の異なる数字を自動生成し候補を管理
-  Hit/Blowの履歴に基づいて候補をフィルタリング
-  エントロピー（情報理論）を用いて最も情報を得られる推測を提示
-  入力ミスに対する警告やリセット機能付き
-  ブラウザだけで動作、インストール不要

---

##  使い方

1. `index.html` をブラウザで開く  
2. あなたが予想した3桁の数字（例: `123`）を入力  
3. 相手から得た Hit / Blow の数を入力して「入力」ボタンを押す  
4. 候補が自動で絞られ、次のおすすめが表示されます

---

##  技術的ポイント

- JavaScript/HTML/CSS で完結（外部ライブラリなし）  
- すべての候補に対して結果の分布を取り、エントロピーを計算  
- 最も「情報を引き出せそうな」推測をスコア順に表示

---

---

#  HIT & BLOW (English ver)

This is a web app designed to help you win the **"Hit & Blow"** (3-digit number guessing game).  
It uses **entropy (information theory)** to recommend the most informative next guess.  
Simple UI, no installation needed — just open and play  
🔗 [Try the Demo](https://sho7772987.github.io/HIT-BLOW-2/)

---

##   Features

- Automatically generates all valid 3-digit numbers with unique digits  
- Filters candidates based on Hit/Blow history  
- Calculates entropy for each guess to determine the most informative one  
- Input validation and reset functionality included  
- Fully browser-based — no installation or dependencies

---

##   How to Use

1. Open `index.html` in your browser  
2. Enter your guessed 3-digit number (e.g., `123`)  
3. Input the number of Hits and Blows returned by your opponent  
4. The app will narrow down candidates and recommend the best next guess

---

##   Technical Notes

- Pure HTML/CSS/JavaScript (no external libraries)  
- For each candidate, the app simulates possible outcomes and calculates entropy  
- Ranks guesses based on expected information gain

---
