
### Questions
* git merge lab - git push origin master threw an error
* git log --graph

### Objectives
YWBAT
* define git
* perform branching and merges in git (remotely)
* compare and contrast git commit to git push

### Outline
* Git stuff 
* Pep-8


```python
import pandas as pd
import numpy as np

import matplotlib.pyplot as plt
```

# Pep 8 Standards (Because we aren't newbs)


```python
# Fix this coding cell
x = 3
y = 5
x + y
```




    8




```python
# Now this one 
# camel case thisIsCamelCase
# this_is_snake_case
# variables/methods/almost everything -> lowercase
# classes -> uppercase

well_this_is_cool = lambda x: 2*x

well_this_is_cool(8)
```




    16




```python
## Now also fix this one...
whats_in_name = 2
montague = 1
capulet = 0

print(montague + capulet == whats_in_name)
```

    False



```python
#time to write functions!...not really, we're pep-8ing some stuff

def my_function(a, b, c, d):
    return a*b + c - d 


print(my_function(3, 4, 2, 9))
```

    5


### Assessment

What is the purpose of version control?
* keep a working file (so it doesn't break)
* merge changes after testing
* maintains the health of codebase


What is pep-8?
* formatting guide for python


Should we use pep-8? I'm kinda curious what y'all think.
* should code be dependent on pep-8 standards?
* standards like pep-8 make sense
* lines shouldn't be longer than 79 characters
