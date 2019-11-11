# このチュートリアルについて

このチュートリアルは、coq-jupyter の形式で記述されています。Coqとcoq-jupyter をインストールしていれば、ドキュメントの内部でCoqのコマンドが実行できます。

全体の構成については[目次](0-Contents.ipynb)をご覧ください。（ファイル名は、0-Contents.ipynbです。）
git clone https://github.com/maruyama097/coq-tutorial でダウンロードできます。

Coqとcoq-jupyterのインストールなしでも、jupyter のnotebookとしてだけなら、GitHubへのアクセスだけでも、画像を含めてドキュメントの多くの部分を読むことは可能です。
- ただ、文字の一部が欠けていたり、HTMLのタグがそのまま表示されることがあります。
- もちろん、Coqのコマンドは実行できません。

Coqとcoq-jupyterのインストールをお勧めします。

# Coqとcoq-jupyterのインストールについて

Mac とWindowsでは、インストールのやり方が異なりますので、ご注意ください。

## Macの場合

Anacondaを既にインストールしている場合と、そうでない場合とで、別々のインストールの仕方を紹介します。

### Anacondaがインストール済の場合

次のコマンドで、Coqとcoq-jupyterのインストールができます。
```
     conda config --add channels conda-forge 
     conda create -n coq coq-jupyter
     conda activate coq
```
### Anacondaを使わずにインストールしたい場合

次の資料を参考にしてください。

#### 「macOSにbrewでcoq_jupyterをインストールする」 　http://bit.ly/33vHeX3

## Windowsの場合

Windowsの場合には、WSLを使って Coqとcoq-jupyter をインストールします。

次の資料を参考にしてください。

#### 「WSLにcoq-jupyterをインストールする」　http://bit.ly/33nw8TB

平原さん、情報提供ありがとうございました！