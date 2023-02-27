# continue

for($i = 1; $i < = 10; $i ++){

if($i % 3 == 0){

continue;

}

echo $i;

}

結果：123457810 ※3の倍数以外

ループそのものを完全に抜けてしまうbreak文に対して、continue文は現在の周だけをスキップし、ループそのものは継続して実行します。

continue文もfor, while, foreachなどの繰り返し文の中で利用できます。
