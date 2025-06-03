# Functionalities and Implementation:

1. **Enhanced User Roles:**
   - Create separate roles for Admin and Customer. Separate Login Methods
   - Admin: Can add, update, and delete products, and view user activities, can also deactivate    user.
   - Customer: Can browse products, leave reviews, and make purchases.
   - Implementation: Use conditional checks to identify the role during login.

2. **Product Management:**
   - Allow Admins to manage products (add, update, delete) and Customers to browse product lists.
   - Implementation: Store product information in arrays or files .

3. **Add to Cart:**
   - Allow Customers to add products to a cart for later purchase.
   - Implementation: Use arrays to temporarily store cart items and save to a file for persistence.

4. **Sorting and Filtering:**
   - Allow Customers to sort products by price, rating, or category and filter by price range or category.
   - Implementation: Use sorting algorithms (e.g., Bubble Sort or Selection Sort) and conditional checks for filtering.

5. **Banking Information:**
   - Add dummy payment methods like credit/debit card or wallet balance and generate receipts.
   - Implementation: Use file handling to store dummy payment details and create receipt files.

6. **Review System:**
   - Allow Customers to leave reviews and ratings for products.
   - Implementation: Use arrays or files to store reviews and calculate average ratings for display.

7. **Order Management:**
   - Enable Customers to view their cart, confirm orders, and check order history.
   - Implementation: Use file handling to save order details and display past orders.

8. **Error Handling:**
   - Handle invalid inputs, missing files, and other runtime errors gracefully.
   - Implementation: Use `try-catch` blocks, a mechanism for handling exceptions (errors that occur during program execution)  and input validation to ensure smooth program execution.

9. **Data Persistence:**
   - Save user details, product information, and transaction history between program runs.
   - Implementation: Use file handling to read/write data to files for all major functionalities.
