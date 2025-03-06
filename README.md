# Price Calculator

A simple Python program that allows users to enter item prices and calculates the total bill.

## How It Works

- The program continuously prompts the user to enter an item price.  
- It adds each valid price to the total sum.  
- If the user enters `'q'`, the program stops and displays the final bill total.  
- If the user enters an invalid input (non-numeric and not `'q'`), an error message is shown.  

## Usage

Run the script in a Python environment:  

```sh
python calci.py
```

### Example

```
Enter the item price or press q to quit:  
10  
Order total so far: 10.00  

Enter the item price or press q to quit:  
5.5  
Order total so far: 15.50  

Enter the item price or press q to quit:  
q  
Your bill total is: 15.50 Thanks for using our calculator!
```
