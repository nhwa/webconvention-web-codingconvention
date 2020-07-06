# tutorial Hompage

## coding convention

### HTML 코드 작성 규칙
1.HTML 버전 - HTML5 사용
```html
<!DOCTYPE html>
```
2.들여쓰기
왼쪽 열부터 오른쪽으로 일정한 간격(tab)만큼 띄어 쓰기를 통해 HTML 구조 생성

3.주석
1) HTML 코드의 주석은 코드 그룹을 구분하거나, 참고해야 하는 사항을 기술
2) 마크업 수정 시, 수정부분을 표기하는 주석은 날짜를 기입하여 사용

```html
<!-- 2012-12-25 주석내용 -->
<div>
...
</div>
```

notice
시작하는 구분자("<!")와 주석을 시작하는 구분자("--") 사이에는 공백 문자(white space)가 올 수 없다.
```
text
<! -- comments (X) -->
<!-- comments (△) -- > 내용을 종료하는 "--"와 코멘트을 종료하는 ">" 사이에는 공백 문자(white space)가 올 수 있다.
<!--- comments (X) ---> 코멘트 내용에서 두개 이상의 하이픈('-')을 연속해서 사용하면 안된다.
```

#### BEM : Block Element Modifier

#### .block__element--modifier

#### block: 전체를 감싸고 있는 블록요소

#### element : 내부요소

#### modifier : 기능
