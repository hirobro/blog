# Emmet, HTML 빠르게 마크업하기

## 주석처리된 부분 입력시 아래 태그가 입력

```html

<!-- ! -->>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>



<!-- div -->
<div></div> 
<!--div.class --><!--.class-->
<div class="class"></div> 
<!--div.id --><!--.id--><!--div#-->
<div class="id"></div> 




<!--div>ul>li-->
<div>
    <ul>
        <li></li>
    </ul>
</div>

<!--div>ul+ol-->
<div>
    <ul></ul>
    <ol></ol>
</div>   

<!-- * -->
<!--ul>li*5-->>
<ul>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
</ul>


<!-- ^ -->
<!--div>ul>li^ol-->
<div>
    <ul>
        <li></li>
    </ul>
    <ol></ol>
</div>


<!-- () -->
<!--div>(header>ul>li*2>a)+footer>p-->
<div>
    <header>
        <ul>
            <li><a href=""></a></li>
            <li><a href=""></a></li>
        </ul>
    </header>
    <footer>
        <p></p>
    </footer>
</div>


<!--{}-->
<!--p{hello}-->
<p>hello</p>

<!--{$}-->
<!--p.class${item}*5-->
<p class="class1">item</p>
<p class="class2">item</p>
<p class="class3">item</p>
<p class="class4">item</p>
<p class="class5">item</p>


<!--lorem-->
<!--p>lorem4-->
<p>Lorem ipsum dolor sit.</p>
```
