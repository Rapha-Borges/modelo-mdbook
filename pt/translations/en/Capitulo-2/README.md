# TEMPORARILY UNAVAILABLE

# Using a processor to add Material Design admonishments.

##  Example:

````
``` + admonish + {chosen_format}

{TEXT TO BE DISPLAYED}

```
````
&nbsp;

---

## Reference

For other examples you can consult the official documentation [CLICK HERE](https://tommilligan.github.io/mdbook-admonish/reference.html)

&nbsp;

---

## Info

```admonish info
A beautifully styled message.
```

````
```admonish info
{TEXT TO BE DISPLAYED}
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

You can use markdown and HTML to customize

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

## Bug alert

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

You can also customize with a CSS file by adding class names

````
```admonish note class="custom-0 custom-1"
Styled with my custom CSS class.
```
````

```admonish note class="custom-0 custom-1"
Styled with my custom CSS class.
```

Which will generate something like this in the HTML, where you can apply the CSS:

````
<div class="admonition note custom-0 custom-1"
    ...
</div>
````
&nbsp;

---

## Collapsible


````
```admonish title="{CUSTOM TITLE}" collapsible=true
{TEXT TO BE DISPLAYED}
```
````

```admonish title="{CUSTOM TITLE}" collapsible=true
{TEXT TO BE DISPLAYED}
```
&nbsp;

---

## Invalid blocks

If there is an error in rendering it will be displayed like this

```admonish title="\j"
This block will error
```