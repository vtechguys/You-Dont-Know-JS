# JavaSrcript | DOM
### Add Class
To add class on `DOM` element refered by `element` variable in our code we use `element.classList.add(...classes);`. The function accepts multiple classnames as parameters. These multiple parameters is not supported in *IE 11*.
```js
element.classList.add('class-name');
// Multiple params not supported in IE 11
element.classList.add('class-name-1', 'class-name-2', 'class-name-3');
```
### Remove class
To remove class from `element` we use `element.classList.remove('class-name');`. The function accepts multiple classnames to remove class from classList. Mutiple feature is not supported in *IE11*.
```js
element.classList.remove('class-name');
// Multiple params not supported in IE 11
elements.classList.remove('class-name-1', 'class-name-2');
```
### Toggle class
```js
element.classList.toggle('class-name');
```
### Check if has class
```js
element.classList.contains('class-name');
```
