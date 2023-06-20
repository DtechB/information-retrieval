# Information retrieval

### Install all dependencies first and run main runner

```
py venv venv
```

```python
./venv/Scripts/activate # Windows cmd.exe variant if using Python 3.7.2 or later.
```

```
py -m pip install requirements.txt
```

---

## 👉 IR_T1_practical

### code1

- data: docs
- run: main.py
- input: query

```
py main.py
```

### code2

- data: docs, index
- run: main.py
- input: query
- test: text.py

```
py main.py
```

---

## 👉 IR_T2_practical

- data: docs
- run: main.py
- input: query

```
py main.py
```

---

## 👉 IR_T3_practical

- data: docs, lang_docs
- run: crawler.py, searcher.py
- input: site_name, query

### crawler extract docs and lang_docs (python, java, javascript) data folder as json

```
py crawler.py
```

### searcher parse json docs, index and make query ranking

```
py searcher.py
```

## ✅ Lincence

GNU GENERAL PUBLIC LICENSE Version 3

Copyright (C) 2007 Free Software Foundation, Inc. <https://fsf.org/>
Everyone is permitted to copy and distribute verbatim copies
of this license document, but changing it is not allowed.

## 👉 Contributors

<table> 
    <tr>
        <td align="center"><a href="https://github.com/DtechB"><img
                src="https://avatars.githubusercontent.com/u/86948741?v=4"  width="100px;"  height="100px;"
                alt="danial"/><br/><sub><b>Danial</b></sub></a><br/><a
                 title="Code">💻</a></td>
        <td align="center"><a href="https://github.com/javadKefayati"><img
                src="https://avatars.githubusercontent.com/u/78617055?v=4"  width="100px;"  height="100px;"
                alt="javad"/><br/><sub><b>Javad</b></sub></a><br/><a
                 title="Code">💻</a></td>
    </tr>
</table>
