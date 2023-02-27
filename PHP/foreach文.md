# foreach

$towns = array(’東京’, ‘大阪’, ’京都’);

foreach($towns as $town){

echo $town.’ ’;

}
結果：東京　大阪　京都

foreach文とは、配列または連想配列に対して、先頭のデータから順に繰り返し処理を行うための命令です。

以下のように配列のデータを１つずつ取り出して処理を行うことが出来ます。

「as」の後ろの変数に、ループの度にデータが先頭から順に代入されていきます。asの後ろの変数名は何を指定しても大丈夫です。

# foreachの書き方（１）

foreach(配列 as 値変数){

繰り返したい処理;

}

foreach(配列 as キー変数 = > 値変数){

繰り返したい処理;

}

foreach文では、配列内のデータが順次「キー変数」、「値変数」に代入され、それに対して処理が繰り返し適用されます。

「キー変数」には、配列のときはインデックス番号が、連想配列のときはキーが代入されます。

ただし、「キー変数」の部分は省略可能です。

# foreachの書き方（２）

$colors = array(’apple’ = > ‘red’, ‘banana’ = > ‘yellow’,  ‘grape’ = > ‘purple’);

foreach($colors as $key = > $value){

echo $key. ’ : ‘ . $value.’ ‘;

}

結果：apple:red  banana:yellow  grape:purple

 

foreach文は理解しにくいので少し例を見てみましょう。 図の配列は、果物の名前を「キー」として、その色を「値」として保持している連想配列です。

1周目のループでは$keyに'Apple'、$valueに'Red'が、２周目のループでは$keyに'Banana'、$valueに'Yellow'が入っています。
