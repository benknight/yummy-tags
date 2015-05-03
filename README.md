# Yummy Tags

A custom Polymer element for adding tags from a list of values.

# Usage

Import it:

	<link rel="import" href="yummy-tags.html">

Define your data:

	<script>
		window.codeLangs = ['ActionScript', 'C', 'C#', 'C++', 'Clojure', '...'];
	</script>

Use it:

	<yummy-tags globalValues="codeLangs"></yummy>

# Features

* Autocomplete
* Behaves like an input field with support for backspace, arrow keys, enter, etc.  Similar to (Select2)[https://select2.github.io/examples.html].