# hero

```
combining images, colours, text, links and calls to action.

 Used for splashy home page banners
```

<img src="heroPage.png" width="50%">

<br>

## ๐ก background-image

```css
header {
  background-image: url();
  background-size: cover;
}
```

```
url๋ก ์ด๋ฏธ์ง๋ฅผ ์ฝ์ํ๊ณ 
size property๋ก ์กฐ์ ํ๋ค
```

### + gradient ์ ์ฉ

```
์ด๋ฏธ์ง ์์ ํ์คํธ๋ฅผ ๋์ผ๋ฉด ๋ช์ ๋๋น๊ฐ
์ ์ด๋ฃจ์ด ์ง์ง ์์

linear-gradient(rgba())
์์ฑ์ ์ด์ฉํด ์ด๋ฏธ์ง ๋ช์์ ์ฃฝ์ผ ์ ์์
```

```css
header {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.4)),
    url();
}
```

    ์ค์ฒฉํด์ ์ฐ๋ฉด ์์์๋ถํฐ z-index๊ฐ ๋  ์์

    ์ฌ๋ฌ๊ฐ์ ์ด๋ฏธ์ง๋ฅผ ๊ฒน์น  ์ ์์

<br>

## ๐ก empty div

<img src="emptyDiv.png" width="50%">

```css
.outer-div {
  width: 1200px;
}

.inner-div {
  width: 50%;
}
```

inner-div์ ํฌ๊ธฐ๋ parent element ํฌ๊ธฐ์ ๋ฐ์ ์ฐจ์งํ๊ฒ ๋จ
