# **02. 개발 환경 설정**

## 01. 설치

1. 크롬 브라우저
    2. Atom 텍스트 에디터 (https://atom.io/)
3. Node.js 
4. Vue.js devtools(크롬 확장 플러그인)

## **02. Atom 설정**

1. **테마 설정**

    Atom -> Preferences -> Install -> Themes -> seti-ui, atom-material-syntax-dark 설치

    * seti-ui: 직관적인 파일 아이콘 제공
    * atom-material-syntax-dark: 자바스크립트 코드 구문 강조색의 조합 👍

    Themes -> UI Theme -> Seti 선택

2. **패키지 설치**

    * language-due: 싱글 파일 컴포넌트 제공

## **03. Node.js 설치**

1. Node.js 설치

    https://nodejs.org/ko/

    Terminal에서 node -v로 버전 확인

## **04. Vue 개발자 도구 설치**

​	https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd

## **05. Hello Vue.js!**

Vue 작업 순서는 **HTML 파일 생성 -> Vue 소스 코드 추가 -> 브라우저로 실행** 으로 이루어 진다.

```html
<html>
    <head>
        <title>Vue Sample</title>
    </head>
    <body>
        <div id="app">
            {{ message }}
        </div>
        <script src="https://cdn.jsdelivr.net/npm/vue@2.5.2/dist/vue.js"></script>
        <script>
            new Vue({
                el: '#app',
                data: {
                    message: 'Hello Vue.js!'
                }
            });
        </script>
    </body>
</html>
```

코드 작성후 브라우저에서 실행하면 아래처럼 보인다.
<img src="/02_First_project/Hello_Vue.js!.png" alt="Hello, Vue.js" style="zoom:50%;" /> 