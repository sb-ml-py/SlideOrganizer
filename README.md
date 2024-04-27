# SlideOrganizer
[Slide_Organizer.py](Slide_Organizer.py) is a simple program meant to organize digital slides into an SQLite database. It will create the database, allow for viewing, searching, adding slides, removing slides, and printing the database to an Excel (.xlsx) spreadsheet. Slides can be added or removed en-masse using an Excel spreadsheet as well.

This database serves only to organize information associated with the slide collection and does not edit any of the slides themselves. It essentially functions the same way one would record information about their collection on paper or in a digital spreadsheet. The advantage of using an SQLite database over a spreadsheet is that the information is integral to each entry, so the information is higher fidelity - namely sorting and searching the collection does not risk modifying the data in the collection.

I suggest creating a folder such as "Slidebox' that will house Slide_Organizer.py and a subfolder called "Slides" that will house the actual collection (.svs files). However for simplicity, you may wish to store your slide collection in the "slidebox_files" folder that the database resides in.

## Prerequisites
1. Python
2. Additional Python libraries: openpyxl, tabulate

For help setting up Python with the appropriate libraries, see [How to Set Up Python](setup_python.md)

## Instructions
1. Download [Slide_Organizer.py](Slide_Organizer.py) into your desired slidebox folder. This can be on a removable drive or on a computer.
2. Run [Slide_Organizer.py](Slide_Organizer.py) with Python
