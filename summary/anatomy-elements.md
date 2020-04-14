# HTML의 요소 분석

```html
<p>My name is Devinan</p>
```

시작태그, 즉 Opening tag는 `<p>` 이런식으로 그리고 닫힌태그, 즉 Closing tag는 `</p>` 이다.

## 중첩 요소

<p>Element가 서로 겹치지 않고 서로 완전히 쌍을 이루도록 태그를 중첩해야한다.</p>

```html
    <p>This is <em>very <strong>wrong</em>!</strong></p>
```

```html
<p>
  This <em>is <strong>correct</strong>.</em>
</p>
```

## Block vs inline Elements

html에서는 블록 요소와 인라인 요소로 구분한다. 먼저 블록 요소를 살펴보자.

- **블록요소** : 블록 수준의 요소는 웹사이트내에서 블록의 구조가 보일수 있는 형태이다. 블록 요소가 있으면 그 이전 혹은 이후에 어떤 내용이 나오든 새로운 줄이 나타난다.
  > 블록 수준의 요소는 인라인 요소안에 중첩 할수가 없다!!! 메모메모
- **인라인요소** : 인라인 수준의 요소는 블록의 구조가 아닌 문서의 내용의 작은 부분만 둘러싸는 요소이다. 인라인 요소는 새로운 줄이 생기지 않는다. 일반적인 텍스트의 형태가 나온다.

> !!! 여기서 언급하는 block, inline 개념은 CSS의 display 개념이 아니다. 주의 해야 한다.

## 단일 Elements

모든 html의 요소 Opening tag, Closing tag 는 아니다. 즉 단일 태그도 존재한다.
예를 들어 이미지 태그가 있다.

```html
<img src=../images/img.png>
```

결과:

<img src=../images/img.png>

## Attributes

<p>
    속성은 시작태그에 위치하고 있습니다. 이름과 값으로 구성되어 있습니다. 값과 이름은 "="으로 구분됩니다. 속성 값이 있을경우는 blockquote로 둘러싸여 있으며 속성값이 없을 경우는 공백 문자 또는 큰 따움표나 작은 따옴표를 사용해서 묶어야합니다. = 값이 빈 문자열 인 경우 ""문자와 함께 값을 생략 할 수 있습니다.
</p>

```html
<!-- empty attributes -->
<input name="address" disabled />
<input name="address" disabled="" />

<!-- attributes with a value -->
<input name="address" maxlength="200" />
<input name="address" maxlength="200" />
<input name="address" maxlength="200" />
```
