# MkDocs template

[![CI Status](https://github.com/Bit-Part-Young/mkdocs-template/actions/workflows/mkdocs-deploy.yml/badge.svg)](https://github.com/Bit-Part-Young/template/actions/workflows/mkdocs-deploy.yml)

Mkdocs 模板。

---

## 使用

### LaTeX 公式

内联公式：使用 `$...$`，如 $f(x) = x^2$ 。

行间公式：使用 `$$...$$`，如

```markdown
$$
F(x) = \int^a_b \frac{1}{2}x^4
$$
```

$$
F(x) = \int^a_b \frac{1}{2}x^4
$$

---

### 不同代码块的互相切换

=== "Python"

    ```python
    print("Hello, Python!")
    ```

=== "JavaScript"

    ```javascript
    console.log("Hello, JavaScript!");
    ```

---

### mkdocs Admonitions

!!! abstract
    这里是 abstract

!!! note
    这里是 note

!!! tip
    这里是 tip

!!! info
    这里是 info

!!! success
    这里是 success

!!! question
    这里是 question

!!! warning
    这里是 warning

!!! danger
    这里是 danger

!!! failure
    这里是 failure

!!! bug
    这里是 bug

!!! example
    这里是 example

!!! quote
    这里是 quote

---

toggle admonitions

??? note
    这里是 toggle note

---

expanded toggle admonitions

???+ note
    这里是 expanded toggle note

---

inline admonitions

这里是 inline note
!!! note inline end
    这里是 inline note
