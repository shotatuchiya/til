# HTMLにPHPを埋め込む

＜?php

class Menu {

public $name;

}

$curry = Menu(’CURRY’);

?＞

＜p＞＜?php echo $curry - > name ?＞＜/p＞

PHPのコードを埋め込むことで、HTMLのコードとPHPのコードを切り分けることができ、見やすくなります。

# セミコロンを省略できる条件

＜p＞＜?php echo $curry - > name ?＞＜/p＞

PHPのコードは、文末にセミコロン「;」を使って区切る必要があると学習してきました。

しかしPHPのコードを１行で書き表す場合は、区切る必要がないのでセミコロンを省略することができます。
