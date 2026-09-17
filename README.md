# Interactive Data Visualization Application
<br>

This Python project allows data visualization on a 2D graph, connecting points with a dashed line and displaying the name associated with each point. The `matplotlib` library is used to create the graphs, and `numpy` is used to manipulate the data.
<br>

## GUI Usage
<br>

To run the program and visualize the graph using the graphical user interface:
<br>

1. Run the Python script `main.py`:
    ```sh
    python main.py
    ```
<br>

2. In the GUI window, you can add data rows by entering the name, x value, and y value in the corresponding fields and clicking the "Add Row" button.
<br>

3. To delete a row, click the "Delete" button next to the row you want to remove.
<br>

4. After entering all the data, click the "Draw Graph" button to generate and display the graph.
<br>

## Project Structure
<br>

- `main.py`: The main script that launches the graphical user interface.
- `gui.py`: Contains the `DataEntryApp` class that manages the graphical user interface for data entry.
- `graph.py`: Contains the functions for reading data from the CSV file and drawing the graph.
- `data.csv`: The CSV file containing the input data.
<br>

## Dependencies
<br>

Make sure you have the following Python packages installed:
<br>

- `tkinter`
- `matplotlib`
- `numpy`
<br>

You can install them using `pip`:
<br>

```sh
pip install matplotlib numpy tkinter
```
<br>

## Features

- Add Rows: Allows adding new data rows through the graphical interface.
- Delete Rows: Allows deleting data rows from the graphical interface.
- Draw Graph: Generates and displays a 2D graph based on the entered data or data loaded from the CSV file.
- Data Sorting: Sorts the data based on x values before displaying it on the graph.
- Point Labeling: Displays the name associated with each point on the graph.
