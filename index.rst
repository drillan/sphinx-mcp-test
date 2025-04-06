.. Sphinx-MCP-Sample ドキュメントのマスターファイル
   sphinx-quickstart によって 2025年4月6日（日）14:35:01 に作成されました。
   このファイルは完全に自由にカスタマイズできますが、少なくとも
   ルート `toctree` ディレクティブを含める必要があります。

Sphinx-MCP-Sample ドキュメント
===============================

プロジェクト概要
--------------

Sphinx-MCP-Sampleは、Model Context Protocol (MCP)とSphinxを組み合わせた
先進的なドキュメント作成システムです。以下の特徴があります：

* MCPによる高度な文脈理解
* Sphinxの豊富な機能
* カスタマイズ可能なテーマ

インストール手順
-------------

1. 必要なパッケージのインストール::

    pip install sphinx mcp-server

2. プロジェクトのクローン::

    git clone https://github.com/yourusername/sphinx-mcp-test

3. ビルドの実行::

    make html

.. toctree::
   :maxdepth: 2
   :caption: 目次:

   sphinx_users

