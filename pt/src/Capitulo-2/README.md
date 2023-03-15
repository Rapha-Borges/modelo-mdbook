# TEMPORARIAMENTE INDISPONÍVEL

# Utilizando um processador para adicionar Material Design admonishments.

##  Exemplo de uso:

````
``` + admonish + {formato_escolhido}

{TEXTO PARA SER EXIBIDO}

```
````
&nbsp;

---

## Referência

Para outros exemplos você pode consultar a documentação oficial [CLICANDO AQUI](https://tommilligan.github.io/mdbook-admonish/reference.html)

&nbsp;

---

## Info

```admonish info
A beautifully styled message.
```

````
```admonish info
{TEXTO PARA SER EXIBIDO}
```

````
&nbsp;

---

## Example

```admonish example
My example is the best!
```

````
```admonish example
My example is the best!
```
````
&nbsp;

---

## Note

```admonish
A plain note.
```

````
```admonish
A plain note.
```
````
&nbsp;

---

## Warning 

````
```admonish warning title="{TITULO CUSTOMIZADO}"
The following steps can lead to irrecoverable data corruption.
```
````


```admonish warning title="{TITULO CUSTOMIZADO}"
The following steps can lead to irrecoverable data corruption.
```
&nbsp;

---

## Success

````
```admonish success title="{TITULO CUSTOMIZADO}"
This will take a while, go and grab a drink of water.
```
````


```admonish success title="{TITULO CUSTOMIZADO}"
This will take a while, go and grab a drink of water.
```
&nbsp;

---

## Markdown/HTML

Você pode utilizar markdown e HTML para customizar

````
```admonish tip title="_Referencing_ and <i>dereferencing</i>"
The opposite of *referencing* by using `&` is *dereferencing*, which is
accomplished with the <span style="color: hotpink">dereference operator</span>, `*`.
```
````


```admonish tip title="_Referencing_ and <i>dereferencing</i>"
The opposite of *referencing* by using `&` is *dereferencing*, which is
accomplished with the <span style="color: hotpink">dereference operator</span>, `*`.
```
&nbsp;

---

## Alerta de bug

````
~~~admonish bug
This syntax won't work in Python 3:
```python
print "Hello, world!"
```
~~~
````

~~~admonish bug
This syntax won't work in Python 3:
```python
print "Hello, world!"
```
~~~
&nbsp;

---

## Custom

Você também customizar com um arquivo CSS adicionando nomes de classes

````
```admonish note class="custom-0 custom-1"
Styled with my custom CSS class.
```
````

```admonish note class="custom-0 custom-1"
Styled with my custom CSS class.
```

Que vai gerar algo assim no HTML, aonde você podera aplicar o CSS:

````
<div class="admonition note custom-0 custom-1"
    ...
</div>
````
&nbsp;

---

## Collapsible


````
```admonish title="{TITULO CUSTOMIZADO}" collapsible=true
{TEXTO PARA SER EXIBIDO}
```
````

```admonish title="{TITULO CUSTOMIZADO}" collapsible=true
{TEXTO PARA SER EXIBIDO}
```
&nbsp;

---

## Invalid blocks

Se ocorrer um erro na renderização será exibido dessa forma

```admonish title="\j"
This block will error
```