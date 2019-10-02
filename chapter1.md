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

`@instructions`
1. Generate a list named ```integers``` that consists of numbers ranging from 1 to 1,000 (i.e., [1,2,...,999,1000]).
2. Calculate the sum of the last 500 list elements and print the sum to the console.

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}
print('This is an exam, you gotta figure out the solution by yourself')
integers = []
```

`@sct`
```{python}
solution = "import numpy as np; integers = [i for i in range(1,1001)]; print(np.sum(integers[-500:]))"

#Ex().has_equal_value(extra_env = {'integers': integers})

Ex().check_object('integers').has_equal_value(incorrect_msg = 'asdf', override = "integers = [i for i in range(1,1001)]")
#Ex().has_output(str(np.sum(integers[-500:])))
success_msg("Correct, you've earned 5 points!")
```
