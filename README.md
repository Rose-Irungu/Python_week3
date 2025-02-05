# Discount Calculator

## Overview
This Python script calculates the final price of an item after applying a discount, but only if the discount is **20% or higher**. If the discount is below 20%, the original price remains unchanged.

## How It Works
- The script defines a function `calculate_discount(price, discount_percent)`, which:
  - Checks if the discount percentage is **20% or higher**.
  - Applies the discount if the condition is met.
  - Returns the original price if the discount is lower than 20%.
- The user is prompted to enter:
  - The original price of the item.
  - The discount percentage.
- The script then prints the final price after checking the conditions.

## Installation and Running the Script
### Prerequisites
- Python 3 must be installed on your system.
- VS Code (optional but recommended).

### Steps to Run the Script
1. **Clone or Download the File**
   - Save the script as `index.py` in a directory of your choice.

2. **Open the Script in VS Code**
   - Open **Visual Studio Code**.
   - Click on **File > Open Folder** and select the folder where `index.py` is saved.
   - Open `index.py` in the editor.

3. **Run the Script in Terminal**
   - Open the terminal in VS Code (`Ctrl + ~` or **View > Terminal**).
   - Navigate to the directory (if needed):
     ```sh
     cd path/to/your/file
     ```
   - Run the script using:
     ```sh
     python index.py
     ```
     *(Use `python3 index.py` if using Python 3 on macOS/Linux.)*

4. **Enter User Inputs**
   - The script will prompt you to enter the **original price** and **discount percentage**.
   - Enter values and press **Enter**.

5. **View the Output**
   - If the discount is **20% or more**, the final price after the discount is displayed.
   - Otherwise, it informs the user that no discount was applied.

## Example Usage
```
Enter the original price of the item: 100
Enter the discount percentage: 25
Discount applied! The final price is: $75.00
```

## License
This project is for educational purposes only. Feel free to modify and use it.

## Author
**Rose Njeri Irungu**

