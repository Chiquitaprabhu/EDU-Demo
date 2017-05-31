# EDU-Demo
Simple site to take the name of a movie along with some metadata and store in localStorage using Javascript.

----- ----- ----- ----- -----
The HTML page has four text input fields for accepting the required data. The submit button sends the form data to a Javascript script which will store this data in a JSON format in the localStorage. The first time that the form is submitted, the script creates a new element called "MovieDataJSON" and every other time, will just append the new data to this already created localStorage element.

The HTML interface also has three buttons for debugging:
1. Dump LocalStorage : It dumps the contents of the localStorage onto an alert box.
2. Clea LocalStorage : It clears the localStorage's element which stores the data related to this application.
3. Check LocalStorage : It asserts whether the element ("MovieDataJSON") exists in LocalStorage through an alert.
