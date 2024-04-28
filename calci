total_sum = 0  # Initialize total sum to 0 outside the loop

while True:
    user_input = input("Enter the item price or press q to quit: \n")  # Use clear variable names
    if user_input != 'q':
        try:
            price = float(user_input)  # Convert input to a float for accurate calculations
            total_sum += price  # Add the price to the total sum using += operator
            print(f"Order total so far: {total_sum:.2f}")  # Print total with 2 decimal places
        except ValueError:
            print("Invalid input. Please enter a number or 'q' to quit.")
    else:
        break  # Exit the loop when user enters 'q'

print(f"Your bill total is: {total_sum:.2f} Thanks for using our calculator!")
