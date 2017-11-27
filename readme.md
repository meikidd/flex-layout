# Flex Layout

## Sticky Footer Layout

[demo link](./demos/1.html)

![demo 1 - Sticky Footer](./assets/images/demo1.png)

```html
<body>
  <header>HEADER</header>
  <article>CONTENT</article>
  <footer>FOOTER</footer>
</body>
```

```css
body {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}
article {
  flex: auto;
}
```

## Fixed-Width Side Bar

[demo link](./demos/2.html)

![demo 1 - Sticky Footer](./assets/images/demo2.png)

```html
<body>
  <header>HEADER</header>
  <div class="content">
    <aside>ASIDE</aside>
    <article>CONTENT</article>
  </div>
  <footer>FOOTER</footer>
</body>
```

```css
body {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}
.content {
  flex: auto;
  display: flex;
}
.content article {
  flex: auto;
}
```

## 左右布局

[demo link](./demos/3.html)

![demo 1 - Sticky Footer](./assets/images/demo3.png)

```html
<body>
  <aside>ASIDE</aside>
  <div class="content">
    <header>HEADER</header>
    <article>CONTENT</article>
    <footer>FOOTER</footer>
  </div>
</body>
```

```css
body {
  min-height: 100vh;
  display: flex;
}
aside {
  flex: none;
}
.content {
  flex: auto;
  display: flex;
  flex-direction: column;
}
.content article {
  flex: auto;
}
```
