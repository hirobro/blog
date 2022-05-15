# css 선택자

## css

css=cascading style sheet 덮어씌워주

```
<div style= "margin: 0 auto; width: 1080px;" <!--가운데 정렬용 div 인라인 스타-->
```

* 속성명: 속성값; 속성명2: 속성값2;
* margin= 속성명 0 auto; =속성값 ;  width= 속성명2 1080px;=속성값 2
* html은 구조,css 디자인,자바스크립트 동작을 담 인라인 스타일인 현재 코드를 css로 변

### 선택자

선택자는 html의 태그를 선택하는 것

div태그가 많아 누군지 모르기 때문에  태그에 id태그를 이용해 이름을 정해준

```html
<div id= "header-center">
```

```css
div#header-center/* div 삭제가능 #header-center*/ {
 margin: 0 auto;
 width: 1080
 }
```

## htmlcss 링크 걸어주

```html
<!DOCTYPE html>
<html lang="ko">
  <head>
    <meta charset="utf-8" />
    <title>네이버</title>
    <link rel="shortcut icon" type="image/x-icon" href="./favicon.ico?1" />
    <link rel="stylesheet" href="./naver.css" /> <!-- 링크 태그이용 naver.css 파일지-->
  </head>
```

```
```
