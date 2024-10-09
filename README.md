# Map Tool

<img src ="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"> <img src ="https://img.shields.io/badge/Direct_X-006600?style=for-the-badge&logo=directx&logoColor=black"> <img src ="https://img.shields.io/badge/MFC-%23E34F26?style=for-the-badge&logo=mfc&logoColor=white"> <img src ="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white"> 

## Project
이 프로젝트는 현재 미완성 상태입니다. 향후 업데이트를 통해 기능 추가와 버그 수정을 진행할 예정입니다.

## Overview

DirectX와 MFC를 활용하여 제작된 Map Tool로, 게임 맵을 제작하기 위한 다양한 기능을 제공합니다.

## Features
- **맵 사이즈 및 Texture 선택** : 사용자 정의로 맵의 크기와 Texture를 선택 가능.
  
- **WireFrame 기능** : 맵의 구조를 WireFrame 형식으로 확인 가능.

- **FBX 파일 로드** : FBX 파일을 불러와 맵에 오브젝트 배치 가능.

- **프러스텀 컬링** : SpaceDivision과 Frustum을 사용해 프러스텀 컬링 기능 구현.

- **맵 페인팅** : 맵 Texture의 R, G, B, A 4개의 채널을 사용해 맵에 페인팅 가능.

- **마우스 피킹** : 마우스 피킹 기능을 사용하여 맵에 배치한 오브젝트의 위치, 회전, 크기 조절 가능.

- **맵 높이 조절** : 마우스 피킹 기능을 사용하여 맵의 높이를 조절 가능.

## Setting
1. **파일 구조**: 실행 파일의 상위 폴더에 `data`, `fbx`, `_shader` 폴더가 있어야 합니다.
   - `data`, `fbx` 파일의 이름이나 위치를 변경하면 데이터를 불러올 수 없습니다.
     
   ![파일 구조](https://github.com/user-attachments/assets/eb82801d-44ae-4f12-ab02-567f539b4ac1)

2. **필요한 파일**: 실행 파일과 같은 폴더에 `fmod.dll`과 `DefaultMap.hlsl` 파일이 필요합니다.
   ![필요한 파일](https://github.com/user-attachments/assets/b39027d2-8754-43d6-83ee-9c5acb1f921b)

* 위 과정은 Release 파일을 생성해(exe파일) 실행할 경우에 해당합니다.

## How To Use

* 카메라 이동 : 키보드 W, A, S, D

* 카메라 회전 : 마우스 우 클릭 드래그

* 마우스 피킹 : 마우스 좌 클릭

|  |   |
|---|---|
|메인 화면|맵 생성|
|<img width="450" alt="image" src="https://github.com/user-attachments/assets/cb35d270-4e7e-43f7-8f96-c35718011f03">|<img width="450" alt="image" src="https://github.com/user-attachments/assets/96f1f44a-0abe-46eb-b90d-ace255e7af66">|
|FBX 로드|FBX 배치|
|<img width="450" alt="image" src="https://github.com/user-attachments/assets/7136bbef-866d-4dfb-9066-56439b1ee4d4">|<img width="450" alt="image" src="https://github.com/user-attachments/assets/d677c141-f013-4740-835b-b3816e9c0a96">|
|오브젝트의 Transform| 맵 페인팅 |
|<img width="450" alt="image" src="https://github.com/user-attachments/assets/7ccf6e63-1a1d-404b-b0cb-6ea711df0202"> |<img width="450" alt="image" src="https://github.com/user-attachments/assets/da2541df-b716-4b95-9369-c3e99669294a">
|맵 높이 조절 화면| 맵 높이 조절 |
|<img width="450" alt="image" src="https://github.com/user-attachments/assets/f2069afe-6bce-4c9f-9bb4-4385b04ceecc"> |<img width="450" alt="image" src="https://github.com/user-attachments/assets/2183d7c4-5179-4296-83dd-35fc93ed5795"> | 



