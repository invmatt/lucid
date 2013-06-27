<img src="http://i.imgur.com/oWAt9MZ.png" alt="Lucid for SASS" />

A SASS Framework without any additional styling. Lucid features a responsive grid, useful mixins and a collection of base styles for buttons, forms, menus and tables.

<h5>Download the latest version</h5>
<h6>Version 0.0.1 - <a href="https://github.com/invmatt/lucid/archive/master.zip" alt="Download Lucid">Download</a></h6>
<p>Note: Lucid is incomplete and the file structure, names and contents will change.</p>

<h5>Compiling the SASS/SCSS</h5>
<pre>
# Example (project styles directory)
sass --watch lucid/lucid.scss:css/[desired-css-file-name].css
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
| _shame.scss

  | Additional
    | _buttons.scss
    | _core.scss
    | _forms.scss
    | _menus.scss
    | _tables.scss
    
  | base
    | _containers.scss
	| _custom.scss
    | _defaults.scss
    | _grid.scss
    | _overrides.scss
    
  | mixins
    | _addons.scss
    | _core.scss
    | _functions.scss
    | _helpers.scss
</pre>