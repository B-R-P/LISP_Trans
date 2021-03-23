# LISP_Trans
Customize syntax of lisp with [LangTrans](https://github.com/B-R-P/LangTrans)

source.yaml - Syntax Representation(Customized Language)<br>
              (Regular Expression for tokens)<br>
target.yaml - Pattern Representation(Orginal Language)<br>
              (Template of orginal language with tokens)
## Example
### Customized Syntax

```python
func printhis(s):
	format(t,s)
printhis("Customized!")
```
### Original Syntax

```lisp
(defun printhis (s)
	(format t s)
)
(printhis "Customized!")
```

## Usages

```console
py langtrans.py <source file> <target file> source target
```
