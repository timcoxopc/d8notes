## Attaching a library in a preprocess function
You can attach a library in a preprocess function using the special key '#attached':

```twig
function yourmodule_preprocess_maintenance_page(&$variables) {
  $variables['#attached']['library'][] =  'your_module/library_name';
}
```

## Attaching a library in a twig template
You can also attach a library in a twig template by using the attach_library() twig function. So in any *.html.twig:

```twig
{{ attach_library('your_module/library_name') }}
<div>Some markup {{ message }}</div>
```

## drupal.org
[Notes](https://www.drupal.org/docs/8/creating-custom-modules/adding-stylesheets-css-and-javascript-js-to-a-drupal-8-module)
