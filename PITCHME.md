## Python Visualization Workshop


Northwestern IT Research Computing Services  
July 9, 2018  

Jim Griffin

---
### Outline

* Intro  
  * plot anatomy
  * types of plots
  * matplotlib organization  
* Simple examples  
* Styling plot elements  
* Plotting with **Pandas** dataframes  
* Pretty plots (**Seaborn**, colorpalettes)  

---
### Object Oriented Interface

* Matplotlib plots have two primary classes - Figures and Axes
* Preferred plotting approach is:
  1. Create figure and axis instances w/ plt.subplots
  2. Use figure and axis methods to modify visual elements

---

### Basic matplotlib syntax
```python
import matplotlib.pyplot as plt

fig, ax = plt.subplots()
ax.plot(x,y, ***kwargs)
fig.savefig('path/to/file.png')
```
@[1](Matplotlib import statement)
@[3](Create figure and axis objects)
@[3](like this?)
@[4](Most plotting functions exist as Axes methods  
multiline??  
sup?
  )
@[5](Figure methods control axes layout and saving)

![Anatomy1](Images/plotparts.png)


---?image=Images/plotparts.png&size=auto 50%
#### Parts of a python plot:

---
* write stuff
<img src="Images/plotparts.png" style="max-height: 300px;"/>

---


```

```
