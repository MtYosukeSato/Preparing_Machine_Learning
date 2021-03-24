# prepearing machine lerning
OpenCV画像認識の正解画像における[filename x y width height]のテキストデータを書き出すものです。

# Description
画像表示、データの登録、テキストデータとして書き出し、といった動作を、HTMLファイル1枚で完結することを目標としています。
使用しているのは、HTML5・Canvas・CSS・Javascriptになります。
自分で使うため、かつ、ポートフォリオのようなものですのでライセンスフリーです。

#Demo
![スクリーンショット](https://raw.github.com/wiki/MtYosukeSato/Preparing_Machine_Learning/img/README.png)

#Usage
1.preparing_machine_learning.htmlを開く。
2.「ファイルの選択」をクリックし、画像が保存されているフォルダを選んで「アップロード」する。
（サーバーとは通信しないので画像走査をするだけです。）
3.右側に表示された画像をクリックして、左側に画像を表示させる。
（「Ctrl + 十字キーの上」と「Ctrl + 十字キーの下」でも選択が可能です。）
4.認識させたいオブジェクトをマウスでドラッグすると、リストにデータが反映されます。
5.「テキストのダウンロード」をクリックすると、ダウンロードフォルダにデータが保存されます。

#Requirement
動作確認環境はWindows10のMicrosoft Edgeです。

#Future updates planned
簡易的なものではありますが、追加したいなと思っている機能がまだあります。
更新時期は不定です。
・一つの画像内で複数の認識オブジェクトがある場合の登録（現在は一つだけです。）
・すでに書き出しているテキストデータがあれば読み込む（技術的に可能であれば追加。）
・画像の縮小表示（大きな画像では操作しずらいものとなっています。）
・リロードしてもデータが消えない（Cookieで実現できれば追加。）

#Author
佐藤 洋介

#License
フリーライセンス