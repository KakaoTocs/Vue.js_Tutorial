

## 2. View Instance

View Instance: 뷰로 화면을 개발하기 위한 필수적으로 생성하는 **기본 단위**

```javascript
new Vue({
    el: '#app',
    data: {
        message: 'Hello Vue.js!'
    }
});
```

* new Vue({...}): **인스턴스**
* el: '#app': el 속성 & View Instance가 그려질 지정
* data: {  message: 'Hello Vue.js!' }: data 속성

**new Vui()**로 **인스턴스를 생성**하고, 인스턴스 안에 **el 속성**으로 뷰 인스턴스가 **그려질 지점**을 정한다. 그 후 **data속성에 message 값을 정의**해 **화면의 {{ message }}에 연결** 했다.

