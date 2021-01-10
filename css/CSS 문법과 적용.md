# CSS 문법과 적용

## CSS 문법
```css
h1 { color: yellow; font-size:2em; }
```
- 선택자(selector) - "h1"
- 속성(property) - "color"
- 값(value) - "yellow"
- 선언(declaration) - "color: yellow", "font-size: 2em"
- 선언부(declaration block) - "{ color: yellow; font-size:2em; }"
- 규칙(rule set) - "h1 { color: yellow; font-size:2em; }"


## CSS 주석
```css
/* 주석 내용 */
/*
    주석은 여러 줄로도
    선언 할 수 있습니다.
*/
```


## CSS 적용
1. inline style
    ```css
    <div style="color:red;"> 내용 </div>
    ```

1. internal style
    ```css
    <style> div {color: red;} </style>
    ```

1. external style
    ```css
    <link rel="stylesheet" href="css/style.css">
    ```

1. import
    ```css
    @import url("css/style.css");
    ```