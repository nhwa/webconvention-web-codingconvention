# coding convention

## HTML Convention
HTML 코드를 작성할때 다음과 같은 기본 규칙을 준수한다.

### HTML 코드 작성 규칙

#### 1. HTML 문서는 반드시 DTD를 선언한다.
새로운 HTML 문서를 작성할 때 'HTML5'를 사용한다.
```html
<!DOCTYPE html>
```
#### 2. 인코딩 선언
신규 HTML 문서를 작성할 때 기본 인코딩은 utf-8을 원칙으로 한다.
```html
<meta charset="utf-8">
```
#### 3. 들여쓰기
마크업의 중첩이 깊어질 때마다 자식 요소는 1탭 들여 쓰고, 1탭의 크기는 공백 4칸으로 설정한다.
문서 내에서 반드시 탭을 이용하여 들여쓰기를 하며, 탭을 대신하여 공백으로 띄어 들여쓰지 않는다.

#### 4. 주석
1. HTML 코드의 주석은 코드 그룹을 구분하거나, 참고해야 하는 사항을 기술한다.
2. HTML 주석의 시작과 종료는 아래와 같이 표기, 기본 형식에 맞게 작성한다.

```html
<!-- 주석내용 -->
<div>
...
</div>
<!-- //주석내용 -->
```

**_너무 많은 주석은 유령문자 버그를 생성하므로 되도록 자제 한다._**
```html
<! -- comments -- > (X) 시작하는 구분자("<!")와 주석을 시작하는 구분자("--") 사이에는 공백 문자(white space)가 올 수 없다.
<!--- comments ---> (X) 코멘트 내용에서 두개 이상의 하이픈('-')을 연속해서 사용하면 안된다.
<!-- comments -->   (O) 
```

#### 5. 영문 소문자 사용
DTD를 제외한 모든 요소와 애트리뷰트는 소문자로 작성한다.
```html
<DIV Class="wrap"> wrap </DIV> (X)
<div class="wrap"> wrap </div> (O)
```

#### 6. Character entity references (문자 엔티티 참조)를 사용
특수 기호는 문자 엔티티 참조를 사용하여 코드로 변환한다.
HTML 5의 Character references : https://dev.w3.org/html5/html-author/charref
```html
<h4> Q&A </h4> (X)
<h4> Q&ampA </h4>(O)
```
#### 7. 빈 줄
의미 있는 객체를 구분하기 위하여 코드 그룹 간 1줄씩 빈 줄을 만드는 것은 허용한다. 
빈 줄의 간격은 1줄을 초과하지 않는다.
```html
<head>
  내용
</head>
# 빈 줄
<body>
</body>
```

#### 8.

#### BEM : Block Element Modifier

#### .block__element--modifier

#### block: 전체를 감싸고 있는 블록요소

#### element : 내부요소

#### modifier : 기능
