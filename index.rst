.. Sphinx-MCP-Sample ドキュメントのマスターファイル
   sphinx-quickstart によって 2025年4月6日（日）14:35:01 に作成されました。
   このファイルは完全に自由にカスタマイズできますが、少なくとも
   ルート `toctree` ディレクティブを含める必要があります。

Sphinx-MCP-Sample ドキュメント
===============================

プロジェクトの概要
-----------------

このプロジェクトは、Model Context Protocol (MCP) をSphinxで活用するためのサンプルプロジェクトです。
MCPの機能を効果的に活用し、高品質なドキュメントを作成する方法を紹介します。

主な特徴
--------

* Sphinxによる美しいドキュメント生成
* Model Context Protocolの統合
* 日本語ドキュメントのサポート
* カスタマイズ可能なテーマとスタイル

クイックスタート
--------------

1. プロジェクトのセットアップ::

    $ git clone https://github.com/yourusername/sphinx-mcp-test
    $ cd sphinx-mcp-test
    $ pip install -r requirements.txt

2. ドキュメントのビルド::

    $ make html

3. ブラウザで ``_build/html/index.html`` を開いてドキュメントを確認

詳細なドキュメント
----------------

以下のセクションで、より詳細な情報を確認できます：

.. toctree::
   :maxdepth: 2
   :caption: 目次:

   sphinx_users

