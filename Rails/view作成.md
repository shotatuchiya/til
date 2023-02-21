# ビューの作成・設定

app/views/questions/new.html.erb  # new.html.erb　ファイル作成

<%= form_with model: @question, local: true do |form| %>

<%= form.text_field :title, placeholder: "タイトル" %><br>  #text_field ヘルパーメソッド :titleはテーブル

<%= form.text_area :content, placeholder: "質問内容" %><br>  #text_area ヘルパーメソッド

<%= form.text_field :name, placeholder: "投稿者名" %><br>  #text_field ヘルパーメソッド

<%= form.submit 'POST'%>

<% end %>

# 備考

・拡張子に.erbでファイル作成

・<%= %> フォームなどの表示させたい場合に＝をつける。

・<% %> eachなどの繰り返し文に使用。
