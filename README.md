Comic Book Server
===============

A web API/Application that serves up CBR and CBZ comics and displays them in the browser.


## DESCRIPTION:

This is a web API/Application wriiten in python and using flask. ( pip install flask ) 

####This allows you to read your digital comic collection in a web browser on any device. 


In its current state it will take a folder of comics ( CBZ and CBR only right now ) and will allow a user to browse through all subdirectories and select comics.

Once selected the comic is copied to a static folder, unpacked, embedded into some html and displayed. Each comic is served up from a unique folder.

###Currently you will want to clean out the unique folders generated in the static folder every once an a while. It does not have a janitor. 



## VERSION HISTORY:

**v0.1a** 
* Core Functionality, and some html styling. IT FUCKING WORKS!!

**v0.2a**
* Added Loading screen for unpacking comics

**v0.3b**
* Added Some basic application logging (incomplete)
* Added auto scroll to top on Comic Load and Entering a new directory
* Added support for GIF and PNG
* Corrected Logo and Loading to not rely on external address
* Added info div and link
* Added better error handling for running in production 

**v0.4b**
* Removed dependency for hardcoded urls
* Updated loading screen 
* Added tornado front end ( for production)
* Abstracted views to templates
* Improved Logging

## HELP:

Feel free to send me a message! I will be glad to explain my work.
