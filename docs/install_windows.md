---
layout: docs
title: Windowsへのインストール方法
---
バイナリパッケージを利用する
----------------------------
開発者でない場合、予めコンパイルされていてインストーラの付属したバイナリパッケージを利用するのが簡単です。
`ftp://ftp.vim.org`でも配布されていますが、大きなバージョンアップのタイミングでしかリリースされません。
Windows向けには[KaoriYa](http://www.kaoriya.net/)からバイナリパッケージが配布されています。

> [![KaoriYa](http://www.kaoriya.net/assets/images/header-logo.png)](http://www.kaoriya.net/software/vim)


1.  ダウンロード

    Windows 32bit版、Windows 64bit版のどちらかをダウンロードします。

2.  解凍

    圧縮ファイル解凍ツールを使って展開します。
    [Common Archivers Library - 統合アーカイバ・プロジェクト](http://www.madobe.net/archiver/main.html)などからzipを解凍出来るツールをインストールします。

3.  配置

    フォルダ構成をそのまま希望の場所に移動します。
    `C:\Program Files`等にインストールしても良いですが、後々問題とならない様`C:\vim`等スペースを含まないディレクトリに格納した方が良いでしょう。

4.  パスを通す

    マイコンピューターのプロパティから詳細設定を開き、環境変数の設定画面を開きます。
    ユーザーの環境変数欄でPATH環境変数に保存したフォルダを追加します。
    また存在しない場合は追加します。

