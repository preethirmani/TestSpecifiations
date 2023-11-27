 # UNIT TEST 1

 A function called "multiplication" that returns the product of the two input numbers.

# Expectations

the function multiplication will return the product of two numbers
the functions takes 2 arguments 
the 2 arguments are 2 numbers
the 2 arguments are 2 negative numbers
the 2 areguments are 1 negative and 1 positive number
the 2 arguments are 1 number and 0
we would expect multiplication(2, 3) will return 6
we would expect multiplication(-2, -3) will return 6
we would expect multiplication(2, -3) will return -6
we would expect multiplication(2, 0) will return 0

# Test Specs
1. Expect multiplication(2, 3) to return 6
2. Expect multiplication(2) to return 0 or error 
3. Expect mutliplication(2,'string') to return 0 or error
4. Expect multiplication('string', 'string') to return 0 or error
5. Expect muliplication() to return 0 or error
6. Exxpect multiplication (4,-3) to return -12
7. Expect mutliplication of (-4, -3) to return 12
8. Expect multiplication of (4, 0) to retrun 0


# Unit Test 2
# A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.
Example: concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1])
...should result in [-1, 1, 3, 9, 15]

# Expectation

1. the function concatOdds will correctly concatenate the two arrays and return 
2. The function should only return odd numbers
3. The function should return the array in ascending order
4. The function takes 2 arguments
5. The 2 arguments are 2 arrays with integers
6. The function should handle cases where one or both input arrays are empty.
7.  If neither array contains odd numbers (even numbers), the function should return an empty array.

# Test Specs
1. Expect concatOdds([1, 4, 5], [2, 3, 6]) to return [1,3,5];
2. Except concatOdds([9, 2, 7], [5, 4, 6]) to return [2,5,7,9];
3. Except concatOdds([], [2, 4, 6]) to return [];
4. Except concatOdds([2, 4, 6], [8, 10, 12]) to return [];
5. Except concatOdds([1, 3, 5, 5], [2, 4, 6, 7]) to return [1,3,5,7];


# Functional Tests:
# A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.

# Test Case 1
# Guest Checkout Functionality
 Objective : Verify that a user can successfully check out as a guest

 1. Navigate to the shopping cart
 2. Initiate the checkout process
 3. Select the option to check out as a guest
 4. Complete the checkout the process

Expected Result : Guest user completes the purchase without creating account.

# Test Case 2: Logged-in User Checkout
Objective: Confirm that a logged-in user can successfully proceed through the checkout process.

 1. Log in as a registered user.
 2. Add items to the shopping cart.
 3. Initiate the checkout process.
 4. Complete the checkout.

Expected Result: The user completes the purchase, and the system recognizes them as a logged-in user.


# Test Case 3: Account Creation Prompt for Guest Checkout
Objective: Ensure that a user checking out as a guest is prompted to create an account.

 1. Navigate to the shopping cart.
 2. Initiate the checkout process as a guest.

Expected Result: The system prompts the user to create an account during the guest checkout process.

# Test Case 4: Login Prompt for Guest Checkout
Objective: Verify that a user checking out as a guest is given the option to log in.

  1. Navigate to the shopping cart.
  2. Initiate the checkout process as a guest.

Expected Result: The system offers the user the option to log in during the guest checkout process.

# Test Case 5: Account Creation from Guest Checkout
Objective: Confirm that a user can successfully create an account during the guest checkout process.

  1. Navigate to the shopping cart.
  2. Initiate the checkout process as a guest.
  3. Choose to create an account during the checkout.

  Expected Result: The user creates an account seamlessly, and the order is associated with their new account.

# Test Case 6: Smooth Transition Between Guest and Logged-in Checkout
Objective: Ensure a smooth transition for a user who decides to log in during the guest checkout.

  1. Navigate to the shopping cart.
  2. Initiate the checkout process as a guest.
  3. Choose to log in during the guest checkout.

  Expected Result: The system seamlessly transitions the user to a logged-in checkout without losing order details.

# Test Case 7: Guest Checkout Order Persistence*
Objective:* Confirm that order details persist if a guest user decides to create an account during checkout.
 
  1. Navigate to the shopping cart.
  2. Initiate the checkout process as a guest.
  3. Choose to create an account during the checkout.
  
  Expected Result: The system preserves the shopping cart items and order details when the user creates an account during guest checkout.


 
 

