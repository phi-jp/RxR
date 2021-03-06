# Web Reverse Reverse

<img src="https://raw.github.com/webrxr/RxR/master/img/icon/Icon@2x.png" width="114" height="114">

phi氏が制作したTMLib.jsを使用してReverse ReverseというiPhoneのゲームをウェブ上で動かしてみました。

- [tmlib.js](https://github.com/phi1618/tmlib.js)

iPhone版とのReverse Reverseの差は

- エフェクトや演出の簡易化
- ゲームバランスの簡易化
- 一部のゲームモードのみ搭載

となっています。  
ゲームはこちらからどうぞ - [Reverse Reverse](http://webrxr.github.com/RxR/)  
紹介記事はこちらです - [JavaScript ライブラリの tmlib.js を使って iPhone のゲームを Web に移植してみた](http://bit.ly/KkRVeU)


## ルール

オセロを元にしたゲームです。  
白石と黒石を交互に置くのではなく既に盤面には白石と黒石が置かれています。  
白石をタッチすると黒石に、逆に黒石をタッチすると白石に変化します(色の変化と言うよりは違う色の石を置き直す、という方がオセロっぽいかもです)。  
オセロと同じように同じ色の石と石の間にある違う色の石を挟んで色を変化させていきます。

例)

□■■■■ ← 一番右の黒石をタッチする  
□■■■□ ← タッチした黒石の色が変わって…  
□□□□□ ← 間にある白石で挟まれた黒石も変化する  

タッチする順番や色の制限はありません。  
これを繰り返して盤面の石を全て黒にしたら1ステージクリアです。  
ちなみにこれは簡易ルールでiPhone版は白石の数を指定した数に合わせるなど少し要素が増えています。


## 最後に

今回Reverse ReverseをWebで再現するにあたって開発元である[OAP](http://www.oap.cc/)様には最大限の協力を頂きました。  
Web版への許可や素材の使用など許可を頂きました。  
ありがとうございます。


本家iPhone版はリリース元会社が無くなってしまったため現在ダウンロードできません...。  
実質これが本家となってしまうのかも。

- [Reverse Reverse](http://itunes.apple.com/jp/app/reverse-reverse/id412804019?mt=8)
- [Reverse Reverse Lite](http://itunes.apple.com/jp/app/reverse-reverse-lite/id412804420?mt=8)

## ライブラリ/素材製作者様やブログのリンクなど
tmlib.js開発者のphi氏 ブログ

- [TM Life](http://bit.ly/MsWNlN)

ゲーム中の効果音は全てザ・マッチメイカァズ2nd様の物を使用させて頂きました。  
素晴らしい素材ありがとうございます。

- [ザ・マッチメイカァズ2nd 【フリー効果音素材】](http://osabisi.sakura.ne.jp/m2/)様

私(Halt)のブログ

- [なんかもう実験場](http://bit.ly/MsWGXg)
