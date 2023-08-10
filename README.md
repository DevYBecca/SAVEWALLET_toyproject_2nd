# 📊 가계구조대(SAVEWALLET)

> React, TypeScript, REST API를 활용한 가계부 프로젝트<br />  
> 수입과 지출을 기록, 수정, 삭제할 수 있고<br />  
> 수입, 지출 내역을 리스트와 달력, 차트로 확인할 수 있는 반응형 웹입니다.<br />

<br />

## 📌 프로젝트 소개

> **패스트캠퍼스 프론트엔드 개발 부트캠프 5기**<br />  
> **개발 기간** : 2023.07.05 - 2023.07.24<br />  
> **배포 링크** : **[SAVEWALLET](https://savewallet.netlify.app/)**<br />  
> **Repository** : [SAVEWALLET](https://github.com/FEGROUP9/SAVEWALLET)<br />

<br />

## 📌개발 팀원 및 역할

| <a href="https://github.com/hookor"><img src="https://avatars.githubusercontent.com/u/115582699?v=4" width=200px alt="안중후" /></a> | <a href="https://github.com/7581058"><img src="https://avatars.githubusercontent.com/u/100559990?v=4" width=200px alt="김다슬" /></a> | <a href="https://github.com/DevYBecca"><img src="https://avatars.githubusercontent.com/u/125433485?v=4" width=200px alt="윤금엽" /></a> | <a href="https://github.com/leechanghwi"><img src="https://avatars.githubusercontent.com/u/128275359?v=4" width=200px alt="이창휘" /></a> |
| :----------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------: |
|                                                 [안중후](https://github.com/hookor)                                                  |                                                 [김다슬](https://github.com/7581058)                                                  |                                                 [윤금엽](https://github.com/DevYBecca)                                                  |                                                 [이창휘](https://github.com/leechanghwi)                                                  |
|                                                          캘린더 페이지                                                          |                                                        메인 페이지, 추가 페이지                                                         |                                                            차트 페이지                                                             |                                                            리스트 페이지                                                             |

<br/>

## 📌 기술 스택

### Development
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Styled Components](https://img.shields.io/badge/Styled%20Components-DB7093?style=flat&logo=styledcomponents&logoColor=white)

### Config
![npm](https://img.shields.io/badge/Npm-CB3837?style=flat&logo=npm&CB3837&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=Vite&logoColor=white)

### Library  
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=axios&logoColor=white)
![Recoil](https://img.shields.io/badge/Recoil-3578E5?style=flat&logo=Recoil&logoColor=white)
![FullCalendar](https://img.shields.io/badge/FullCalendar-4285F4?style=flat&logo=GoogleCalendar&logoColor=white)
![Chartjs](https://img.shields.io/badge/Chartjs-FF6384?style=flat&logo=chartdotjs&logoColor=white)
![MUI](https://img.shields.io/badge/MUI-007FFF?style=flat&logo=mui&logoColor=white)

### Enviroment  
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/Github-181717?style=flat&logo=github&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=flat&logo=VisualStudioCode&logoColor=white)

### Deployment  
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat&logo=netlify&logoColor=white)

### Cowork Tools  
![Miro](https://img.shields.io/badge/Miro-050038?style=flat&logo=miro&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat&logo=slack&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white)
![Zoom](https://img.shields.io/badge/Zoom-2D8CFF?style=flat&logo=zoom&logoColor=white)

<br />

## 📌 프로젝트 테스트

### clone project

```bash
$ git clone https://github.com/FEGROUP9/SAVEWALLET.git
```

### install npm

```bash
$ npm install
```

### start project

```bash
$ npm run dev
```

<br />

## 📌구현 페이지와 주요 기능

**1️⃣ 메인 페이지**

- 현재 로그인 중인 사용자의 이번 달 수입/지출 합계 조회
- 현재 로그인 중인 사용자의 오늘 수입/지출 합계 조회
- 지출 내역, 달력, 차트, 수입/지출 입력 페이지로 이동
- 메뉴 슬라이드에서 로그인 클릭 시 로그인 페이지로 이동
- 메뉴 슬라이드에서 로그아웃 클릭 시 로그아웃

**2️⃣ 수입/지출 입력 페이지**

- 기록할 수입/지출 선택
- 기록할 금액 입력
- 기록할 사용처(메모) 입력
- 기록할 날짜, 시간 선택
- 저장 버튼을 통한 기록 추가

**3️⃣ 지출내역 페이지**

- 기록한 내역 월별 조회
- 기록한 날짜, 기록한 카테고리, 사용처 조회
- 기록한 날의 총 수입, 총 지출, 수입/지출 합계 조회
- 모달을 통한 기록 수정
- 내역 삭제
- 달력, 차트, 입력 페이지로 이동

**4️⃣ 달력 페이지**

- 기록한 내역 월별 달력으로 조회
- 내역 클릭 시 날짜별 작성된 수입/지출 금액 조회
- 내역 클릭 시 날짜별 작성된 수입/지출 카테고리
- 내역 클릭 시 날짜별 작성된 수입/지출 사용처 조회
- 내역, 차트, 입력 페이지로 이동

**5️⃣ 차트 페이지**

- 기록된 내역 월에 따른 카테고리별 수입/지출 차트로 조회
- 기록된 내역 월 별 수입/지출 총액 조회
- 기록된 카테고리 리스트 출력
- 카테고리별 수입/지출 총액 출력
- 각 카테고리 클릭 시 카테고리별 월별 서브차트 조회로 이동  
  - 기록된 내역이 없는 월로 이동시 입력 페이지로 이동할 수 있도록 알림

**6️⃣ 서브차트 페이지**

- 기록한 내역 카테고리별, 월별 수입/지출 총액 차트로 조회
- 기록한 내역 카테고리별 전체 조회
- 내역, 달력, 입력 페이지로 이동

**7️⃣ 로그인 페이지**

- 카카오 로그인 API를 통한 로그인
- 메인 페이지로 돌아가기

<br />

## 📌폴더 구조

<details>
<summary>보기</summary>
<div markdown="1">

```
📦 SAVEWALLET
├─ .eslintrc.cjs
├─ .gitignore
├─ .prettierrc
├─ README.md
├─ index.html
├─ netlify.toml
├─ package-lock.json
├─ package.json
├─ public
│  └─ favicon.ico
├─ src
│  ├─ api
│  │  ├─ DeleteList.ts
│  │  ├─ EditList.ts
│  │  ├─ ExpensesSummary.ts
│  │  ├─ FetchCategoryExpenses.ts
│  │  ├─ LogAccount.ts
│  │  ├─ LogExpense.ts
│  │  ├─ MonthlyExpenses.ts
│  │  ├─ axios.ts
│  │  └─ index.ts
│  ├─ assets
│  │  ├─ kakao_login_medium_wide.png
│  │  └─ logo_gradi.png
│  ├─ components
│  │  ├─ App.tsx
│  │  ├─ chart
│  │  │  ├─ ChartList.tsx
│  │  │  ├─ IncomeExpensesFilter.tsx
│  │  │  ├─ PeriodRange.tsx
│  │  │  └─ PieChartOptions.ts
│  │  ├─ common
│  │  │  ├─ DeleteItem.tsx
│  │  │  ├─ EditModal.tsx
│  │  │  ├─ ErrorComponent.tsx
│  │  │  ├─ Footer.tsx
│  │  │  ├─ Header.tsx
│  │  │  ├─ Loading.tsx
│  │  │  ├─ Month.tsx
│  │  │  ├─ NotFound.tsx
│  │  │  ├─ ViewLogs.tsx
│  │  │  └─ index.ts
│  │  ├─ home
│  │  │  └─ SlideMenu.tsx
│  │  ├─ index.ts
│  │  ├─ list
│  │  │  └─ ListItems.tsx
│  │  └─ subchart
│  │     ├─ BarChartOptions.ts
│  │     └─ ChartList.tsx
│  ├─ hooks
│  │  ├─ ChartHooks.ts
│  │  └─ index.ts
│  ├─ main.tsx
│  ├─ pages
│  │  ├─ Calendar.tsx
│  │  ├─ Chart.tsx
│  │  ├─ Home.tsx
│  │  ├─ KakaoLogin.tsx
│  │  ├─ List.tsx
│  │  ├─ LogAccount.tsx
│  │  ├─ Router.tsx
│  │  ├─ SignIn.tsx
│  │  ├─ SubChart.tsx
│  │  └─ index.ts
│  ├─ recoil
│  │  ├─ DateState.ts
│  │  ├─ SelectedCategoryState.ts
│  │  ├─ SelectedDateState.ts
│  │  └─ index.ts
│  ├─ style
│  │  ├─ fonts
│  │  │  └─ global.ts
│  │  ├─ index.ts
│  │  └─ theme.ts
│  ├─ types
│  │  ├─ chart-types.d.ts
│  │  ├─ font.d.ts
│  │  ├─ fonts.d.ts
│  │  └─ subchart-types.d.ts
│  └─ vite-env.d.ts
├─ tsconfig.json
├─ tsconfig.node.json
└─ vite.config.ts
```

</div>
</details>

<br />

## 📌구현 화면

| 메인페이지(모바일)                            | 메인페이지(데스크탑)                           |
| --------------------------------------------- | ---------------------------------------------- |
| ![image](./src/assets/readme/mobile_home.png) | ![image](./src/assets/readme/desktop-main.png) |

| 지출/소비 입력 페이지(모바일)                       | 지출/소비 입력 페이지(데스크탑)                             |
| --------------------------------------------------- | ----------------------------------------------------------- |
| ![image](./src/assets/readme/mobile_logaccount.png) | ![image](./src/assets/readme/desktop-signin-logaccount.png) |

| 지출/소비 내역 페이지(모바일)                 | 지출/소비 내역 페이지(데스크탑)                       |
| --------------------------------------------- | ----------------------------------------------------- |
| ![image](./src/assets/readme/mobile_list.png) | ![image](./src/assets/readme/desktop-signin-list.png) |

| 달력 페이지(모바일)                               | 달력 페이지(데스크탑)                                     |
| ------------------------------------------------- | --------------------------------------------------------- |
| ![image](./src/assets/readme/mobile_calendar.png) | ![image](./src/assets/readme/desktop-signin-calendar.png) |

| 차트 페이지(모바일)                            | 차트 페이지(데스크탑)                                  |
| ---------------------------------------------- | ------------------------------------------------------ |
| ![image](./src/assets/readme/mobile_chart.png) | ![image](./src/assets/readme/desktop-signin-chart.png) |

| 서브차트 페이지(모바일)                           | 서브차트 페이지(데스크탑)                                 |
| ------------------------------------------------- | --------------------------------------------------------- |
| ![image](./src/assets/readme/mobile_subchart.png) | ![image](./src/assets/readme/desktop-signin-subchart.png) |

<br />

## 📌 담당 페이지 및 기능 구현

### 차트 페이지 & 서브차트 페이지

#### 1.

<br />

## 📌 프로젝트 회고
