# kt_7th_miniproject
웹 프레임워크 Django를 사용하여 ChatGPT API 활용한 사이트 제작

프로젝트 구성
---
![1](https://github.com/rakkeshasa/kt_7th_miniproject/assets/77041622/952275e0-140e-49d2-93a3-e036594e8e02)

수어 번역 AI 모델을 mlflow에 업로드 후 홈페이지에서 수어 이미지가 들어오면 모델을 통해 </BR>
수어를 번역한 후ChatGPT한테 질문

프로젝트 개요
---
- 농아인들은 손으로 대화를 합니다. 이를 수화 혹은 수어라고 합니다.
- 수화는 하나의 의사소통 수단, 수어는 언어의 의미를 담고 있습니다.
- 일반인이 수어를 배워서 농아인들과 대화할 수 있지만 쉬운일은 아니다.
- 이미지 분류를 통해서 수어를 알파벳으로 번역하는 AI 서비스 ROQKF

프로젝트 데이터
---
![2](https://github.com/rakkeshasa/kt_7th_miniproject/assets/77041622/f7e695ab-4c30-4491-b737-5e22f3e1e495)

데이터 원본: https://www.kaggle.com/datasets/datamunge/sign-language-mnist

제작한 AI 모델
---
![7](https://github.com/rakkeshasa/kt_7th_miniproject/assets/77041622/7d9ffae1-14b0-4f7e-8eda-4b49f12f603d)

코드 구현
---
- ChatGPT API 활용

![1](https://github.com/rakkeshasa/kt_7th_miniproject/assets/77041622/740b0ca8-0e7d-4390-803b-0e04798c1ce2)

- 로그인 기능 구현

![2](https://github.com/rakkeshasa/kt_7th_miniproject/assets/77041622/aa562918-72b3-4adb-9143-72a8bf75c133)


사용한 도구
---
- Visual Studio Code
- ChatGPT API
- WinSCP
- Putty
- AWS
- Django
- mlflow
- Bootstrap

프로젝트 주요 기능
---
- 수어 번역
- ChatGPT와 대화
- 회원가입 및 로그인 기능

프로젝트 산출물
---
- 메인페이지![3](https://github.com/rakkeshasa/kt_7th_miniproject/assets/77041622/861443e0-e8bb-4802-beb1-6ab673c2854c)
- 로그인페이지![4](https://github.com/rakkeshasa/kt_7th_miniproject/assets/77041622/74eb069d-5ac5-452b-acca-06be7fdb6f99)
- ChatGPT대화 페이지![5](https://github.com/rakkeshasa/kt_7th_miniproject/assets/77041622/cd2b460d-2f38-4272-87be-c6ff2eff6031)
- 수어 ChatGPT대화 페이지![6](https://github.com/rakkeshasa/kt_7th_miniproject/assets/77041622/d2f7c518-6568-4845-8e5a-0205e0d3b0ff)


담당 역할
---
- 수어 번역 AI모델 개발
- 인프라 담당
- Django 백엔드 담당

개선할 점
---
- 대화 페이지에서 버튼 누르면 새로고침이 되는 문제
- Bootstrap css 수정이 잘 안된점
- 수어 대화 페이지에서 파일 추가를 여러번하면 수어로 문의하기 버튼이 창에 가려서 안눌리는 점
- 통일되지 못한 nav bar메뉴
