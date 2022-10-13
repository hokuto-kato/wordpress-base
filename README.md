<div align="center">
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
