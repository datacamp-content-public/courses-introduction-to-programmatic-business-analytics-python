---
title: 'Python exam tasks'
description: '5 points'
---

## Task 1, 5 points

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

This "exercise" is part of the exam for the course Introduction to programmatic business analytics given in Lappeenranta-Lahti University of Technology.

**IF YOU CLICK "Show Answer" IN A TASK, YOU WILL GET ZERO (0) POINTS FROM THE TASK!**

`@instructions`
1. Generate a list named "[integers]()" that consists of numbers ranging from 1 to 10,000,000 (i.e., [1,2,...,9999999,10000000]).
2. Calculate the sum of the first 5,000,000 list elements and print the sum to the console.

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}
import numpy as np
integers = [i for i in range(1,10000001)]
print(np.sum(integers[:5000000]))
```

`@sct`
```{python}
Ex().check_object("integers").has_equal_value()
Ex().has_output(1647668640)
success_msg("Correct, you've earned 5 points!")
```
