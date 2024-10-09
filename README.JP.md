# Map Tool

<img src ="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"> <img src ="https://img.shields.io/badge/Direct_X-006600?style=for-the-badge&logo=directx&logoColor=black"> <img src ="https://img.shields.io/badge/MFC-%23E34F26?style=for-the-badge&logo=mfc&logoColor=white"> <img src ="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white"> 

## Project
このプロジェクトは現在未完成の状態です。 今後のアップデートで、機能の追加とバグの修正を行う予定です。

## Overview

DirectXとMFCを活用して製作されたMap Toolで、ゲームマップを製作するための様々な機能を提供します。

## Features
- **マップサイズ及びTexture選択**:ユーザー定義でマップのサイズとTextureを選択可能。

- **WireFrame機能**:マップの構造をWireFrame形式で確認可能。

- **FBXファイルロード** : FBXファイルを読み込んでマップにオブジェクトを配置可能。

- **Frustum Culling**:SpaceDivisionとFrustumを使用してFrustum Culling機能を実装。

- **マップペイント**:マップTextureのR、G、B、Aの4つのチャンネルを使用してマップにペイントが可能。

- **マウスピッキング**:マウスピッキング機能を使用してマップに配置したオブジェクトの位置、回転、サイズ調節が可能。

- **マップの高さ調節**:マウスピッキング機能を使用してマップの高さを調節可能。

## Setting
1.**ファイル構造**:実行ファイルの上位フォルダに `data`, `fbx`, `_shader` フォルダが必要です。
   - `data`, `fbx` ファイルの名前や位置を変更すると、データを読み込めません。
     
   ![ファイル構造](https://github.com/user-attachments/assets/eb82801d-44ae-4f12-ab02-567f539b4ac1)

2. **必要なファイル**: 実行ファイルと同じフォルダに `fmod.dll`と `DefaultMap.hlsl` ファイルが必要です。
   ![필요한 파일](https://github.com/user-attachments/assets/b39027d2-8754-43d6-83ee-9c5acb1f921b)

* 上記のプロセスは、Release ファイルを生成し（exe ファイル）実行する場合に該当します。

## How To Use

* カメラ移動:キーボードW·A·S·D

* カメラ回転:マウスを右クリックした状態でドラッグ

* マウスピッキング:マウス左クリック

|  |   |
|---|---|
|メイン画面|マップの生成|
|<img width="450" alt="image" src="https://github.com/user-attachments/assets/cb35d270-4e7e-43f7-8f96-c35718011f03">|<img width="450" alt="image" src="https://github.com/user-attachments/assets/96f1f44a-0abe-46eb-b90d-ace255e7af66">|
|FBXロード|FBX配置|
|<img width="450" alt="image" src="https://github.com/user-attachments/assets/7136bbef-866d-4dfb-9066-56439b1ee4d4">|<img width="450" alt="image" src="https://github.com/user-attachments/assets/d677c141-f013-4740-835b-b3816e9c0a96">|
|オブジェクトのTransform|マップのペイント |
|<img width="450" alt="image" src="https://github.com/user-attachments/assets/7ccf6e63-1a1d-404b-b0cb-6ea711df0202"> |<img width="450" alt="image" src="https://github.com/user-attachments/assets/da2541df-b716-4b95-9369-c3e99669294a">
|マップの高さ調節の画面| マップの高さ調節 |
|<img width="450" alt="image" src="https://github.com/user-attachments/assets/f2069afe-6bce-4c9f-9bb4-4385b04ceecc"> |<img width="450" alt="image" src="https://github.com/user-attachments/assets/2183d7c4-5179-4296-83dd-35fc93ed5795"> | 




