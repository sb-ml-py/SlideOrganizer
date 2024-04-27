# How To Set up Python
## Run Python on Notepad++
	1. Install python and Notepad++
	2. in Notepad++ run>run... 
		a. browse for python.exe (C:\Programs\Python\python.exe)
		b. add after the program -i $(FULL_CURRENT_PATH)
			[C:\Programs\Python\python.exe -i $(FULL_CURRENT_PATH)]
   	3. Save to [alt]+[R] as runPython
	
	
## Install Additional Packages (non-portable)
	1. Make sure python is installed to a directory you can access via cmd
	2. Open cmd
	3. Change directory to the folder that contains python
		>cd C:\Programs\Python
		
	4. Make sure pip is installed and up to date
		>python -m pip install --upgrade pip
		
	5. Install package
		>python -m pip install [package name]
		e.g. >python -m pip install openpyxl


## Install Additional Packages (portable)
	1. Install the package as above using a non-portable version of Python
	2. Copy the folders from the Python\Lib\site-packages from the non-portable version
	3. Paste them to that same folder in the portable version
