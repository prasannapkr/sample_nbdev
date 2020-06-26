# Project name here
> Summary description here.


This file will become your README and also the index of your documentation.

## Install

`pip install nbdev_template`

## How to use

Fill me in please! Don't forget code examples:

```python
test_eq(say_hello("Jeremy"), "Hello Jeremy!")
```

    Hello Jeremy!



    ---------------------------------------------------------------------------

    AssertionError                            Traceback (most recent call last)

    <ipython-input-47-91ac42a35f51> in <module>
    ----> 1 test_eq(say_hello("Jeremy"), "Hello Jeremy!")
    

    /usr/local/lib/python3.7/site-packages/fastcore/test.py in test_eq(a, b)
         30 def test_eq(a,b):
         31     "`test` that `a==b`"
    ---> 32     test(a,b,equals, '==')
         33 
         34 # Cell


    /usr/local/lib/python3.7/site-packages/fastcore/test.py in test(a, b, cmp, cname)
         20     "`assert` that `cmp(a,b)`; display inputs and `cname or cmp.__name__` if it fails"
         21     if cname is None: cname=cmp.__name__
    ---> 22     assert cmp(a,b),f"{cname}:\n{a}\n{b}"
         23 
         24 # Cell


    AssertionError: ==:
    None
    Hello Jeremy!

