# Powershell-study

* 変数 <br>
 $変数 = 値<br>
 $変数 = "文字列"<br>

<br>

* 配列 <br>
 @(a, b, c, d)<br>
 @{a; b; c; d}<br>

<br>

* 演算子<br>
  | 演算子 | 意味 | 
  | ------ | ------| 
  | -eq | = |
  | -ne | not= |
  | -gt | > |
  | -ge | >= |
  | -lt | < |
  | -le | <= |
  
<br>

* パラメータ<br>
  Param(<br>
  [型]$変数1,<br>
  [型]$変数2 = "へんすう"<br>
　)<br>
* スイッチパラメータ<br>
<https://learn.microsoft.com/ja-jp/powershell/module/microsoft.powershell.core/about/about_functions_advanced_parameters?view=powershell-7.4><br>

<br>

* Function<br>
　Function 関数名(引数) { 処理 return(戻り値) }<br>
 <br>
呼び出しは以下の4通り<br>
・引数なし/戻り値なし　→　関数名<br>
・引数なし/戻り値あり　→　$変数名 = 関数名<br>
・引数あり/戻り値なし　→　関数名 引数1 引数2　※スペース区切りで表記<br>
・引数あり/戻り値あり　→　$変数名 = 関数名 引数1 引数2<br>

<br>

* ループ処理<br>
　for (初期化式; 条件式; 増減式) {<br>
	　繰り返す処理<br>
　}<br>

 

  
