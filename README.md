# OVRCharacterController
VRゲーム中にキャラクタコントロール

VRMのモデルファイルを読み込んで、フルトラッキングでキャラクタを操作するアプリです。

# VRゲーム中にも同時起動可能

通常のUnityアプリと違い、VRゲームと同時起動ができます。
HMDと両手コントローラーのみ、
HMDと両手コントローラーと腰トラッカー(現在問題あり)、
HMDと両手コントローラーと両足トラッカー、
HMDと両手コントローラーと腰と両足トラッカー
それぞれのキャリブレーションに対応しています。

OVRCharacterControllerを最初に起動し、その後VRゲームを起動してください。

#基本の操作方法
起動するとコントロールパネルが表示されます。
VRMモデル読み込みを押して、任意のVRMモデルを読み込んでください。
モデルのライセンスが表示されますので、問題なければ同意しますを押してください。
その後、モデル読み込みウインドウを閉じて、キャリブレーションボタンを押します。
画面の指示通りに進めてください。

キャラクタが表示されている画面をマウスで操作するとカメラがコントロールできます。
ホイール：ズーム
右クリック＋ドラッグ：カメラの移動

リリースページ：[https://github.com/sh-akira/OVRCharacterController/releases]
ダウンロードはリリースページからOVRCharacterController.zipをダウンロードしてください。
解凍後Build.exeを実行で開始します。


(ソースコードは準備中です)

まだテスト版です。テストが不十分の可能性が大いにあります。
何か問題があった際は、Twitterでお問い合わせください。
下記の問題は把握しています。
[@sh_akira](https://twitter.com/sh_akira)

テスト環境：
OS: Windows 10 (1803)
CPU:Core i7 8700k
GPU: Geforce GTX1080Ti
Mem: 16GB
VR: Vive


見つかった問題
・腰のトラッカーのみでトラッキングした際に、地に足付かない。
