# react-router 사용법

## npm i react-router-dom@6.4 터미널을 이용해 설치합니다.

## useNavigate 사용법

유저를 를 다른곳으로 이동시키는 방법
1.Link 유저가 클릭해야함
2.useNavigate 개발자가 의도한대로 이동시킬수있음

```tsx
// Header.tsx에서
const onAboutClick = () => {
  navigate("/이동시킬 컴포넌트");
};

return <button onClick={onAboutCiick}>About</button>;
```

# Outlet 컴포넌트

Route의 자식들을 render 합니다
