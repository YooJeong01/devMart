# ![Image](https://github.com/user-attachments/assets/fb2d5b6f-c814-4c81-b159-36ec3fcb9238) devMart

- 사용자는 **개발자 상품을 탐색**하고, **찜**, **장바구니 담기**, **바로 결제** 기능을 이용할 수 있습니다.  
- **개발자 유형 테스트**를 통해 **추천 아이템**을 확인할 수 있습니다.  
- **단축키를 활용한 이스터에그**로 숨겨진 밈 콘텐츠를 즐길 수 있습니다.  
- **상품 리스트 정렬 기능**(최신순, 인기순, 구매순)과 **좌측 카테고리 필터**, **플로팅 버튼** 등 다양한 UI 기능을 제공합니다.
- **노션형 질문 남기기 기능**을 제공하여 자유롭게 질문을 등록할 수 있습니다.


## 미리보기
#### 👇 아래 사진 클릭시 실행 영상 화면으로 이동합니다 👇
[![Video Label](https://github.com/user-attachments/assets/03d89ed7-b957-4236-8140-fb4ec1c03c43)](https://youtu.be/3VP03anxoFA)


## 프로젝트 구조
```
/devMart
├── /client
│ ├── /assets                  # 이미지, 효과음
│ ├── /features                # 주요 기능별 모듈
│ │ ├── /change-theme          # 테마 전환 기능
│ │ ├── /developer-survey      # 개발자 유형 테스트
│ │ ├── /easter-egg            # 밈 이스터에그
│ │ ├── /navigation            # 좌측 내비게이션 메뉴
│ │ ├── /notes                 # 마크다운 노트 기능
│ │ ├── /product-sort          # 상품 정렬 기능
│ │ ├── /rendering             # 상품 리스트 렌더링 관련 기능
│ │ ├── products.js            # 상품 데이터 정의
│ │ ├── shuffle-products.js    # 상품 무작위 정렬
│ │ └── storage.js             # localStorage 제어
│ ├── index.html
│ ├── main.js
│ ├── reset.css
│ └── style.css
├── /node_modules
├── .gitignore
├── .prettierrc.cjs
├── db.json
├── eslint.config.mjs
├── package-lock.json
├── package.json
└── README.md


```

## 주요 기능

- 🛒 플로팅 버튼을 통한 **상품 찜하기 / 장바구니 담기 / 바로 결제 기능**
- 🧩 **개발자 유형 테스트**로 **추천** 아이템 확인
- 🎮 **단축키를 이용한 이스터에그(밈) 출력**
- 🗂️ **카테고리 필터 및 상품 정렬 기능** 제공
- 🧭 **좌측 네비게이션을 통한 섹션 이동**
- 🌓 **라이트/다크 모드** 지원
- 💾 **로컬스토리지를 통한 데이터 저장**
- 📱 **반응형 웹사이트**
- ⚙ **웹 접근성 향상**
- 📄 **노션형 질문 남기기 기능**
- 📥 **API를 활용한 통신 및 노트 CRUD 기능 구축**

## 시작하는 방법

1. 프로젝트 실행 전, 터미널에서 아래 명령어를 입력해 주세요.  
   (※ `npm`이 설치되어 있어야 합니다.)
    
    ```bash
    npm install    # 최초 1회 패키지 내용 설치
    npm run dev    # 클라이언트 실행
    ```

2. [배포 링크](https://devmart-final.netlify.app/)로도 접속하실 수 있습니다.

## devMart 기획
![Image](https://github.com/user-attachments/assets/4cf86a28-9268-42dc-930a-228f6ce8869c)
![Image](https://github.com/user-attachments/assets/658da4b3-d366-4ebd-a4be-9af70673a6ff)
![Image](https://github.com/user-attachments/assets/2075c19e-e658-49f6-a545-0cb3c357680b)
![Image](https://github.com/user-attachments/assets/4f50b55a-f2f6-4883-b1c2-0d0575f1d6fe)
![Image](https://github.com/user-attachments/assets/ee65b9fc-ab83-40f8-b17e-b32cfb1a19c6)
![Image](https://github.com/user-attachments/assets/c3d35f92-7ae5-4884-a0f9-c757203d93b7)
![Image](https://github.com/user-attachments/assets/6b88d8a2-c860-4fb6-9f6c-9e2d680098f5)
![Image](https://github.com/user-attachments/assets/14cd239f-0039-4432-84fa-0c15878d5557)
![Image](https://github.com/user-attachments/assets/3cdd3731-1706-4d9f-8890-3967eb44cff1)


## 웹사이트 화면 시나리오
![Image](https://github.com/user-attachments/assets/aee03ce2-402a-4407-9309-601e42fe34a7)
![Image](https://github.com/user-attachments/assets/c80183d6-f020-4d03-b1e7-61066fbe22c1)
![Image](https://github.com/user-attachments/assets/23aeabe1-c8e0-4395-be37-fc1c4e226a86)
![Image](https://github.com/user-attachments/assets/698041b4-8dea-4fce-918e-3c37b711c50f)
![Image](https://github.com/user-attachments/assets/123aa728-16c1-40bb-9517-c3103903eedf)
![Image](https://github.com/user-attachments/assets/cbe097b8-1a17-4d6a-9356-60d1c2220b12)
![Image](https://github.com/user-attachments/assets/dc391b48-986d-4398-8d5c-4067e26213c0)

## 모바일 화면 시나리오
![Image](https://github.com/user-attachments/assets/f2d6c5a3-0dc3-470b-b328-6a1d0ae0f202)
![Image](https://github.com/user-attachments/assets/44cf1313-2624-42f6-8543-177cbd2c8249)
![Image](https://github.com/user-attachments/assets/32ad6004-8768-4df7-9f64-c2a9032eda8a)
![Image](https://github.com/user-attachments/assets/1296dac9-4ce4-4a3f-b74e-377b85ca3a0e)
![Image](https://github.com/user-attachments/assets/21a53b17-b07a-414b-afd2-106ee9baa7ad)
![Image](https://github.com/user-attachments/assets/10878ff4-43cb-4aaa-a264-cca23b3ea2fc)
![Image](https://github.com/user-attachments/assets/743e1bd9-79d5-4bda-b9e5-099cec0de5a7)




## 구조도 및 협업/개발툴
![Image](https://github.com/user-attachments/assets/324699ca-28c2-4240-821e-8e4273b9d6dc)



## 커밋 컨벤션

| 타입 | 설명 |
|------|------|
| [Feat] | 새로운 기능 추가 |
| [Fix] | 버그 수정 |
| [Docs] | 문서 수정 (README 등) |
| [Style] | 코드 포맷팅, 세미콜론 누락 등 기능 변경 없는 수정 |
| [Refactor] | 코드 리팩토링 (기능 변화 없음) |
| [Perf] | 성능 향상 관련 수정 |
| [Test] | 테스트 코드 추가/수정 |
| [Build] | 빌드 관련 파일 수정 (예: package.json) |
| [Ci] | CI 설정 수정 (예: GitHub Actions) |
| [Chore] | 기타 변경사항 (예: 주석, 리드미, 패키지설정) |
| [Revert] | 이전 커밋 되돌리기 |




## 코드 컨벤션

### 파일 & 폴더 구조

| 구분 | 규칙 | 예시 |
| --- | --- | --- |
| 폴더명 | 케밥케이스 | `/product-list`, `/self-test` |
| 파일명 | 케밥케이스 | `product-list.js`, `product-card.js` |
| 공통 스타일 | `style.css` |  |

### 변수명 & 함수명

| 영역 | 명명 규칙 | 예시 |
| --- | --- | --- |
| JS 함수명 | 카멜케이스 | `renderProductList()` |
| JS 변수명 | 카멜케이스 | `productListArray` |
| Boolean 변수 | is/has/can + 카멜케이스 | `isActive` |

### HTML

| 구분 | 규칙 | 예시 |
| --- | --- | --- |
| class | 케밥케이스 | `product-list`, `nav-button`, `dark-mode-toggle` |
| id | 케밥케이스 | `product-list-section`, `side-navigation` |

### CSS

| 구분 | 규칙 | 예시 |
| --- | --- | --- |
| CSS 변수 | 케밥케이스 | `--color-primary`, `--color-bg` |
| 클래스명 | HTML 규칙 동일 (케밥케이스) | `product-card` |
```
margin은 top이 아닌 bottom으로 밀어주기
```

### 주석(JSDoc)

모든 export 함수에는 JSDoc 작성 권장

```jsx
/**
 * 상품 리스트를 렌더링합니다.
 * @returns {void}
 */
export function renderProductList() {
  // ...
}
```
### 들여쓰기
```
들여쓰기는 한 칸 Tab 으로 한다.
```

### 줄바꿈
```
매개변수가 4개 이상일 경우, 줄바꿈 한다.
```

### 브랜치 관리 전략
```
main과 기능별 브랜치를 따로 만들어서 관리한다.
예시) feature/developer-survey -> 설문조사 기능 브랜치
```
----



## 멤버

| 황유정 | 이소민 | 이승은 |
| --- | --- | --- |
| ![Image](https://github.com/user-attachments/assets/22ac8949-8279-463f-84a5-8b2b9404c123) | ![Image](https://github.com/user-attachments/assets/f70a3bf5-30e3-4908-8c1c-34f6fe54a531) | ![Image](https://github.com/user-attachments/assets/6a2dbd4b-0ab9-4836-83bf-6e73bc761c0d) |
| FE | FE | FE |
| 팀장 | 팀원 | 팀원 |
| [GitHub](https://github.com/YooJeong01) | [GitHub](https://github.com/mintsky0172) | [GitHub](https://github.com/seungdev) |
