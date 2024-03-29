# MkDocs template

[![CI Status](https://github.com/Bit-Part-Young/mkdocs-template/actions/workflows/mkdocs-deploy.yml/badge.svg)](https://github.com/Bit-Part-Young/mkdocs-template/actions/workflows/mkdocs-deploy.yml)

Mkdocs 模板。

**Features**:

- 已配置 GitHub Actions，可自动部署到 GitHub Pages
- LaTeX 公式渲染

---

效果图：

![mkdocs-effect](./assets/mkdocs-effect.png)

---

## 搭建

- 搭建 MkDocs 环境

```bash
# 方式 1
conda create -n mkdocs python=3.11

conda activate mkdocs
pip install -r requirements.txt

# 方式 2
./setup.sh

source venv/bin/activate
```

- 自定义修改 `mkdocs.yml` 配置文件相关内容

- 本地预览；手动部署到 GitHub Pages

```bash
#  本地预览
mkdocs serve

# 部署到 GitHub Pages
mkdocs gh-deploy
```

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
