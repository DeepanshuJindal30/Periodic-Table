# Periodic-Table

A GUI periodic table allows users to click on an element or hover over it with the mouse to display information about the element, such as its symbol, atomic number, atomic mass, and properties. It may also provide links to more detailed information about the element or related topics.

Import the required libraries: tkinter, ttk, mysql.connector, and messagebox.

Create the main window using Tk(). Set the title of the window to "PERIODIC TABLE".

Create two LabelFrame widgets, root and user, using ttk.LabelFrame(). root will contain the periodic table, while user will contain user information (not implemented in the code you provided).

Define the conn function to connect to a MySQL database, execute a query to retrieve information from the info table, and return the result.

Create labels for the periods (rows) of the periodic table using a loop and the Label widget. Set the text of the labels to the period number and set the background color to white.

Create labels for the groups (columns) of the periodic table using a loop and the Label widget. Set the text of the labels to the group number and set the background color to white.

Define several lists containing the element symbols for each group of the periodic table.

Define the no function to retrieve information about an element from the MySQL database using the conn function and display it in a message box.

Create buttons for each element of the periodic table using a loop and the Button widget. Set the text of the button to the element symbol, the foreground color to black, the background color to a pale orange, and the width and height to 5 and 2 respectively. Set the command attribute of the button to the no function, passing in the element symbol as an argument.

Pack the root and user LabelFrame widgets to display them in the main window.

Run the main loop of the application using mainloop().
