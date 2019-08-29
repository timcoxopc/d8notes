## Twig 

### Twig Debug

```yml
Twig Debug
parameters:
  twig.config:
    debug: true
```

### Links

To link to a url from twig: a href="content.field_link[0]['#url']"

#### Link type

```twig
content.field_link['#items'][0].uri 
content.field_link['#items'][0].title
```

### Debugging

#### Show all variables

```twig
{{ dump() }} 
```
#### Show details of variable

```twig
{{ dump(variable) }} - 
```
#### ?

```twig
{{ items|safe_join(", ") }} 
```
