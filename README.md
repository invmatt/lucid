<img src="http://i.imgur.com/oWAt9MZ.png" alt="Lucid for SASS" />

A SASS CSS Framework without any additional styling

<h5>Compiling the SASS/SCSS</h5>
<pre>
# Example (project styles directory)
sass --watch lucid/lucid.scss:css/[desired-css-file-name].css
</pre>

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
    | defaults.scss
    | grid.scss
    | overrides.scss
    
  | mixins
    | addons.scss
    | core.scss
    | functions.scss
    | helpers.scss
</pre>
