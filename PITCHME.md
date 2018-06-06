### Python Visualization Workshop


Northwestern IT Research Computing Services  
July 9, 2018  

Jim Griffin

---
#### Outline

* Intro Slides
  * matplotlib organization
  * plot anatomy
  * types of plots  
* Simple examples
* Styling plot elements  
* Plotting with **Pandas** dataframes  
* Pretty plots (**Seaborn**, colorpalettes)  

---

#### Matplotlib.pyplot Classes
  * Figure  
  * Axes  
<img src="Images/plotparts.png" style="max-height: 400px;"/>

---

##### Preferred (Object-oriented) approach:

  1. Create figure and axis objects
  2. Use figure and axis methods to modify visual elements

---

##### Example matplotlib syntax

```python
  import matplotlib.pyplot as plt

  fig, ax = plt.subplots()

  ax.plot(x,y, ***kwargs)
  ax.set_xlabel('x label')

  fig.savefig('path/to/file.png')
```
@[1](Matplotlib import statement)
@[3](Create figure and axis objects)
@[5](Axes objects have methods for most common plot types</br>(i.e. line, scatter, bar, pie))
@[6](Axes methods also control labels, titles, limits, tick properties)
@[8](Figure methods control axes layout and saving)
---
