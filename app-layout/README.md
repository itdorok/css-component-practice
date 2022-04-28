## grid template

```
grid-row
grid-column

row와 column의 위치를 지정한다
```

```css
body {
  display: grid;
  grid-template-columns: 80px 400px 1fr 250px;
  grid-template-rows: 80px 1fr;
}

nav {
  grid-row: 1/-1;
}

menu {
  grid-column: 2/-1;
}
```

## :last-child(),margin

<br>

<img src="lastChild.png" width="50%">

```
trash button을 button:last-child로 선택

margin-left:auto;로 지정하면
오른쪽에 붙고 왼쪽 여백이 자동으로 조절됨
```

## scroll

```css
section {
  display: flex;
  flex-direction: column;
  overflow: scroll;
}
.menu {
  height: 96px;
  flex-shrink: 0;
}
```

- section안의 element를 수직으로 정렬

- flex-shrink: 0은 아이템의 크기를 컨테이너에 맞춰서 줄이지 않도록 설정

- overflow: scroll로 section 크기를 넘어가는 element는 스크롤로 볼 수 있음
