# プロダクトのタイトル
地名読めるかな？

## プロダクトの紹介

- 8枚のカードの裏に書かれた地名を交互に開き、Google音声検索で地名を答えて当てていくゲーム
　（「ここをクリックしてGoogle音声検索を開始！」をクリックして、マイクを許可して音声を入力）

## 工夫した点，こだわった点

- 「Web Speech API」の音声認識機能を活用
- 音声検索だけではプロダクトとして面白くないので、対戦型クイズゲーム形式でユニークさを付与

## 苦戦した点，共有したいハマりポイントなど
- JSだけで、かつ、ローカル環境で使えるAPIがなかなか見つからず、プロダクトを作り始めるまでに8割ぐらいの時間を要した
- 「Web Speech API」の音声認識機能も、コードサンプルを参照して作っただけで、コードの意味を十分理解できていない
- ほとんどのAPIで情報の受け取り方が全然分からないかった。APIの叩き方もJSON等での情報の受け取り方も分からず、作業を進めるのに難儀した。今後PHPなど使える言語を増やしながら、使いたいAPIを正しく利用できるようになっていきたい。

## URL
https://nkunitake.github.io/geographicalname/
※API keyは不要のAPIを利用しています。
