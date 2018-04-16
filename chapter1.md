---
title: Insert the chapter title here
description: >-
  Insert the chapter description here


---
## A really bad movie 2- 2

```yaml
type: MultipleChoiceExercise
lang: python
xp: 50
skills: 1
key: eedd7aa181
```

Have a look at the plot that showed up in the viewer to the right. Which type of movies have the worst rating assigned to them?

`@instructions`
- Long movies, clearly
- Short movies, clearly
- Long movies, but the correlation seems weak
- Short movies, but the correlation seems weak

`@hint`
Have a look at the plot. Do you see a trend in the dots?

`@pre_exercise_code`
```{python}
# The pre exercise code runs code to initialize the user's workspace.
# You can use it to load packages, initialize datasets and draw a plot in the viewer

import pandas as pd
import matplotlib.pyplot as plt

movies = pd.read_csv("http://s3.amazonaws.com/assets.datacamp.com/course/introduction_to_r/movies.csv")

plt.scatter(movies.runtime, movies.rating)
plt.show()
```


`@sct`
```{python}
# SCT written with pythonwhat: https://github.com/datacamp/pythonwhat/wiki

msg_bad = "That is not correct!"
msg_success = "Exactly! The correlation is very weak though."
test_mc(4, [msg_bad, msg_bad, msg_bad, msg_success])
```





---
## Insert exercise title here

```yaml
type: MultipleChoiceExercise

xp: 

key: 8b9da9f3a4
```

dasdas

`@instructions`
- first
- second
- third

`@hint`
this is a hint

`@pre_exercise_code`
```{}
# ec dasmdas
```


`@sct`
```{}
# sct
```





---
## Insert exercise title here

```yaml
type: PureMultipleChoiceExercise

xp: 

key: 86fb1ec231
```

pure mce


`@hint`
hint





`@possible_answers`
- one
- two
- [three]

`@feedbacks`
- no
- no
- yes



