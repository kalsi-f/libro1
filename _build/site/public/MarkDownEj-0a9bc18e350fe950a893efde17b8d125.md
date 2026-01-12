# Ejemplo de un MarkDown

Esto es *cursiva*, **negrita**, `inline code`, y [un link](https://Wikipedia.org).

```python
print("""
Esto es un bloque de codigo
""")
```
> Esto es una cita

Aqui aparece un gato

:::{figure} ./images/gato.jpeg
:name: gato
¡Esta es la foto de un gato!
:::

::::{tab-set}

:::{tab-item} Markup
:sync: markup

Aquí puedes ver el código fuente utilizado para esta sección:

\`\`\`markdown
# Ejemplo de un MarkDown

Esto es *cursiva*, **negrita**, `inline code`, y [un link](https://Wikipedia.org).

\`\`\`python
print("""
Esto es un bloque de codigo
""")
\`\`\`

> Esto es una cita

Aqui aparece un gato

:::{figure} ./images/gato.jpeg
:name: gato
¡Esta es la foto de un gato!
:::
\`\`\`
:::

:::{tab-item} Result
:sync: result

# Ejemplo de un MarkDown

Esto es *cursiva*, **negrita**, `inline code`, y [un link](https://Wikipedia.org).

```python
print("""
Esto es un bloque de codigo
""")