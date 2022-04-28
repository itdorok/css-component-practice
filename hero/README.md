# hero

```
combining images, colours, text, links and calls to action.

 Used for splashy home page banners
```

<img src="heroPage.png" width="50%">

<br>

## 💡 background-image

```css
header {
  background-image: url();
  background-size: cover;
}
```

```
url로 이미지를 삽입하고
size property로 조절한다
```

### + gradient 적용

```
이미지 위에 텍스트를 놓으면 명암 대비가
잘 이루어 지지 않음

linear-gradient(rgba())
속성을 이용해 이미지 명암을 죽일 수 있음
```

```css
header {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.4)),
    url();
}
```

    중첩해서 쓰면 앞에서부터 z-index가 더  작음

    여러개의 이미지를 겹칠 수 있음

<br>

## 💡 empty div

<img src="emptyDiv.png" width="50%">

```css
.outer-div {
  width: 1200px;
}

.inner-div {
  width: 50%;
}
```

inner-div의 크기는 parent element 크기의 반을 차지하게 됨
