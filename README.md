# このボットについて 
このボットはポケモンの素早さを素早く参照することを目的として作成しました。
具体的には「ポケモン名、速さ（最速、準速、無振り、下降、最遅の5段階のいずれか）」と入力することでそのポケモンの素早さ実数値およびランク補正後の素早さを返します。
ポケモン名と速さの間の点は全角でも半角でも反応します。また、ポケモン名はひらがなでもカタカナでも、またひらがなとカタカナが混じっていても反応します。

# 使い方　
1.!pをボットを使いたいチャンネルで打ち込み、ボットを起動状態にする<br>
2.「ポケモン名、速さ（最速、準速、無振り、下降、最遅の5段階のいずれか」の文字列を打ち込むとポケモンの素早さ実数値が返答される。

なお、ポケモン名および速さが間違っている場合は警告文を返します。

# 現在確認している不具合
1.複数のフォルム（ランドロスの化身、霊獣）、リージョンフォームがあるポケモンは通常フォルムの素早さしか返ってこない
これは素早さを取得するときにPokeapiに図鑑番号で問い合わせているため
解決には別の手法か例外処理をする必要がある。（解決するかどうか未定）

# 使用させていただいているサイト
・Pokeapi様[https://pokeapi.co/]
素早さ種族値を取得するために使用させていただいております。

