객체화 ( Objectification )
---
html의 tag, css의 property는 자체로는 객체가 아니지만
브라우저가 이것들을 *객체화*한다.
자바스크립트는 이 객체를 이용하여 *브라우저를 제어*한다

예를 들어, image 크기를 동적으로 바꾸고 싶다면 
`<img>` 태그가 가지는 `width` property를 가져와 수정하면 된다
```
// img tag가 1개일 때에만 유효
var img = document.getElementByTagName('img'); 
```

