![NothingPatch](https://github.com/reindex-ot/magisk-module-nothing/blob/master/.github/title.png?raw=true)
## Nothing Phone(1) Patch

Nothing Phone(1) Patch の内容

* カメラシャッター音の強制を無効化
* 電源メニューから緊急通報と機内モードを削除
* USB ケーブル着脱時に画面がオンにならないように変更
* ジェスチャーナビゲーションバーのバーを非表示に変更 (不要だったら system/product/overlayのhidenavbarpill.apk を削除で)
* 壁紙のズームを無効化 (されてると思う)
* 2 ボタンナビゲーションバーの追加
* Nothing OS v1.5.Xの環境でもNothing OS 2.0のアプリを使用可能にする (試験的)

をする Magisk モジュールです。  
必要ないものがあれば overlay フォルダにある apk を削除するかデコンパイルして編集してください。

適当に編集をしたんでマジで超適当です。フォークするなりで自由に弄ってください。

## 更新履歴

#### v2
* Nothing OS v1.5.X(Android 13)でもNothing OS v2.0のアプリを使用可能にするオプションを追加

  試験的な物なので動作は保証しません。試したい方は[こちら](https://drive.google.com/drive/folders/1l5v9wuyXmezRqqDYrwJ5z8NPBNFP4XmN)

## ライセンス

- [WTFPL](http://www.wtfpl.net/)

```
            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                    Version 2, December 2004

 Copyright (C) 2004 Sam Hocevar <sam@hocevar.net>

 Everyone is permitted to copy and distribute verbatim or modified
 copies of this license document, and changing it is allowed as long
 as the name is changed.

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

  0. You just DO WHAT THE FUCK YOU WANT TO.
```
