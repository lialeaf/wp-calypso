Security Icon
=============

This is a component that is used for security icons to indicate state in Jetpack Scan.

## Usage

```es6
import SecurityIcon from 'landing/jetpack-cloud/components/security-icon';

const SecurityIconExample = () => (
	<div>
		<SecurityIcon icon="okay">
		<h1>Your site looks great!</h1>
	</div>
);
```

## Props

* `icon`: ( string ) Can be `okay` or `error`. Defaults to `okay`.
* `className`: ( string ) Additional classes to add to `img` tag.
