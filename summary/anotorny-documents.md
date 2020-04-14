# HTML 문서의 기본 구조

HTML 페이지 문서를 살펴보자

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Parrot</title>
  </head>
  <body>
    <h1>First Title</h1>
    <p>This is a <a href="demo.html">Link</a>sample.</p>
    <!-- this is a comment -->
  </body>
</html>
```

- `<!DOCTYPE html>` 문서유형이 html이라는 정보를 알리기 위한 짧은 문자열입니다.

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
```

- `<html></html>`: `<html>`의 요소, 페이지 모든것을 포함하는 요소입니다.
- `<head></head>`: `<head>`의 요소, 웹 페이지에서 사용자가에게 보여지는 컨텐츠 영역이 아닙니다. 여기에는 컨텐츠에 css를 넣을 수있으며 웹페이지의 제목, 키워드, 설명을 넣을 수 있습니다.
- `<meta charset="utf-8">`: 이 요소는 문서에 UTF-8 형식으로 charcter 설정을 명시합니다. 이 설명은 사람의 언어를 대다수 번역/또는 글자 출력이 정상적으로 작동됩니다. 이 설명은 어떠한 언어여도 거의 다 적용이 되므로 이유 없이 복사해서 붙여도 됩니다. 왜냐하면 적용하지 않았을경우에 언어가 깨지는 경우가 발생합니다. --> 뷁두ㅑㅇ려
- `<title></title>`: `<title>`의 요소, 페이지의 제목을 설정하게 됩니다. 브라우저의 텝을 보시면 titel이 적용되게 만들어 줍니다.
- `<body></body>`: `<body>`의 요소, 페이지에서 사용자가 볼수 있는 공간입니다.
