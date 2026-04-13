# Learn Markdown

## Markdown Cheatsheet

* [Language Identifiers](#language-identifiers)


## Language Identifiers
> 
    To enable syntax highlighting for different formats in Markdown, you simply add the language identifier immediately after the first set of triple backticks in a fenced code 
    block. 

Fenced Code Blocks: Wrap your code in triple backticks `(```)` or triple tildes `( ~~~ )` on the lines before and after the code.

**Syntax Highlighting**: You can specify a language (e.g., `python` or `js`) immediately after the opening backticks to enable colour highlighting.

### Common Language Identifiers
Most Markdown renderers (like GitHub, VS Code, and Obsidian) support these common tags:

| Language 	    | Identifier(s)
|---            |--- 
|JavaScript     | `javascript` or `js`
|HTML	        | `html`
| Bash / Shell	| `bash`, `sh`, or `shell`
|CSS	        | `css`
|Python	        | `python` or `py`
|JSON	        | `json`
|YAML	        | `yaml` or `yml`
|Markdown	    | `markdown` or `md`

### Examples of Fenced Code Blocks

JavaScript
```
    ```javascript
        console.log("Hello World");
    ```
```

HTML

~~~
```html
    <p>This is a paragraph.</p>
```
~~~

Bash
~~~
```bash
echo "Current user is: $USER"
```
~~~


**Important Tips**

- **Case Sensitivity**: Most renderers are case-insensitive, but lowercase is the standard convention.

- **Supported Languages**: The specific list of supported languages depends on the tool you are using; for instance, GitHub uses the Linguist library, which supports hundreds of formats.

- **Plain Text**: If you want a code block without any highlighting (just a grey box), use ```text or leave the space after the backticks blank. 