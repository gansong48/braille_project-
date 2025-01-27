# 닷앤닥 (dot(.) and doc)

점자 문서 제작을 위한 이미지-텍스트-점자 변환 애플리케이션<br>

## 프로젝트 기간 및 팀원

- 기간: 2021년 4월 27일 ~ 2021년 11월 30일
- 팀원: 5명

## 프로젝트 소개

- 사용자가 디바이스를 통해 촬영하거나 이미지/텍스트 파일을 업로드하면, 점자 문서를 수정 및 저장할 수 있도록 제공하는 모바일 애플리케이션입니다.
- 사용자는 점역할 텍스트를 업로드하면 별도의 추가 변환 없이 점자 프린터로 출력 가능한 문서를 다운로드합니다.
- 본 애플리케이션은 직관적인 인터페이스와 즐겨찾기 등 부가적인 기능을 포함하여 사용자 편의성을 높입니다.

## 프로젝트 기능

- 사진에서 텍스트로, 텍스트에서 BRF 파일로 변환이 하나의 애플리케이션에서 가능합니다.
- 애플리케이션에서 업로드된 파일 확인 및 즐겨찾기 기능을 제공합니다.
- 이미지에서 문자를 추출하는 OCR 기능과 추출한 문자를 점자로 변환하는 기능을 사용합니다.
- 사용자가 선택한 이미지에서 문자를 추출하여 TXT 파일로 저장 → 저장된 TXT 파일은 사용자가 선택하면 점자 문서인 BRF 파일로 변환합니다.
- 정확성 향상을 위해 TXT 파일의 오탈자를 수정하는 기능을 추가하였고, 즐겨찾기를 통해 개별 파일을 관리할 수 있어 사용자의 편의를 높였습니다.

## 기술스택

- **Backend**: Python
- **Frontend**: Android Studio, Kotlin
- **Database**: SQLite
- **Deployment**: AWS Lambda, AWS Amplify

## 프로젝트 산출물

<img src="./images/1.png" alt="Image1" width="400"/>
<img src="./images/2.png" alt="Image1" width="400"/>
<img src="./images/3.png" alt="Image1" width="400"/>
<img src="./images/4.png" alt="Image1" width="400"/>

- 시연영상 링크: https://m.youtube.com/watch?v=P4vnPOT8wHs&feature=youtu.be
