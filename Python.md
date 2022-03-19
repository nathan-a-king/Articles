# Python

## Variables

[Formatted string literals](https://docs.python.org/3/reference/lexical_analysis.html#f-strings) (also called f-strings for short) let you include the value of Python expressions inside a string by prefixing the string with `f` or `F` and writing expressions as `{expression}`.

```py
firstname = "ada"
lastname = "lovelace"
fullname = f"{firstname} {lastname}"
print(f"Hello, {fullname.title()}!")
```