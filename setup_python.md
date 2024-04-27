# How To Set up Python
These instructions are for how to set up Python coding with Notepad++ on Windows. For other users, there is documentation available elsewhere online.

## Run Python on Notepad++
1. Install [Python](https://www.python.org/downloads) and [Notepad++](https://notepad-plus-plus.org/downloads/).
2. In Notepad++ click run>run.
3. Browse for Python and insert its filepath followed by -i for interactive then \$(FULL\_CURRENT\_PATH). It should look something like:
   
		C:\Programs\Python\python.exe -i $(FULL_CURRENT_PATH)

4. Save to [alt]+[R] as runPython.
	
	
## Install Additional Packages (non-portable)
1. Make sure python is installed to a directory you can access via cmd.
2. Open cmd.
3. Change directory to the folder that contains python.

		>cd C:\Programs\Python
		
4. Make sure pip is installed and up to date.

		>python -m pip install --upgrade pip

5. Install package. (in this example the package is openpyxl)

   		>python -m pip install openpyxl


## Install Additional Packages (portable)
1. Install the package as above using a non-portable version of Python.
2. Copy the folders from the Python\Lib\site-packages from the non-portable version.
3. Paste them to that same folder in the portable version.
