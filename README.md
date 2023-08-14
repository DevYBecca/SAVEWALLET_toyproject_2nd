# 📊 가계구조대(SAVEWALLET)

> React, TypeScript, REST API를 활용한 가계부 프로젝트<br />  
> 수입과 지출을 기록, 수정, 삭제할 수 있고 수입, 지출 내역을 리스트와 달력, 차트로 확인할 수 있는 반응형 웹입니다.<br />

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
|                                                            캘린더 페이지                                                             |                                                       메인 페이지, 추가 페이지                                                        |                                                               차트 페이지                                                               |                                                               리스트 페이지                                                               |

## 📌 기술 스택

### Development

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Styled Components](https://img.shields.io/badge/Styled%20Components-DB7093?style=flat&logo=styledcomponents&logoColor=white)

### Config

![npm](https://img.shields.io/badge/Npm-CB3837?style=flat&logo=npm&CB3837&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=Vite&logoColor=white)

### Library

![Recoil](https://img.shields.io/badge/Recoil-3578E5?style=flat&logo=Recoil&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=axios&logoColor=white)
![Chartjs](https://img.shields.io/badge/Chartjs-FF6384?style=flat&logo=chartdotjs&logoColor=white)

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

#### 1. chart.js, react-chartjs-2, chartjs-plugin-datalabels 라이브러리 도입

> 이번 프로젝트의 주제는 '가계부 프로젝트'이기 때문에 통계에서 `수입/지출 내역들을 출력해주는 차트`가 필요했다. 차트 라이브러리 중 가장 점유율이 높고 정보가 많으면서 강사님께서도 추천하신 `Chart.js` 라이브러리를 채택했다.그런데 사용해보니 생각보다 공식 문서가 불친절한 느낌이었고, npm 생태계에서 지원 여부를 확인하고 devDependencies를 설치해야 하기도 했다.<br />

```Bash
$npm install chart.js react-chartjs-2 // React에서 chart.js를 렌더링하기 위한 라이브러리
$npm install -D @types/chart.js // TypeScript에서 사용하기 위한 타입 정의

// @types/chart.js : Chart.js 라이브러리의 타입 정의를 제공함
// @types/react-chartjs-2 : 더 이상 사용X(react-chartjs-2는 자체 유형 정의 제공)
// Chart.js v2일 때 제작된 라이브러리라 뒤에 '2'가 붙음
```

> 차트를 출력할 컴포넌트에서 `ChartOptions`와 `ChartData` 객체로 차트의 속성과 데이터들을 지정해줘야 했는데 범례(legend) 속성이나 데이터 레이블 속성을 커스텀 해주고 싶을 때, 차트를 스타일링 해주고 싶을 때 등의 상황에 대한 공식 문서의 설명이 부족해서 검색이 많이 필요했다. 그래서 주석으로 설명을 최대한 꼼꼼하게 작성하게 되었다.<br />

<img src="https://github.com/DevYBecca/SAVEWALLET_toyproject_2nd/assets/125433485/8ff86852-be97-4d53-8fd5-73c604c94c8d" height=400 />
<img src="https://github.com/DevYBecca/SAVEWALLET_toyproject_2nd/assets/125433485/3b0de6bf-4dbe-4d75-9b4e-e24c0766ef26" height=400 />

<br />

> 그리고 return문에서 출력하는 `차트 컴포넌트의 data 속성에서 타입 에러`가 발생했는데 `react-chartjs-2에서 사용하는 ChartData, ChartOptions 타입이 Chart.js 라이브러리에서 정의된
타입과 일치하지 않아 발생하는 에러`였다. 그래서 TypeScript에서 Chart.js 라이브러리의 타입을 선언해주기 위해 `chart-types.d.ts` 파일을 생성해주었더니 에러가 발생하지 않았다.<br />

```TypeScript
// chart-types.d.ts
import { ChartOptions, ChartDataset } from 'chart.js'

declare module 'chart.js' {
  interface PieDatasetOptions {
    // 사용자 정의 데이터셋 옵션 추가를 위한 인터페이스
    datasetOptions?: ChartDataset
  }

  interface ChartTypeRegistry {
    // Chart.js에서 새로운 차트 유형을 등록하기 위한 인터페이스
    customPie: {
      // 사용자 정의 차트 유형 추가
      chartOptions?: ChartOptions<'pie'> // 해당 차트 유형에 대한 옵션 지정
      datasetOptions?: PieDatasetOptions // 데이터셋에 대한 옵션 지정
    }
  }
}
// chart-types.d.ts 파일은 Chart.js 라이브러리의 타입을 확장하는 역할
// 모듈 확장 선언을 하기 때문에 export 키워드 사용 X
// chart-types.d.ts에서 선언한 타입 내용들이 chart.js 모듈에 추가됨
```

#### 2. components와 hooks 분리

> Chart 컴포넌트와 SubChart 컴포넌트에서 차트를 출력하는 로직이 주요 내용이 되도록 `내역을 조회하는 기간을 선택하는 컴포넌트 및 내역을 출력해주는 리스트 같은 부가적인 요소들을 components 파일에 분리`했다. 그리고 `ChartHooks.ts 파일에 Chart 컴포넌트에서 사용하는 함수 및 SubChart 컴포넌트로 넘겨줄 state들을 업데이트하는 함수들을 분리`해주었다. 그 결과 Chart와 SubChart 컴포넌트의 코드 가독성을 높일 수 있었던 것 같다. <br />

<img src="https://github.com/DevYBecca/SAVEWALLET_toyproject_2nd/assets/125433485/0574a4bc-e33d-42ca-9037-45a636c3106e" height=400 />

<br />

#### 3. recoil로 state 상태 관리하기

> 프로젝트 초반에 조원들과 상태 관리를 어떤 방식으로 해야할지 이야기를 나눌 때, 다른 조원분께서 이전 프로젝트에서 `recoil을 사용했는데 사용법이 간결해서 금방 배울 수 있었던 게 장점`이라고 추천해주셔서 recoil로 상태를 관리해보기로 했다. recoil 폴더에 `recoil로 관리하는 state들을 atom으로 지정`해주고, state를 관리할 컴포넌트에서 `useRecoilState()`로 state를 가져오면 된다. 그리고 set 함수로 상태를 업데이트해주면 recoil을 이용한 state 상태 관리가 가능하다! redux로 상태를 관리할 때는 state, slice, reducer, combineReducer, configStore 등 구성 요소가 많은데 recoil은 처음 사용할 때 부담이 확실히 적은 것 같다.<br />

```TypeScript
// DateState.ts
import { atom } from 'recoil'
//Recoil의 상태를 표현하는 단위
// Atoms 업데이트 시 해당 Atom을 구독하는 모든 컴포넌트가 업데이트
export const dateState = atom<number>({
  key: 'dateState',
  default: new Date().getMonth() + 1
})
// 디폴트값은 현재월로 설정

// SelectedCategoryState.ts
export const selectedCategoryState = atom<string | null>({
  key: 'selectedCategoryState',
  default: null
})

// SelectedDateState.ts
export const selectedDateState = atom({
  // 디폴트값은 현재 월로 설정
  key: 'selectedDateState',
  default: { year: 2023, month: 7 }
})

// ChartHooks.ts
export const useChartHandlers = () => {
  const navigate = useNavigate()
  const [selectedDate, setSelectedDate] = useRecoilState(selectedDateState)
  const [, setSelectedCategory] = useRecoilState(selectedCategoryState)
  // ...
   // 카테고리 Click Event Handler
  const handleCategoryClick = category => {
    setSelectedCategory(category)
  }

  // SubChart 컴포넌트 이동
  const handleShowSubChart = category => {
    setSelectedCategory(category)
    navigate('/subchart', { state: { category } })
  }
  // ...
```

#### 4. 반응형 웹으로 구현하기

> 프론트엔드 개발인만큼 반응형 웹으로 구현하는 것이 적합하지만 시간이 부족해서 시도를 하지 못한 경우가 많았다. 이번 프로젝트는 api 구성이 간단하여 반응형으로 구현해보기로 했다. 프로젝트에서 스타일링을 `styled-component`를 채택했는데 `style 폴더의 theme.ts` 파일에 device별 break-point가 될 width를 정의해주고, theme.ts를 전역에서 사용이 가능하도록 App.tsx에서 `ThemeProvider` 컴포넌트에 theme를 속성으로 감싸주면 전역에서 반응형으로 컴포넌트를 구현할 수 있다.<br />

```TypeScript
// theme.ts
export const size = {
  mobile: '770px',
  tablet: '1023px',
  laptop: '1460px'
}

export const theme = {
  mobile: `(max-width: ${size.mobile})`,
  tablet: `(min-width: ${size.mobile}) and (max-width: ${size.tablet})`,
  laptop: `(min-width: ${size.tablet}) and (max-width: ${size.laptop})`,
  desktop: `(min-width: ${size.laptop})`,
  // ...

// App.tsx
export const App = () => {
  return (
    <>
      <ThemeProvider theme={theme}>
        <Outlet />
      </ThemeProvider>
    </>
  )
}
```

> Chart.js의 경우 출력된 차트를 반응형으로 출력해주는 속성을 지원하고 있기 때문에 컴포넌트 내에서 따로 반응형 작업을 추가해주지 않아도 문제 없이 잘 출력되었다. device별 width를 각각 지정해주면 `@media (min-width: 770px) {}`의 형식을 매번 작성해줘야 하기 때문에 전역에서 사용이 가능한 theme 파일을 생성하여 관리해주는 방법을 다음에 필요한 경우 적용해 봐야겠다!

<br />

## 📌 프로젝트 회고

> 쇼핑몰 토이 프로젝트 이후 곧바로 진행한 두 번째 프로젝트였는데 api 구성이 생각보다 간단해서 새로운 라이브러리를 공부해보고 도입하고 싶어 차트 파트를 담당해서 진행했다. Chart 컴포넌트에서 출력하는 `Pie Chart`의 데이터 라벨을 차트 내부가 아닌 outlabel 형식으로 커스텀 해주고 싶었는데, Chart.js에서는 지원하지 않는 속성이라 chartjs-plugin-datalabels 라이브러리로 차트 내부에서 위치 조정을 해주는 방식으로 구현을 하게 되었다. 그리고 이번 프로젝트에서 GitHub의 `issue를 이용하여 협업하는 방법`을 배웠는데 팀원 간의 작업현황을 직접 의사소통을 하지 않고도 알 수 있다는 점이 큰 장점으로 느껴졌다. 팀장님께서 초기 개발 세팅을 해주신 `repository를 로컬에 clone 했을 때 import문에서 절대경로로 작성해둔 내용을 인식하지 못하는 에러`를 만나 다양한 방법을 시도해보았는데 갑자기 절대경로가 인식이 되면서 그 당시 `작업하고 있던 stash의 내용이 다 날아가버리는 일이 있었다😭` 아직도 어떤 이유에서 에러가 해결이 된 것인지 파악하지 못해 그 당시 남겨놓았던 터미널 로그를 확인해보고 그 내용에 대해 정리해둬야 할 것 같다🙌🏻

<br />

## 📌 담당 페이지 리팩토링(23.08.14)

<details>
<summary>보기</summary>
<div markdown="1">

### 차트 페이지 & 서브차트 페이지

#### 1. `<>...</>`(empty fragment) → `<React.Fragment>...</React.Fragment>` 변경

> React 16 ver.부터는 Fragment를 empty fragment의 단축 구문으로 사용할 수 있다. React에 대해 처음 배울 때 `Fragment를 <div>로 묶어주기 싫다면 빈 Fragment로 바꿔주면 된다`고 배웠는데 프로젝트 제출 후 멘토님께서 `<React.Fragment>`를 사용하면 좋겠다는 리뷰를 남겨주셔서 찾아보니 Fragment의 전통적인 문법 형태인데 명시적으로 Fragment를 사용했음을 표현할 수 있고, map() 함수 등을 사용했을 때 key 값을 속성에 지정해줘야 한다면 empty fragment에는 사용할 수 없어 React.Fragment를 사용해야 한다고 한다!

<br />
