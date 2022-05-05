# 태그 구조 이해하기

## &#x20;태그 구조 설명 &#x20;

```html
<!doctype html>
<html> <!-- parent-->
    <head> 
    <!-- childeren 자식태그  head : 문서에 대한 정보 , 화면에 안보임 -->
    </head>
    <body> 
    <!-- childeren 자식태그 body : 화면 -->
    </body>
</html> <!-- parent-->

```

## 네이버 favicon&#x20;

```html
<!doctype html>
<html>
    <head>
        <meta charset="utf-8" />
        <title>naver</title>
        <link rel = "shortcut icon" type="image/x-icon" href="./favicon.ico?1">
                                                        <!-- ./  현재 폴더 -->
    </head>
        <body>
        </body>
</html>
```

* 개발자 도구  단축키 f12 , 맥북 command+option+i
* 개발자 도구  -> Elements -> ctrl + f  -> favicon 검색 -> 코드 copy ->  주소 copy -> \
  이미지  html 폴더에 함께 save

