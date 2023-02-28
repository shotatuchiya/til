# 送信ボタン

＜form action=”sent.php” method=”post”＞

Emailを入力してください

＜input type=”submit” value=”送信”＞

＜/form＞

送信ボタンをつくるには<input type="submit">を用います。

value属性に指定された値がボタン上に表示されます。

# フォームのデータを受け取る

＜?php echo $_POST['name']; ?＞　　←'name'はキーを表す

＜?php echo $_POST['body']; ?＞

フォームで送信した値を受け取るには「$_POST」を使用します。

「$_POST」は連想配列になっています。[ ]の中に、<input>と<textarea>のname属性に指定した値を入れることで、それぞれの送信した値を受け取ることが出来ます。
