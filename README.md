# Tech Rat Code Standards and Guidelines
Here you will find rules we expect all contributing developers to follow, regardless of who they are. Any PR not following these rules will be denied. No exceptions!

# The Rules
### Rule 1: NO SINGLE CHAR LENGTH VARIABLES
### Rule 2: _"Don't be an asshat."_ -DerryBear
### Rule 3: If one exists, read and follow the associated language section for the project you are contributing to
### Rule 4: If one exists, read and follow the CONTRIBUTING.md of the repository you're contributing to.


Our minimum language requirements are listed below, these rules apply unless 
they are **explicitly** overwritten by the project's CONTRIBUTING.md

#Python specific rules
###1: NO SINGLE CHAR LENGTH VARIABLES

###2. All submitted code __MUST__ comply to PEP8 standards and convensions.
 - Exception: maximum line length extended to `100` (read: one Hundred) characters.
 
###3. Logic checks and their actions should not be on the same line.
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
 
###4. All submitted code must be documented effectively.
 - you may find a lot of legacy code in some of our repositories that are 
 undocumented, these are not examples to follow.
 
 ###5. Techrats reserve the right to request changes to opened pull requests.
 - We reserve the right to reject Pull requests that do not effect required changes.
 