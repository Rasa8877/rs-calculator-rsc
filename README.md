# 📐 RSC (Really Simple Calculator)

RSC is the simplest calculator library in Python!  
It lets you evaluate complex math expressions **safely**, with support for variables and all basic math operators.

Version: **0.3.2** – *Improved API with setv() and calc()*

---

## 🔧 Installation

```bash
pip install rsc
```
or

```bash
pip install rsc==0.3.2
```

---

## 🚀 Quick Start

```python
import rsc

print(rsc.calc("2 + 3 * (4 - 1)"))  # ➜ 11
print(rsc.calc("5 ^ 2 + 10"))       # ➜ 35
```

You can also assign variables:

```python
rsc.setv("a", 10)
rsc.setv("b", 20)
rsc.setv("c", 10)

print(rsc.calc("a + b - c"))     # ➜ 20
print(rsc.calc("(a + b) - c"))   # ➜ 20
```

---

## ✅ Supported Features

* Operators: `+`, `-`, `*`, `x`, `/`, `//`, `%`, `**`, `^`
* Parentheses for grouping
* Variables using `setv(name, value)`
* Safe evaluation (using `asteval`)
* Simple API

---

## 📘 Usage Reference

```python
rsc.calc(expression: str) -> float | str
```

```python
rsc.setv(name: str, value: float | int)
```

```python
rsc.show_help()  # Prints usage instructions
```

---

## 🌐 Links

* [GitHub Repo](https://github.com/Rasa8877/rs-calculator-rsc)
* Contact: [letperhut@gmail.com](mailto:letperhut@gmail.com)

---

## 🧠 Author

Made with ❤️ by Rasa8877
RSC — the simplest calculator library in Python!
