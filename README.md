GitCommitHookCp

=============

ローカル : git

共有     : svn

という環境でsvn側にはプロジェクトファイルとか無駄なファイルは追加したくないかつ、svnのignoreファイルは書くのがめんどくさいのでどうにかしてみた。

git側でcommitした時に、gitで管理しているファイルだけをsvn側にコピーしてくれる。


##使い方

.git/hooks/の下にpost-commitを配置して、svnで管理しているフォルダへのパスを書き換えるだけ
