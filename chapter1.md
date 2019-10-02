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

This "exercise" is part of the exam for the course Introduction to Programmatic Business Analytics given in Lappeenranta-Lahti University of Technology.

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
# This is an exam, you gotta figure out the solution by yourself
integers = []
```

`@sct`
```{python}
import numpy as np
integers = [i for i in range(1,1001)]

Ex().check_object('integers').has_equal_value(override = integers, incorrect_msg = 'Incorrect, try again.')
Ex().has_output(str(np.sum(integers[-500:])))

success_msg("Correct, you've earned 5 points!")
```

---

## Task 2, 5 points

```yaml
type: NormalExercise
key: 268299d90c
xp: 100
```

This "exercise" is part of the exam for the course Introduction to Programmatic Business Analytics given in Lappeenranta-Lahti University of Technology.

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}
# This is an exam, you gotta figure out the solution by yourself
integers = ['asdf']
```

`@sct`
```{python}
import numpy as np
integers = [i for i in range(1,1001)]

Ex().check_object('integers').has_equal_value(override = integers, incorrect_msg = 'Incorrect, try again.')
Ex().has_output(str(np.sum(integers[-500:])))

success_msg("Correct, you've earned 5 points!")
```
