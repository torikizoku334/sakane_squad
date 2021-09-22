# 議事録の作り方
## 初めて作る場合
### gitのクローンを行う
#### gitのクローンを行う
https://github.com/icc-sakane/sakane_squad.git
からクローンを行う。<br>
以降2回目以降を行う
## 2回目以降
### pullを行う
git pull origin gh-pages<br>
### 修正を行う
前回の議事録をコピーする（ファイル名は年-月-日-gijiroku.mdとする）<br>
ファイルの内容を修正する<br>
index.mdを修正する<br>
### git hubにあげる
git add .<br>
git commit -m "コメント"<br>
git push orijin gh-pages<br>
## 確認を行う
https://mr-kyary.github.io/sakane_squad/
にアクセスして動作確認
