## Nothing Phone Patch

Nothing Phone Patch の内容

* カメラシャッター音の強制を無効化
* 電源メニューから緊急通報と機内モードを削除
* USB ケーブル着脱時に画面がオンにならないように変更
* ジェスチャーナビゲーションバーのバーを非表示に変更 (不要だったら system/product/overlayのhidenavbarpill.apk を削除で)
* 壁紙のズームを無効化 (されてると思う)
* 2 ボタンナビゲーションバーの追加 (Android 14ベースの場合はNothing Launcherじゃないと正常に使えません) ← 誰か助けてぇー!
* Nothing OS v1.5.Xの環境でもNothing OS 2.0のアプリを使用可能にする (試験的)
* Nothing OS v2.0以降で表示される音量の警告を無効化

をする Magisk モジュールです。  
必要ないものがあれば overlay フォルダにある apk を削除するかデコンパイルして編集してください。

適当に編集をしたんでマジで超適当です。フォークするなりで自由に弄ってください。

### 動作確認済み環境
- Nothing Phone(1) / Nothing OS 1.0.X - 2.6.X
- Nothing Phone(2) / Nothing OS 2.0.X - 3.0.0 Beta
- Nothing Phone(2a) / Nothing OS 2.5.5a - 3.0.0 Beta
- CMF Phone 1 / Nothing OS 2.6.0

の環境でモジュールが動作する事を確認済みです。

Nothing OS v2.0未満でv2.0のアプリを使用したい方は[こちら](https://drive.google.com/drive/folders/1l5v9wuyXmezRqqDYrwJ5z8NPBNFP4XmN)

### English

- Disable Force Camera Shutter Sound.
- Remove emergency calls and airplane mode from the power menu.
- Changed so that the screen does not turn on when the USB cable is attached or detached.
- Changed to hide the gesture navigation bar (remove hideavbarpill.apk in system/product/overlay if you don't need it).
- Disable wallpaper zoom (I think it is).
- Adding a two-button navigation bar.
- Enable Nothing OS 2.0 apps to be used in - Nothing OS v1.5.X environment (experimental)
- Disable Volume Warning.

If you don't need anything, delete or decompile and edit the apk in the overlay folder.

I edited it properly, so it's really suitable. Feel free to fiddle with it by forking it.

Tested On:
- Nothing Phone(1) / Nothing OS 1.0.X - 2.6.X
- Nothing Phone(2) / Nothing OS 2.0.X - 2.6.X
- Nothing Phone(2a) / Nothing OS 2.5.5a - 3.0.0 Beta
- CMF Phone 1 / Nothing OS 2.6.0

## 更新履歴

#### v3
* Nothing OS v2.0以降で表示される音量の警告を無効化とモジュールの名称を変更。

## ライセンス

- [WTFPL](http://www.wtfpl.net/)

```
            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                    Version 2, December 2004

 Copyright (C) 2022 Re*Index.(ot_inc)

 Everyone is permitted to copy and distribute verbatim or modified
 copies of this license document, and changing it is allowed as long
 as the name is changed.

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

  0. You just DO WHAT THE FUCK YOU WANT TO.
```
