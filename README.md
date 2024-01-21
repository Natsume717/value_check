# value_check
predicateのvalue_checkに関するデータパックサンプルになります。

詳しくはブログ記事『[【マイクラ】value_checkで値を比較する【predicate】](https://natsumake.com/predicate_value_check/)』を参考にしてください。

<h3>使い方</h3>

導入後、sample_scoreというスコアボードが生成され、サイドバーには初期値として10という値が表示されているはずです。<br>
表示されない場合は```/reload```を実行してください。

以下の各種コマンドで、value_checkを指示したコマンドを実行できます。<br>
内容については上述したブログ記事で解説しています。

```/execute if predicate sample:scoreboard_value run give @a diamond 1```

```/execute if predicate sample:scoreboard_range run give @a diamond 1```

```/execute if predicate sample:scoreboard_ranges run give @a diamond 1```
