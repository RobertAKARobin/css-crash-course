# Sizing

- Put a "wall" around el that is 5 pixels of solid red

```
.el{
  border:5px solid red;
}
```

- Overlay a "wall" on top of el that is 5 pixels of solid red

```
.el{
  outline:5px solid red;
}
```

- Put 5 pixels of space between el's border and the elements next to it in all directions

```
.el{
  margin:5px;
}
```

- Put...
  - 5 pixels of space between el's top and bottom borders and the elements above and below it
  - 10 pixels between el's left and right borders and the elements to the left and right of it

```
.el{
  margin:5px 10px;
}
```
- Put...
  - 5 pixels of space between el's top border and the bottom edge of the element above it
  - 5 pixels of space between el's right border and the left edge of the element right of it
  - 10 pixels between el's bottom border and the top edge of the element below it
  - 10 pixels between el's left border and the right edge of the element left of it

```
.el{
  margin:5px 5px 10px 10px;
}
```

- Put 5 pixels of space between el's borders and its contents in all directions

```
.el{
  padding:5px;
}
```

- Put...
  - 5 pixels of space between el's top border and the top edge of its contents
  - 5 pixels between el's right border and the right edge of its contents
  - 10 pixels between el's bottom border and the bottom edge of its contents
  - 10 pixels between el's left border and the left edge of its contents

```
.el{
  padding:5px 5px 10px 10px;
}
```

- Make el 50 pixels wide, **plus** a 5-pixel wall on all sides, plus 5 pixels of space between its wall and its content on all sides, for a total width of 70 pixels

```
.el{
  width:50px;
  border:5px solid red;
  padding:5px;
}
```

- Make el a **total** of 50 pixels wide, **including** a 5-pixel wall on all sides **and** 5 pixels of space between its wall and its content on all sides

```
.el{
  width:50px;
  border:5px solid red;
  padding:5px;
  box-sizing:border-box;
}
```

- Make el 10% the width of its container

```
.el{
  width:10%;
}
```

- Make el 10% the width of the browser window

```
.el{
  width:10vw;
}
```

- Make el 10% the height of the browser window

```
.el{
  width:10vh;
}
```

- Make el 1000% the height of its font size

```
.el{
  width:10em;
}
```
