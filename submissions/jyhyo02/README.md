# 1주차 과제 제출 - 개발 환경 & 웹 기초

## 1. 과제 요약
이번 1주차 과제에서 수행한 내용과 선택 과제 진행 상태입니다.

- 실습 1: 개발 환경 버전 확인 (완료)
	- Node.js, npm, Java, Git, Javac 버전 확인
	- 결과는 practice1-env.md 파일에 정리
- 실습 2: 자기소개 정적 웹 페이지 작성 (완료)
	- HTML/CSS/JS를 사용하여 자기소개 페이지 구현
	- 버튼 클릭 시 alert 표시 및 콘솔에 현재 시간 출력
- 실습 3: Git & GitHub (완료)
	- 개인 GitHub 저장소 생성 후 과제 업로드
	- 개인 저장소 URL: https://github.com/<본인아이디>/<저장소이름>
- 실습 4: React 프로젝트 실행 (선택)
	- 상태: 미진행
	- 사유: 로컬 환경 준비 시간 부족으로 이번 주차에서는 진행하지 못했습니다.
- 실습 5: Spring Boot Hello API (선택)
	- 상태: 미진행

--- 

## 2. 실행 방법

### 2-1. 웹 페이지 실행
1. 폴더 이동

```bash
cd submissions/jyhyo02/week01-page
```

2. 브라우저로 index.html 열기
  - Finder에서 index.html 더블클릭 또는
  - VS Code Live Server 확장으로 실행

### 2-2. 환경 확인 결과 보기
아래 파일에서 실습 1 결과를 확인할 수 있습니다.

- practice1-env.md

### 2-3. GitHub 저장소 확인
실습 3 제출 확인은 아래 저장소에서 할 수 있습니다.

- https://github.com/<본인아이디>/<저장소이름>

## 3. 스크린샷 링크/첨부 안내
아래 방식 중 하나로 스크린샷을 첨부합니다.

- 방식 A: submissions/jyhyo02 폴더 안에 images 폴더를 만들고 이미지 파일 저장
  - 예: images/week01-page.png
- 방식 B: GitHub 이슈/이미지 호스팅 링크를 README에 직접 추가

예시 (로컬 파일 첨부 방식):

```md
![실행 화면](./images/week01-page.png)
```

예시 (외부 링크 방식):

```md
[실행 화면 스크린샷](https://example.com/my-screenshot)
```

선택 과제를 진행한 경우 아래 자료를 함께 첨부합니다.

- 실습 4(React): 변경한 App.js 코드 일부 + 실행 화면
- 실습 5(Spring): /hello API 코드 또는 응답 캡처

## 4. 제출 파일 구조

```text
submissions/jyhyo02/
├── README.md
├── practice1-env.md 
└── week01-page/
		├── index.html
		├── style.css
		└── main.js
```