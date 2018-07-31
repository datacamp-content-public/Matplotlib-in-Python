---
  title: "Test"
  description: "Test"
---

## Basics of Matplotlib

```yaml
type: NormalExercise 
lang: python
xp: 100 
skills: 2
key: c67c169ecc   
```


One of the key skills within Data Science is being able to visualize data in order to better understand it. One of the main packages for plotting within Python is called Matplotlib.

Before we use any of the methods in python, we need to import the package.
Most coders abbreviate this package to plt and therefore it is good practice to do the same in order for other people to understand your code.
To import Matplotlib we write the following line in python:
import matplotlib.pyplot as plt

matplotlib.pyplot contains command like functions which each make a change to a figure e.g. create figure, create a plot, plot some lines in plotting area, customize plot with labels and legends etc. 
The various states which are called are preserved across function calls i.e.  it keeps track of functions called such as the plotting area, axes etc.

To call all methods we use the syntax plt.method()

The basic steps to creating plots with matplotlib are:              

1. Prepare data 
2.  Plot
3.  Customize plot 
4. Show plot 

_Plotting_
The .plot method of pyplot to plots the respective data points. 
The .plot takes many parameters, but the first two here are 'x' and 'y' coordinates

_Customization_
A few examples will be looked at in future exercises

_Show Plot_
The plt.plot will "draw"  a plot in the background, but  if we want to view the plot, we use the plt.show() method.
This is done once all the specifications of the plot have been run


`@instructions`
X and Y co-ordinates have already been prepared for you as well as matplotlib imported

1. Plot graph of 'x' and 'y'  using the .plot() method
2.  Label the y-axis "random"  by using .ylabel() method
3. Show the plot using the .show method

`@hint`
- Here is the hint for this setup problem. 
- It should get students 50% of the way to the correct answer.
- So don't provide the answer, but don't just reiterate the instructions.
- Typically one hint per instruction is a sensible amount.

`@pre_exercise_code`

```{python}
import matplotlib.pyplot as plt
```

`@sample_code`

```{python}
import matplotlib.pyplot as plt

#Step 1 Prepare Data
x = [1,2,3,4]
y = [10,20,25,30]

#Step 2 Plot Graph


#Step 3 Label y axis 


#Step 4 Show Plot



```

`@solution`

```{python}
import matplotlib.pyplot as plt

#Step 1 Prepare Data
x = [1,2,3,4]
y = [10,20,25,30]

#Step 2 Plot Graph
plt.plot(x,y)

#Step 3 Label y axis 
plt.ylabel("random")

#Step 4 Show Plot
plt.show()


```

`@sct`

```{python}
# Update this to something more informative.
success_msg("Some praise! Then reinforce a learning objective from the exercise.")
```
