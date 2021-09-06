# js-webpack-boilerplate

SPA를 염두해두고 만들어진 자바스크립트 웹팩 보일러 플레이트

# 사용법

- clone
    ```
    git clone https://github.com/ludacirs/js-webpack-boilerplate.git <디렉토리 이름> 
    ```

- 설치
    ```
    npm install
    ```

- 실행
 
    빌드시
    ```
    npm run build
    ```
 
    빌드 및 서버 실행시
    ```
    npm start
    ```

# 스택

## 로더

- babel-loader: ECMAScript2015 이상의 코드를 적당한 하위 버전에서도 호환될 수 있게 바꾸어주는 로더
- css-loader: css를 자바스크립트에서 불러와서 사용하기 위해 모듈로 바꿔주는 로더
- style-loader: 모듈로 바꾼 css를 돔에 적용시켜주는 로더
- postcss-loader: css 전처리 (sass, scss)등을 사용할 수 있게 해주는 로더

## 플러그인

- html-webpack-plugin: 빌드 과정에서 명시한 html파일의 output을 따로 생성해주는 플러그인 
- clean-webpack-plugin: 빌드시에 이전에 빌드되었던 파일들을 삭제시켜주는 플러그인

## Dev Tool

- inline-source-map: 빌드 과정에서 생긴 에러의 디버깅을 쉽게하기 위해 에러가 난 곳의 코드를 빌드가 되기 전 코드에 매핑시켜주는 툴

## 그외

- normalize.css: 브라우저마다 차이가 존재하는 기본 스타일을 표준화 시켜주는 css