Explanation

1. Prompt the User:
   The program repeatedly prompts the user to enter a date or type "exit" to quit.

2. Parse the Entered Date:
   The entered date is parsed using `DateTime.TryParse`. If the input is invalid, an error message is shown.

3. Compare the Entered Date:
   The difference between the entered date and the current date is calculated using `DateTime.Now`.

4. Display the Appropriate Message:
   - If the difference in days is zero, the entered date is today.
   - If the difference in days is positive, the entered date is in the future.
   - If the difference in days is negative, the entered date is in the past.

5. Handle Invalid Date Inputs:
   Invalid date inputs are handled gracefully by displaying an error message.

6. Loop Continuously:
   The program runs in a loop until the user types "exit".
