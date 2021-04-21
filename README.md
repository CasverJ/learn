`SCSS`
* export导出变量
  ```scss
  // scss
  $color: red;
  :export {
    color: $color;
  }
  ```
  ```js
  // js
  import color from theme.scss
  console.log(color)  // red
  ```

`MD`
* 代码块```后添加文件后缀