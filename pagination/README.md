# pagination

```
페이지가 여러장으로 넘어갈 때
숫자에 해당하는 페이지로 넘어갈 수 있도록 하는 하단부에 버튼
```

<img src="https://user-images.githubusercontent.com/82014471/165665698-8e7116ef-7ced-41a6-99b5-c34398242082.gif" width="50%">

---

## 💡 container 가운데 정렬

### flex

```css
body {
  display: flex;
  justify-content: center;
}
```

### margin

```css
.container {
  margin: 0, auto;
}
```

---

## 💡 button styling

```css
button {
  background: none;
  width: 24px;
  height: 24px;
  color: #fff;
  cursor: pointer;
}
```

button 안에 다른 element가 있는 경우
flex를 이용해서 가운데 정렬

```css
button {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

## + selector specificity

[참조자료 👀](https://developer.mozilla.org/ko/docs/Web/CSS/Specificity)

```
selector의 우선순위에 따라 적용 됨

버튼 내부의 svg icon 색이 바뀌지 않는 문제가 발생
```

```css
.page-link.page-link--current {
  background-color: #087f5b;
  color: #fff;
}
```

> class selector을 붙여서 우선순위를 높여주면 적용됨
