<div align="center">
    <img src="https://user-images.githubusercontent.com/10446161/195706555-c493edc6-5d3c-4f6b-b649-0cb42a9da0fe.svg" alt="logo" width="80" height="auto">
	<h1 align="center">WordPress Base</h1>
	<p align="center">
		Starter theme based on _s
	</p>
</div>

## Built With

-   [WordPress](https://wordpress.org/)
-   [Vite](https://vitejs.dev/)
-   [Sass](https://sass-lang.com/)

## Linter,Formatter

-   [ESLint](https://eslint.org/)
-   [Stylelint](https://stylelint.io/)
-   [Prettier](https://prettier.io/)

## dev,build

### dev

```php
// functions.php
define( 'IS_VITE_DEVELOPMENT', true );
```

```shell
$ vite
```

### build

```php
// functions.php
define( 'IS_VITE_DEVELOPMENT', false );
```

```shell
$ vite build
```
