## Twig Debug
```yml
Twig Debug
parameters:
  twig.config:
    debug: true
```

## Links
To link to a url from twig: a href="content.field_link[0]['#url']"

### Link type
```twig
content.field_link['#items'][0].uri 
content.field_link['#items'][0].title
```

## Debugging
{{ dump() }} - Show all variables
{{ dump(variable) }} - Show details of variable
{{ items|safe_join(", ") }} ?
