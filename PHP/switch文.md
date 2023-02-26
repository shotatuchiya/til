# switch文

switch($coin){

case 0:　←：（コロン）

echo ‘表’;　←；（セミコロン）　　

break;

case 1:

echo ‘裏’;

break;

default:

echo ‘エラー’;

break;

}

if, elseifによる分岐が多く複雑な場合、switch文で書き換えるとシンプルで読みやすいコードにできます。switch(式)の(式)がcaseの値と一致したとき、そのブロックが実行されます。caseのどれにも一致しなかった時、defaultのブロックが実行されます。

# switch文 - break

caseブロックの最後にはbreak命令を指定します。break命令は現在のブロックから脱出するための命令です。break命令がないと、後ろに続くcaseブロックが続けて実行されてしまいます。
