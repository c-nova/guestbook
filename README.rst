==================
ゲストブックアプリ
==================

目的
==================

Webブラウザでコメントを投稿するWebアプリケーションの練習。

ツールのバージョン
==================

:Python:	2.7.10
:pip:		7.1.2
:virtualenv:	13.1.2

インストールと起動方法
======================

リポジトリからコードを取得し、その下にvirtualenv環境を用意します::

  $ git clone https://github.com/c-nova/guestbook
  $ cd guestbook
  $ virtualenv .venv
  $ source .venv\Scripts\activate
  (.venv)$ pip install .
  (.venv)$ guestbook
  * Running on http://127.0.0.1:8000/
  
開発手順
========

開発用インストール
------------------

1，チェックアウトする
2，以下の手順でインストールする::

  (.venv)$ pip install -e .
