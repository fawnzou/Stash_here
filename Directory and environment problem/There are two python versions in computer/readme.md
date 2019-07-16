**Promblems:** 

**When I input code "!python bacon_counter.py input.txt" in Jupyter notebook, it didn't successful.**

<img src="Problem in Jupyter notebook.png">

**But if I run code "python bacon_counter.py input.txt" in anaconda prompt, it get through.**

<img src="different result in conda terminal.png">

**Why did this happen?**

**We analyze in anaconda prompt using code "where python", we find there are two python files in my computer.**
  C:\Users\fawnz\anaconda\Anaconda3\python.exe\
  C:\Users\fawnz\AppData\Local\Continuum\anaconda3\python.exe
  
  The first one is the place I install python, the second one is the place where python is installed I didn't notice. 
  Anaconda prompt ran the first one, but Jupyter notebook ran the second one which is in a environment lack of other module also required by this notebook, so we didn't get through.
  
<img src="conda code 1.png">

<img src="conda code 2.png">

**Solve the problem\**

I change the directory of python, let Jupyter notebook run python version in the first path, this time it worked.
Use "Which Python" check the python path

<img src="Solve problem on Jupyter notebook.png">
