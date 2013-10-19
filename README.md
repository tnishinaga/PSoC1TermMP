PSoC1TermMP
===========

●概要
PSoC1duino用プログラム書き込み用スクリプトです。マルチプラットフォームに対応しています。
本家と違い、ボーレートは115200bps、マイコンは27443固定です。またターミナル機能もありません。

●コードとライブラリについて
Python3で書かれています。
シリアル通信ライブラリはpyserialを使っています。
$ pip install pyserial
でpyserialをインストールしてから使ってください。

●使い方
使い方はexample.txtを参照してください。

●注意
このブートローダのプロトコルはPSoC1のみ利用可能です。
それ以外では利用しないでください。

このプログラムを利用したことにより生じた問題に対し作者は一切の責任を負いません。
またサポートもしませんし、今後意欲的なアップデートも行いません。
自己責任でご利用ください。
