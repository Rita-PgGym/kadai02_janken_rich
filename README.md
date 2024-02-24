# ①課題番号-プロダクト名
課題番号02　じゃんけんアプリリッチバージョン

## ②課題内容（どんな作品か）
じゃんけんをして勝つと得点が入ります

## ③DEMO
https://rita-pggym.github.io/kadai02_janken_rich/

## ④工夫した点・こだわった点
●画面デザイン
 就学前の子どもが一人でもあそべるようなデザインにしました。
 
●画面レイアウト
 cssに苦手意識があったので全体レイアウトを手書きして、
 HTMLでブロック要素ごとにグループを考えてから、cssファイルの編集を始めました。
 意識的に横並びと表を利用するようにしました。
  ・Flexboxを使った横並び（pcの打ち手の画像、勝ち負けの画像、playerの打ち手の画像）
  ・表（スコアボード）
  ・角丸ボタン

●音声再生
 Startボタン、グーボタン、チョキボタン、パーボタンを押すと音声が再生されるようにしました。

●得点表示
 変数を定義して、勝ったら1点の得点が入るようにしました。
 得点が正しく表示されているかどうかを確かめるため、console.logを使って確認するようにしました。

## ④難しかった点・次回トライしたいこと(又は機能)
●難しかった点
 ・cssファイルでの設定（margin、padding、表示位置上下左右指定など）

●トライしたいこと
 ・10点先取の3セット勝負という風なゲームにしたかったです。トライしましたが仕上げきれませんでした。
 
## ⑤質問・疑問・感想、シェアしたいこと等なんでも
- [tips]
  全体レイアウト図を作る→処理を日本語で書く→コーディングするという一連の流れをを意識して取り組みました。
  機能を追加するときは一つずつ、小さな単位で取り込んでいくことを心がけました。
- [参考記事]
  ・音を鳴らす　https://jp-seemore.com/web/3576/#toc2
  ・角丸ボタン　https://ics.media/entry/230629/
  
