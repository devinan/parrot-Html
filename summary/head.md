# head 안을 살펴보기

`<head>`는 `<body>`와 달리 사용자에게 문서의 컨텐츠 영역에 보여질수 없습니다.

head 는 브라우저에게 이 문서의 메타데이터, 혹은 정보를 설명합니다. (ex: 제목, 설명, 저자....)

```html
<head>
  <meta charset="UTF-8" />
  <title>Hello world!</title>
</head>
```

head 에는 여러내용이 많이 들어 갈수 있습니다. 사용자가 head의 내용을 보려면 개발자 도구를 켜서 확인 하실수 있습니다.

## Meta Data

메타 데이터는 charset 외에도 여러 종류가 있습니다.

- 문자열 인코딩: `<meta charset="encodingtype">`

- `name`(메타요소 유형) 과 `content`(실제 메타 컨텐츠 내용) 이 존재합니다.
  - `<meta name="author" content="Devinan">`: 저자 정보
  - `<meta name="description" content="this is a description">`: 설명 정보
