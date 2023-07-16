# JavaScript만으로 작은 노션 구현하기

컴포넌트를 구성하고 History API를 이용하여 작은 노션을 구현했습니다.

문서들이 트리구조로 렌더링 되도록 하였습니다. localStorage를 활용하여 open한 문서는 다시 접속해도 open된 상태로 보여지게 됩니다.

부모 컴포넌트에서 자식 컴포넌트로만 데이터를 넘기는 단방향 데이터 바인딩 방식으로 코드를 작성했습니다. 이를 통해 프로젝트가 커지더라도 데이터 흐름을 예측하기 쉽게 만들었습니다.

Webpack을 이용해 자바스크립트 코드를 번들링했습니다. 이를 통해 IIFE로 코드가 실행되게 만들어 파일 단위의 자바스크립트 모듈을 관리할 때 생길 수 있는 유효 범위 문제를 방지하였습니다.

[Tiny Notion 바로가기](https://metamong.site/)

<br />

## 기능 소개

- 최상단에서 새로운 문서 생성

<img src="https://user-images.githubusercontent.com/93233930/229355247-3d0b24d4-997e-48bc-90e6-0664de03f759.gif" alt="최상단에서 새로운 문서 생성" width="100%">

<br />
<br />

- 새로운 문서에서 하위 문서 생성

<img src="https://user-images.githubusercontent.com/93233930/229355252-62e8bf70-472c-4ff3-8199-41091580e263.gif" alt="새로운 문서에서 하위 문서 생성" width="100%">

<br />
<br />

- 문서 삭제

<img src="https://user-images.githubusercontent.com/93233930/229355338-49717fb2-690f-4271-ad6e-f5c43835ea82.gif" alt="문서 삭제" width="100%">

<br />

## 기술 스택

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=000000"/> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=000000"/> <img src="https://img.shields.io/badge/Amazon CloudFront-FF4F8B?style=for-the-badge&logo=Amazon CloudFront&logoColor=000000"/> <img src="https://img.shields.io/badge/Github Actions-2088FF?style=for-the-badge&logo=Github Actions&logoColor=000000"/> <img src="https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=Webpack&logoColor=000000"/>
