# Fundamentals-Assessment

This repository is submitted as partial fullfillment of a H.Dip in Data Analytics in Computing

*G00398250 Katie O'Brien*
<br>
***
This repository has 2 Jupyter notebooks, one for pyplot and another for CAO points comparisons. It also contains a datset folder and an images folder; as well as a .txt file which should not be modified as it contains important configuration files which Binder requires to run correctly. 




## System Requirements 
***


To modify or run the notebooks on a local machine requires the latest version of Python. Anaconda is an easy to use version available at the following  [url](https://www.anaconda.com/) for Windows, Linux and Mac. Alternatively the static and interactive web based versions of the notebooks are available via the links below. 

## Running Jupyter notebooks

To run the notebooks on a local machine following the installation of `python` you should do the following:

1. Open the command line on your machine. I recommend [CMDer](https://cmder.net/) if using Windows, but the native terminal works fine on Linux/Mac.

2. Navigate to the appropriate folder that contains the downloaded notebook either: `pyplot.pynb` or `cao.ipynb`

3. Type "Jupyter lab" and press "Enter"

4. At this point your browser should automatically start, however, if it doesn't you can copy and paste the info outputted in the terminal into the browser you wish to use and this should start the notebook.


<br>

# Pyplot Notebook

This notebook investigates the use of pyplot and demonstrates some interesting plots that can be created by pyplot. It provides a clear and concise overview of the matplotlib.pyplot package; and an in-depth explanation of 3 intersting plots that can be created by the package. 

These plots are interactive so the user should feel free to edit and modify the code as they see fit to explore the differences that changing the variables can create. One particularly interesting variable that could be changed is the number of bins in the "histogram" section towards the end of the project. 

```
x = penguins["Body Mass (g)"]

plt.hist(x,color = "g", alpha = .50, bins = 10)
plt.xlabel ("Body Weight (g's)")
plt.ylabel ("Count")

```

<br>
The user  might also want to subsitute any of the variables from the dataset used in this project. 

<br>



### Static link
The static view for this notebook on nbviewer is available at:
https://nbviewer.jupyter.org/github/kaob1991/fundamentals-assessment/blob/main/pyplot.ipynb 

or by clicking the following image: [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/kaob1991/fundamentals-assessment/blob/main/pyplot.ipynb)


### Interactive link 
The interactive link for this notebook which will open on Binder can be found by clicking the following image/URL:

https://mybinder.org/v2/gh/kaob1991/fundamentals-assessment/HEAD?filepath=pyplot.ipynb 

or  

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kaob1991/fundamentals-assessment/HEAD?filepath=pyplot.ipynb)


<br>



# CAO notebook 

This notebook investigates the 2021, 2020 and 2019 CAO points. The CAO office co-ordinates the offers of 3rd level university places to students in Ireland. 

The datasets are created from `html`, `xlsx` and `pdf`  datatypes and are combined to a single dataset with points for each year where appropriate. 

The data is then investigated and displayed graphically. 

The user should feel free to investigate and modify the plots to display comparisons between the datapoints of your choosing.

### Static link
The static view for this notebook on nbviewer is available at:

URL: https://nbviewer.jupyter.org/github/kaob1991/fundamentals-assessment/blob/main/cao.ipynb


[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/kaob1991/fundamentals-assessment/blob/main/cao.ipynb)



### Interactive link 
The interactive link for this notebook which will open on Binder can be found by clicking the following image/URL:


https://mybinder.org/v2/gh/kaob1991/fundamentals-assessment/HEAD?filepath=cao.ipynb 


 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kaob1991/fundamentals-assessment/HEAD?filepath=cao.ipynb)




## Credits


### Pyplot
I used  the  following resources significantly in the creation of the pyplot notebook: 
- `matplotlib.pyplot` - the documentation can be found below:
https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html

- `seaborn`- further information can be found at the link below:   
https://seaborn.pydata.org/

- `palmerpenguins` was used in the creation of 2 of the plotting examples- this can be found at the following repository: 
 https://github.com/allisonhorst/palmerpenguins


### CAO

I used the following resources significatly in the completion of this notebook:

- `pandas` - which can be found here: https://pandas.pydata.org/

- `matplotlib.pyplot` - the documentation can be found below:
https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html

- `seaborn`- further information can be found at the link below:   
https://seaborn.pydata.org/

- `numpy`- documentation at the following link: https://numpy.org/doc/stable/index.html



All addditional resources used are referenced at the end of each Notebook 


## Contact: 

Any questions/comments feel free to contact the creator on G003980250@gmit.ie




## References 

- https://towardsdatascience.com/generating-a-requirements-file-jupyter-notebook-385f1c315b52