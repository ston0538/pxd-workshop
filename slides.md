---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: "text-center"
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
---

# pxd XE그룹 이슬비 파트 OKR 

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 p-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Next <carbon:arrow-right class="inline"/>
  </span>
</div>

<a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
  class="abs-br m-6 text-xl icon-btn opacity-50 !border-none !hover:text-white">
<carbon-logo-github />
</a>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# 2021년 OKR 회고 

2021년 OKR 목록
- ⭐️ **KR1**
  - 업무스킬 강화 (부족한 스킬에 대한 강화): 월 1회 이상 각자 선정한 내용으로 개인 학습 후 학습 내용 포스팅 및 파트 회의 시간에 포스팅에 대한 간단한 피드백 진행

- ⭐️ **KR2**
  - 프론트엔드 프로젝트 경험하기: Front-End 개발 프로젝트를 경험해보지 않은 파트원 (대상인원 : 2명)"

- ⭐️ **KR3**
  - 디자인 시스템 만들기 (그룹전체)	
<br>
<br>

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# 2021년 OKR 회고 

결과

- ⭐️ KR1 업무스킬 강화


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>
---

# 2021년 OKR 회고 

결과

- ⭐️ KR2 업무스킬 강화


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# 2021년 OKR 회고 

결과

- ⭐️ KR3 업무스킬 강화


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# 2022년 OKR 목표 

2022년 OKR 목록
- ⭐️ **KR1**
  - 업무스킬 강화 (부족한 스킬에 대한 강화): 그룹 블로그 기능 개선 목록을 만들어서 각자 필요한 스킬과 매칭되는 기능 개선 건을 진행해볼 수 있도록 함	 

- ⭐️ **KR2**
  - 코드 퀄리티 향상	 

---

# 2022년 OKR 목표 

어떻게 진행 할 것인가

️⭐️ **KR1**
- 스킬 메트릭스 점수를 기준으로 부족한 점을 파악 (2021.9월 기준)

<div class="skill-root">
  <div v-click class="absolute w-80 kang">
   - 강은영 <br>
   - 비동기 점수 1.5  <br>
   - 리액트 점수 2  <br>
   - Infinite Scroll 페이징 구현 (리엑트, 비동기)
  </div>
  <div v-click class="absolute w-80 kang">
   - 이선주 <br>
   - 댓글 기능
   - 리액트 점수 2  <br>
   - Infinite Scroll 페이징 구현 (리엑트, 비동기)
  </div>
  <table>
    <thead>
      <tr>
        <th>항목</th>
        <th>상세</th>
        <th>강은영</th>
        <th>이선주</th>
        <th>홍도영</th>
        <th>김현기</th>
        <th>이희원</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th rowspan="4">HTML/CSS</th>
        <td>HTML, CSS 문법을 숙지하고 있으며, 웹표준 시맨틱 마크업을 할 수 있다.</td>
        <td>5</td>
        <td>5</td>
        <td>5</td>
        <td>5</td>
        <td><span class="red">4.5</span></td>
      </tr>
      <tr>
        <td>CSS 전처리기를 사용할 수 있다. (ex : Sass, Less..)</td>
        <td>4</td>
        <td>5</td>
        <td>4</td>
        <td>4</td>
        <td>3.5</td>
      </tr>
      <tr>
        <td>레이아웃 및 공통(공통 요소들의 모듈화) 가이드를 설계할 수 있다.</td>
        <td>5</td>
        <td>4.5</td>
        <td>5</td>
        <td>5</td>
        <td>4</td>
      </tr>
      <tr>
        <td>반응형웹에 대해 이해하고 있으며 코딩할 수 있다.</td>
        <td>4.5</td>
        <td>4.5</td>
        <td>5</td>
        <td>4</td>
        <td>5</td>
      </tr>
      <tr>
        <th>Web Accessibility</th>
        <td>웹 접근성 가이드를 숙지하고 있으며, 작업시 적용/구현 가능하다.</td>
        <td>4</td>
        <td>4.5</td>
        <td>4</td>
        <td>3.5</td>
        <td>3</td>
      </tr>
      <tr>
        <th>Cross Browsing</th>
        <td>IE, CR, SA, FF 등 크로스브라우징을 할 수 있다.</td>
      </tr>
      <tr>
        <th rowspan="4">Javascript</th>
        <td>Javascript 기본 문법을 알고 있다.</td>
      </tr>
      <tr>
        <td>재사용 가능한 객체로 코드를 작성한다.</td>
      </tr> 
      <tr>
        <td>TypeScript 문법에 대해 알고 있으며, 코딩 할 수 있다.</td>
      </tr>
      <tr>
        <td>비동기 통신에 대해 이해하며, 코딩 할 수 있다.</td>
      </tr>
      <tr>
        <th>Interaction</th>
        <td>코드로 애니메이션이나 인터랙션을 구현 할 수 있다.</td>
      </tr>
      <tr>
        <th rowspan="3">Frameworks</th>
        <td>Vue.js 프레임워크를 이용해 코딩 및 다양한 라이브러리를 활용할 수 있다.</td>
      </tr>
      <tr>
        <td>React.js 프레임워크를 이용해 코딩 및 다양한 라이브러리를 활용할 수 있다.</td>
      </tr>
      <tr>
        <td>jQuery를 이용해 UI Script를 작성 및 수정할 수 있다.</td>
      </tr>
    </tbody>
  </table>
</div>



<style>
table {
  font-size: 10px;
}
table th {
  padding: 3px;
}
table td {
  padding: 6px;
}
.skill-root {
  position: relative
}
.kang {
  position: absolute;
  top: -126px;
  right: 10px;
  background-color: #fff;
  color: orange;
  padding: 1.1em;
  border: 1px solid #fff;
  font-size: 11px;
}
span.red{
  color: red;
}
</style>


---

# 2022년 OKR 목표 

어떻게 진행 할 것인가

️⭐️ **KR2**

코드 퀄리티 향상 

- 단순히 블로그 기능 개선을 각자 맡아서 진행하는 것이 아닌 파트 내부에서 각각의 코드 리뷰를 진행	코드 리뷰는 깃헙에서 진행하며, 본인 코드에 대한 확인이 없다는게 저희 그룹원 모두의 문제라고 생각해 다수의 리뷰를 받아 본인 코드에 대한 확신을 갖게 하고 코드 퀄리티를 높이는 것이 목표

- 업무 협업 툴 git의 적극적인 활용 (풀 리퀘스트 등록 후 댓글로 리뷰, 명확한 커밋 메세지 사용)	협업 툴로 git을 적극적으로 활용할 수 있게 파트에서 먼저 실행해본 후 해당 가이드를 노션에 업데이트, 그룹원 모두가 코드 컨벤션처럼 git 가이드를 보고 따라 할 수 있게 하고자 함

- [github flow](https://docs.github.com/en/get-started/quickstart/github-flow)
- [commit convention](https://www.conventionalcommits.org/en/v1.0.0/)
---

# 2022년 OKR 목표 

어떻게 진행 할 것인가

️⭐️ **KR2**

코드 퀄리티 향상

- 짝코딩
	- 짝 프로그래밍은 둘이서 동시에 프로그래밍을 하면서 프로그램을 더 낫게 만들려고 노력하는 두사람 사이의 대화다.
		- 서로 일에 집중 하도록 해준다.
		- 시스템을 더 좋게 다듬기 위해 무엇을 할 수 있을지 브레인스토밍 한다.
		- 떠오른 생각을 명료하게 다듬어 준다.
		- 한 사람이 막힐 때 주도권을 다른 사람에게 넘김으로써, 짜증을 덜 나게 해준다.
		- 팀에서 지키기로 한 실천방법을 서로 책임지고 지키도록 한다.


---

# 2022년 OKR 목표 

어떻게 진행 할 것인가

️⭐️ **KR2**

코드 퀄리티 향상

- 코드리뷰 도입
	- [Code review - Wikipedia](https://en.wikipedia.org/wiki/Code_review)
		- 더 나은 코드 품질
		- **결함 찾기**
		- **학습/지식 이전**
		- **상호 책임 의식 증가**
		- 더 나은 솔루션 찾기



---



---

# Learn More

[Documentations](https://sli.dev) / [GitHub Repo](https://github.com/slidevjs/slidev)
