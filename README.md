# CameraGameTest_Code
UI操作で使用しているScriptについて

**〇Assets/Scripts**
CameraChanger.cs
→カメラ切り替え、撮影(カメラの判定、)等UIの追加機能を実装

アタッチ先
→CameraChanger(CameraGameScene内)

EffectController.cs
→カメラのフラッシュ機能の実装

アタッチ先
UI_Canvas_StarterAssetsInputs_JoysticksCameraGameScene内)


TimerScript.cs
→タイマー(制限時間)の機能を実装

アタッチ先
UI_Canvas_StarterAssetsInputs_JoysticksCameraGameScene内)


UIController.cs
→各ボタン(ポーズ、クリア、ゲームオーバーなど)の押下時の動作を実装

アタッチ先
UI_Canvas_StarterAssetsInputs_JoysticksCameraGameScene内)


**〇追加Assets周り**

StarterAssets
・Assets/StarterAssets(UI周り)


Inputsustem

StarterAssetsInputs.cs
→UIボタン押下時の動作などを実装
(既存の実装に加えてポーズ、カメラ機能の設定を追記)


Mobile

UICanvasControllerInput.cs
→特に追記はないがUI周りで動作を追加するときに必要な場合がある


ThirdPersonController

ThirdPersonController.cs
→プレイヤ―の動き周りの設定(特に修正なし)


