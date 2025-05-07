🔍 Short Description
This Python script creates a graphical interface using Tkinter that allows users to load various Excel files into corresponding SQL Server tables. It supports multiple data sources (e.g., PIM, ME, GH, OEM, Peru, Colombia, Ryco) defined in a configuration list. The script:

Reads Excel files based on keywords from shared directories,

Cleans and prepares the data (fills missing values, adds timestamps, and optional source),

Optionally truncates the target table before insert,

Inserts data into SQL Server dynamically using pyodbc,

Moves processed files to an archive folder, and

Notifies the user via message boxes.

Each button in the GUI executes the corresponding data loading function
