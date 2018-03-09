#Python specific rules
###1. All submitted code __MUST__ comply to PEP8 standards and convensions.
 - Exception: maximum line length extended to `100` (read: one Hundred) characters.
 
###2. Logic checks and their actions should not be on the same line.
the below example is **not** legal.
```python
if foo == 12: bar()
```
Rather, it should be written as 
```python
if foo == 12:
    bar()
```
 - Exception: setting a variable in-line following the below example, is legal:
 ```python
foo = 12 if bar == 42 else None
```
 
###3. All submitted code must be documented effectively.
 - you may find a lot of legacy code in some of our repositories that are 
 undocumented, these are not examples to follow.
 
 
 ###4. Techrats reserve the right to request changes to opened pull requests.
 - We reserve the right to reject Pull requests that do not effect required changes.
 