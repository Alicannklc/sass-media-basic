
Key         | Value
----------- | -----------
xs-phone    |320px
phone       | 480px
tablet      | 768px
tablet-md   | 1024px
widescreen  | 1200px
widescreen-x| 1440px
widescreen-xl| 1920px


Basic
```scss
  .row {
  width: 100%;
  height: 60px;
  position: relative;
  transition: all .2s ease-out;
  z-index: 8;
  @include media('>=Key') {
    margin: 0px;
    color: wheat;
  }
}
```
output Css
```css
.row {
  width: 100%;
  height: 60px;
  position: relative;
  transition: all .2s ease-out;
  z-index: 8; }
  @media (min-width: key) {
    .row {
      margin: 0px;
      color: wheat; }
       }
```

Use
```scss
  @include media('>=Key or px')
```


[include-media](https://include-media.com/)
