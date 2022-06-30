# Description
노마드코더의 NextJS 시작하기 강의 클론 (https://nomadcoders.co/nextjs-fundamentals/)

# Installation
$ npx create-next-app@latest

Running the app
# development
$ npm run dev

# Review
Next.js는 정해진 틀 안에서 커스터마이징하는 **React 기반 프레임워크**
- Create React App으로 생성되는 CSR(Client Side Rendering) 프로젝트는 UI를 가져올 때 React 및 JavaScript 코드를 실행하며 약간의 딜레이가 생긴다
- 반면 Next.js로 생성되는 **SSR(Server Side Rendering)** 프로젝트는 유저가 매우 느린 연결을 사용해도 미리 생성된 HTML 코드를 바로 보여준다 (= **Static Pre Rendering**) 이후 React가 실행- 되며 HTML이 React 컴포넌트가 된다 (= **hydration**)
- 이 경우 검색엔진에서 파악하기 용이해 **SEO**(**Search Engine Optimization**)에도 유리하다
