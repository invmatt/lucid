<img src="http://i.imgur.com/oWAt9MZ.png" alt="Lucid for SASS" />

A SASS Framework without any additional styling. Lucid features a responsive grid, useful mixins and a collection of base styles for buttons, forms, menus and tables.

<h5>Download the latest version</h5>
<a href="https://github.com/invmatt/lucid/archive/master.zip" alt="Download Lucid">Download Lucid</a>

<h5>Compiling the SASS/SCSS</h5>
<pre>
# Example (project styles directory)
sass --watch lucid/lucid.scss/[desired-css-file-name].css
</pre>

<h5>Notes:</h5>
<ul>
<li>Lucid doesn't include a reset</li>
<li>Lucid is bloat free with no unneeded styling</li>
<li>Current version can be found under Base > Defaults</li>
</ul>

<h5>File Structure</h5>
<pre>
| lucid.scss
| shame.scss

  | Additional
    | buttons.scss
    | core.scss
    | forms.scss
    | menus.scss
    | tables.scss
    
  | base
    | containers.scss
	| custom.scss
    | defaults.scss
    | grid.scss
    | overrides.scss
    
  | mixins
    | addons.scss
    | core.scss
    | functions.scss
    | helpers.scss
</pre>

<h5>Updating Lucid</h5>
<p>Replace every file other than custom.scss, shame.scss and overrides.scss.</p>
