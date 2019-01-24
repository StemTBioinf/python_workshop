# Python Foundation Workshop
### Part of Bioinformatics initiative of Research School at Stem Cell Centre, Lund

#### Here you will find all the course material that will be used in the workshop during Feb 5-6, 2019

#### Requirements
This workshop expects that you have already completed an introductory course to Python before. A suggested resource is Codecademy's free Python2 course.

You will need **Python 3.7** installed on your laptop. Best way to install Python is through Anaconda. Just download their installer from the following link and intall it like a regular program.
https://www.anaconda.com/download/

FAQs

What is Anaconda? 

On daily basis, you will likely use much more than just the core Python language. Tens of thousands of software developers across the world have created a large number of very useful packages that you could use through Python languages. However, you need to install them separately as they are not part of the core language. Many times developer develop a package in other languages and make them useable through Python. When you install those packages, your computer should have the right tools to read those other languages as well. This can become a huge hassle because most packages are created on top of other packages. To ease this daunting task of installing Python packages, a metapackage called Anaconda was developed. Anaconda contains the core Python language as well as a lot of commonly used packages that you will need. Did not get enough of Anaconda, read further here: https://stackoverflow.com/questions/42096280/how-is-anaconda-related-to-python

What if the package I need is not present in Anaconda?

No problem, **pip** or **conda** will rescue you. These are two command-line line utilities that allow you to install any package you want in a single line. You run it directly from your terminal if your laptop runs Linux or MacOS. In the case of Windows, you need to launch the 'Anaconda prompt' utility and then run all you Python stuff there. pip and conda are automatically installed when you install Anaconda. Now you might be wondering, where does pip fetch the packages from? Well, pip fetches them from PyPI (https://pypi.org/), a repository of almost all Python packages. It is actually quite easy to package your own Python code and put it on PyPi for others (or future yourself) to use.

Why are there two Python versions? Is Python 3.7 just a newer Python?

Python has two parallel branches, the 2x and the 3x branch. In short 2x branch will be 'dead' soon and almost everybody will be using the 3x branch. Python 3x is getting better, most packages have updated their code to be Python 3 compatible. Well, if you really want Python 2 because of some reason, a good suggestion would be to install it in a 'conda environment'. More on that here: https://conda.io/docs/user-guide/tasks/manage-environments.html. This will allow you to have as many Python 3 and/or Python 2 versions you like. It is very useful to use environments and is highly recommended.

What is the difference between iPython and Python?

iPython basically means interactive Python. How is it interactive? Well, the process of writing code has been like this: you write your code in notepad and you save the file, then you move over to your terminal and launch the file by writing 'python abc.py'. Well, that's quite useful when you know exactly what you want to achieve. However, after the file is launched and it finishes its job you lose all the variables and everything else that was not explicitly saved. Well, this can be an issue, for example, when you are reading data from a file and exploring it, you may want to have the data 'floating around'. This is where iPython comes in, it provides you with an environment where every variable that you create is stored until you close or refresh the session manually. iPython is one of the foundations of the modern data science revolution.

How is iPython related to Jupyter?
