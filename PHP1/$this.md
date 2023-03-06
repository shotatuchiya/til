# $this

class Menu{

public $name;

public function hello(){

echo ‘私の名前は’.$this - > name.’です’;

}

}

$curry = new Menu();

$curry - > name = ‘CURRY’;

$curry - > hello();

結果：私の名前はCURRYです

メソッド内でインスタンスのプロパティやメソッドにアクセスしたい時には「$this」という特殊な変数を用います。

$thisはクラス内のメソッドの定義の中でのみ使用できます。

$thisはメソッドが呼ばれた時に、そのメソッドを呼び出しているインスタンスに置き換えられます。
