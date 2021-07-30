---
title: SSG 란 무엇인가?
date: "2021-07-30T22:40:32.169Z"
description: .
---

#SSG.... 쓱..?!

```toc

```

## 1. About SSG (Static Site Generator)

- 정적사이트생성기(Static Site Generator)는 정적인 웹사이트를 생성해주는 툴로서 일반적으로 마크다운 파일을 읽어 Web Page 를 생성한다.
- 서버에서는 미리 생성 된 HTML 을 Client 에 제공한다. 이를 통해 웹페이지 로딩 및 화면 간 전환이 빨라 사용자의 체감속도가 빠르고, UX 만족도를 높일 수 있다.

## 2. About [Gatsby](https://ko.reactjs.org/docs/create-a-new-react-app.html#gatsby)

> Gatsby는 정적 웹사이트를 React로 만들기에는 최고의 방법입니다. React 컴포넌트를 사용하게 해주지만 미리 렌더링 된 HTML과 CSS를 사용하여 가장 빠르게 로드됩니다.

## 3. What is [Gatsby starter?](https://www.gatsbyjs.com/starters/?)

- Starters are boilerplate projects that Gatsby developers can use to set up a new site quickly. Before creating a starter, it may be helpful to peruse the Gatsby Starter Library to see what already exists and determine how your starter will provide value.

## 4. GraphQL(Graph Query Language)

- Client 에서 서버로 필요한 data 를 요청할 때 사용
- 기존 REST API → 엔드포인트로 요청을 보냄 → 미리 정해진 구조의 응답을 받아 데이터를 사용
- GraphQL → 클라이언트는 능동적으로 자신이 필요한 데이터를 선택하여 서버에게 질의할 수 있음

## 5. [GraphQL in Gatsby](https://www.gatsbyjs.com/docs/tutorial/part-4/)

- compile 타임에 내부에서 Query 를 통해 data 를 받아오는데 사용 됨
- 동일한 HTML template 을 기반으로 data 를 주입하여 각각의 page 를 생성

## 6. 사용 예시 및 준비

- node 설치 (npm)
- Gatsby CLI 설치
- 사용하기 편리한 Editor
- [Github Repository](https://github.com/)
- [Netlify](https://www.netlify.com/)

## 7. 활용 방안

- Project 종료 후 사용자 메뉴얼 Document → Web page 로 제공
- 온라인 가이드 page 생성 (API 인터페이스 Document 등)
  → 예시 Site, 공상평 챗봇 플랫폼, Github Page
  → LINK : [https://caas-manual.github.io/caas/channel_front_ui.html#인증-토큰-받아오기](https://caas-manual.github.io/caas/channel_front_ui.html#인증-토큰-받아오기)
