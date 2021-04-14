#마크다운 정리노트

---

<br><br>

#Heading
총 6가지의 heading

> # Heading 1
>
> ## Heading 2
>
> ### Heading 3
>
> #### Heading 4
>
> ##### Heading 5
>
> ###### Heading 6
>
> <br>

> Paragraph

아무런 기호도 작성하지 않으면 일반 텍스트로 작성된다.

<br><br> #라인

---

언더스코어 세번을 입력하면 라인이 추가된다.
<br><br>

#Text attributes

> This is the **bold** text and this is the _italic_ text and let's do ~~strikethrough~~.

원하는 단어에 별모양(\*\*)으로 감싸주면 볼드체가 되고
별 하나만 감싸 주게 되면 이탈릭으로 만들 수 있다.
그리고 물결 모양 두 개로 감싸주게 되면 strikethrough도 해볼 수 있다.
<br><br>

#Quote

> Don't forget to code your dream.

원하는 문장을 '>'를 통해 quote(인용구) 안으로 넣을 수 있다.
<br><br>

#Bullet list

> Fruits:
>
> - apple
> - banana

별 모양 하나만 앞에 달아주면 목록으로 변환된다.
<br>

> other Fruits:
>
> - apple
> - banana

'-' 를 이용해도 목록을 만들 수 있다.
<br><br>

#Numbered list

> Numbers:
>
> 1.  first
> 2.  second
> 3.  third

숫자를 붙여서 숫자 목록을 만들 수 있다.
<br><br>

#Link
클릭이 가능한 링크

> Click [here](https://www.google.com/)

대괄호 안에 원하시는 단어나 문장을 작성하고 소괄호 안에 원하는 링크를 작성하면 클릭이 가능하게 나타난다.
<br><br>

#Image
![image description](https://en.pimg.jp/070/829/966/1/70829966.jpg)

> ![내용].(주소)
>
> 점은 무시하세요.

느낌표 옆에 대괄호 안에 이미지에 대한 설명을 작성한 다음, 소괄호 안에 이미지 링크를 추가하면 이미지가 나온다.

이미지 사이즈를 바꾸고 싶을 땐 HTMl 태그인 이미지 태그를 이용해서 width(너비)를 지정해주면 된다.
<br><br>

#Table
|Header|Description|
|--|--|

> |     |     |
> | --- | --- |
>
> 점은 무시하세요.

'|' 작대기 사이에 내용을 쓰고 밑에서 다시 작대기를 이렇게 사용하면 테이블로 변환된다.
<br><br>

| Header | Description |
| ------ | ----------- |
| Cell1  | Cell2       |
| Cell1  | Cell2       |
| Cell1  | Cell2       |

> | .   |     |     |     |
> | --- | --- | --- | --- |
> |     |     |
> |     |     |
> |     |     |
>
> 점은 무시하세요.

밑에 이어서 동일하게 작성하면 테이블이 완성된다.
<br><br>

|--|--| 이 부분에 ':'콜론을 붙여 주면 정렬도 할 수 있다.

왼쪽 정렬
|Header|Description|
|:--|:--|
|Cell1|Cell2|
|Cell1|Cell2|
|Cell1|Cell2|

> |:--|:--|

<br><br>

오른쪽 정렬
|Header|Description|
|--:|--:|
|Cell1|Cell2|
|Cell1|Cell2|
|Cell1|Cell2|

> |--: |--: |

<br><br>

가운데 정렬
|Header|Description|
|:--:|:--:|
|Cell1|Cell2|
|Cell1|Cell2|
|Cell1|Cell2|

> |:--: |:--: |

<br><br>

#Code

> To print message in the console, use `console.log('your message')` and ..

문서 안에서 특정한 코드를 보여 주고 싶다면 `(백틱) 키를 이용해서 해당하는 코드를 감싸주면 인라인 형태로 포맷이 가능하다.
<br><br>

```


console.log('your message')

```

다수의 코드가 있는 경우에는 `(백틱) 키를 세 번 누른 다음에 안에 코드를 작성하면 코드블럭이 만들어진다.
<br><br>

> .``` ts console.log('your message') `. ``
>
> 점은 무시하세요.

```ts
console.log("your message");
```

해당 코드에 랭귀지를 표현해주면(어떤 언어인지) 문법이 하이라이트가 된다.

자바스크립트, 자바, 코틀린도 지원이 된다.