# オイラープロジェクトをRubyでプログラミング演習

## 問題文について

以下のページから翻訳された問題文を引用する。有志に感謝。  
http://odz.sakura.ne.jp/projecteuler/  

## コーディングについて

原則としてRubocopやCookpadのRubyコーディング基準を遵守する。  
参考URL:  
https://github.com/fortissimo1997/ruby-style-guide/blob/japanese/README.ja.md  
https://github.com/cookpad/styleguide/blob/master/ruby.ja.md  
  
全文が長いため初心者にとって特徴的な部分のみ抜粋する  

* 1行の文字数は80文字以内
* メソッドの行数は10行以下
* メソッドの引数は4以下
* 原則としてFor文は利用しない

より具体的にはこのレポジトリに含まれるrubocop設定ファイルによるrubocopをクリアすること。  

---  
  
## No. 001  
  
> Problem 1 「3と5の倍数」 †  
> 10未満の自然数のうち, 3 もしくは 5 の倍数になっているものは 3, 5, 6, 9 の4つがあり, これらの合計は 23 になる.  
>   
> 同じようにして, 1000 未満の 3 か 5 の倍数になっている数字の合計を求めよ.  
  
CodeSize: 126 byte  
  
[Code](https://github.com/owlworks/daily_quest/blob/master/codes/001.rb "Code")  
  
