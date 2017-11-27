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