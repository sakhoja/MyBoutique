# MyBoutique
Python
Detailed Project Description:-
The Digital Indian Store Boutique Shopping App is a Python application built using the tkinter library for GUI, matplotlib for data visualization, and pandas for data analysis. The application simulates a boutique shopping experience where customers can browse through different categories of products such as Sarees, Sherwani Suits, Pathani Kurtas, and Jewellery. They can add items to their cart, specify quantities, choose shipping options, and select payment methods. 
Programming Concepts Implemented:-
1.	Object-Oriented Programming: Utilized classes (AllProducts, Sarees, SherwaniSuits, PathaniKurtas, Jewellery) for modeling different product categories.
2.	Graphical User Interface (GUI): Developed a GUI using tkinter for a user-friendly shopping interface.
3.	Data Visualization: Implemented pie charts, bar charts, and histograms using matplotlib to visualize sales data and payment method distribution.
4.	Data Handling: Used JSON for saving and loading purchase data, and pandas for creating data structures for sales analysis.

Overall Summarised Flow of the Program:-
The program begins with a tkinter window. 
Welcome messages and instructions appear.
The customers enter their details and make selections. They can:
•	Choose a product category and then a specific product.
•	Specify the quantity, select shipping options as well payment options.
•	Add items to their cart and view their cart.
•	View visual representations of sales data through pie charts, bar charts, and histograms.
******************************************************************
Start --> 
•  Start: Application starts execution.
•  Main Window Display: The main window of the GUI is displayed to the user.
•  User Inputs:
•	User enters their Customer Name.
•	User selects a Category from the dropdown menu (Category Selection).
•	Based on the selected category, the Product Selection dropdown is updated.
•	User selects a specific Product from the dropdown.
•	User specifies the Quantity of the selected product.
•	User selects a Shipping Option (In-store Pickup or FedEx Delivery).
•  Add to Cart Button Clicked:
•	User clicks the "Add to Cart" button to add the selected item with specified options to the cart.
•  Validate Inputs:
•	Product Category Validation: Ensures that a valid category is selected.
•	Product Selection Validation: Verifies that a product is selected from the updated dropdown.
•	Quantity Validation: Checks that the quantity entered is valid (usually within a specified range).
•	Date Format Validation: Validates the date format (YYYY-MM-DD) for the purchase date.
•  Calculate Item Price (including Shipping):
•	Determines the total price of the selected item including any applicable shipping charges (if FedEx Delivery is selected).
•  Update Cart (Add Item Details):
•	Adds the details of the selected item (name, price, quantity) along with customer details (name, date) to the cart.
•  Save to JSON File:
•	Optionally, saves the current cart contents (purchases) to a JSON file for future reference.
•  Success Message Displayed:
•	Displays a success message confirming that the item has been added to the cart.
•  Display Carts Button Clicked:
•	User clicks the "Display Carts" button to view all items currently in the cart.
•  Display Cart Details (MessageBox):
•	Shows a messagebox or dialog displaying the details of all items in the cart including customer information, purchased items, and total amount.
•  Display Pie Chart Button Clicked:
•	User requests to view a pie chart showing the distribution of sales by product category.
•  Calculate Percentage of Sales by Product:
•	Calculates the percentage of total sales represented by each product category.
•  Display Pie Chart:
•	Generates and displays the pie chart illustrating the sales distribution by product category.
•  Display Date-wise Sales Chart Button Clicked:
•	User triggers the display of a histogram chart showing total sales over time, categorized by date.
•  Calculate Date-wise Percentage of Sales by Products:
•	Analyzes sales data to determine the distribution of sales over specific time periods (e.g., daily, monthly).
•  Display Histogram Chart:
•	Creates and presents the histogram chart depicting the distribution of sales over time periods.
•  End: The application concludes its execution or waits for further user interaction.
******************************************************************

