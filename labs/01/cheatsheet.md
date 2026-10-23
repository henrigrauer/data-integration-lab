### paragraphs

**GitHub** · \<p> and \<\p> on each side of a paragraph treat it as such

```markdown
<p> This is a paragraph </p>
```

<p> This is a paragraph </p>


### task lists
**GitHub** · "- [ ]" and "- [x]" before every item

```markdown
-[ ] This is not done
```
- [ ] This is not done
- [x] This is done


### inline and reference-style links
**GitHub** · "[...]" for the name of the link and "(https://...)" after the link for the reference

```markdown
[name of link](this-is-a-link)
```
[name of link](this-is-a-link)


### fenced code blocks · Python
**GitHub** · three backticks plus the language name open the block, three backticks close it
 
````markdown
```python
def greet(name):
    return f"Hello, {name}!"
```
````
 
````python
def greet(name):
    return f"Hello, {name}!"
````


### alerts
**GitHub** · "> [!NOTE]", "[!TIP]", "[!IMPORTANT]", "[!WARNING]" or "[!CAUTION]" in the first line of a blockquote
 
````markdown
> [!TIP]
> This is a tip box
````
 
> [!TIP]
> This is a tip box


### table with aligned columns, a link and a pipe in a cell
**GitHub** · "|" separates columns, ":---" aligns left, ":---:" center, "---:" right · "\|" writes a pipe inside a cell
 
````markdown
| Left | Center | Right |
|:-----|:------:|------:|
| [course repo](https://github.com/breuert/data-integration) | a \| b | 42 |
````
 
| Left | Center | Right |
|:-----|:------:|------:|
| [course repo](https://github.com/breuert/data-integration) | a \| b | 42 |


### collapsed sections
**GitHub** · "\<details>" around the section, "\<summary>" for the visible title, an empty line before the Markdown content
 
````markdown
<details>
<summary>Hint</summary>
 
This text is hidden until you click on **Hint**.
 
</details>
````
 
<details>
<summary>Hint</summary>
This text is hidden until you click on **Hint**.
 
</details>


### footnotes
**GitHub** · "[^1]" in the text, "[^1]: ..." anywhere in the file · the note appears at the bottom of the page
 
````markdown
This sentence has a footnote.[^1]
 
[^1]: This is the footnote.
````
 
This sentence has a footnote.[^1]
 
[^1]: This is the footnote.
