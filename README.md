## 🔅 Functions

### 🔅 HTML Tags Functions

+-----------------+---------+-----+------+-----+------+-----+
| Functions tag's | content | tag | clas | idd | href | src |
+-----------------+---------+-----+------+-----+------+-----+
| tag             | ✅       | ✅   | ✅    | ✅   | ✅    | ✅   |
+-----------------+---------+-----+------+-----+------+-----+
| specialTagOpen  | ✅       | ✅   | ✅    | ✅   | ✅    | ✅   |
+-----------------+---------+-----+------+-----+------+-----+
| specialTagClose | ❌       | ✅   | ❌    | ❌   | ❌    | ❌   |
+-----------------+---------+-----+------+-----+------+-----+


### 🔅 HTML List Functions
* liOpen(_tipe_) -> _tipe_ == UL or OL list
* liElement(_contentli_) -> _contentli_ == Content of li
* liClose(_tipe_)


### 🔅 Syntax Functions
* closeHead (necessary)
* closeBody (necessary)
* linkCss 

### 🚀 Example
```python
from . import html

page = html()

page.tag("Soy una etiqueta directa desde Pytml 2.0v","h1")

```