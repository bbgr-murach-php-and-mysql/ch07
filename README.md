# murach_php_and_mysql_ch07 #
Murach's PHP & MySQL (3rd Edition), Chapter 06 Exercises

## Exercise 7-1 Get input and display output ##
In this exercise, you will write the PHP code that gets input from a form and displays output.

### **Open and test the application** ##
1. Start the Chrome browser and run the application in the ex_starts\\ch07_ex1 directory. To do that, you can use this URL.\
<http://localhost/ex_starts/ch_07_ex1/>\
This should display a form that has a variety of controls.
2. Enter some data, including a valid email address, and click on the Submit button. This should only display the data that you entered for the email address.

### **Write the code that gets and displays the data entered by the user** ###
3. Open the index.php file for this application and review the code. Note the name that are used for hte various input controls.
4. Open the display_results.php file for this application and review the code. Note that most of the code that gets data from the controls is missing. In addition, most of the code that displays this is missing.
5. Add the code that gets the data from the controls on the first page. Then, add the code that displays this data.
6. For the radio buttons, display a value of "Unknown" if the user doesn't select a radio button.
7. For the check box, display a value of "Yes" or "No" depending on whether the user has selected the check box.
8. For all fields that allow the user to type text into the field, make sure to convert special characters into HTML entities before displaying that data on the second page as described in figure 7-8.
9. For the comment field, make sure to convert new line characters to `<br>` tags so the web page can display new line characters correctly.
10. Test the application to make sure it works correctly. To do that, you can test text fields with special characters such as the ampersand (&), and you can press the Enter key in the comments field to enter a new line character.

## Exercise 7-2 Enhance the Future Value application ##
In this exercise, you will enhance the Future Value application of chapter 2 so it uses drop-down lists instead of text boxes.

### **Open and test the application** ###
1. Start the Chrome browser and run the application in the ex_starts\ch07_ex2 directory. This should display the first page of a Future Value application that's similar to the one presented in chapter 2. Note that this page displays three default values in the three text boxes.
2. Click the Calculate button to perform the calculation. Note that this displays the correct future value calculation on the second page.

### **Write the code that gets and displays the data entered by the user** ###
3. Open the index.php file for this application and review the code. Note the names that are used for the three text boxes.
4. Modify the code so it uses drop-down lists instead of text boxes for the first two entries.
5. For the investment amount, the drop-down list should display values from 10,000 to 50,000 incremented by 5,000. To do this, you can use a for loop that creates the HTML for the drop-down list.\
If you have any trouble with this, you may want to look ahead to the last example in figure 8-11 of the next chapter. Or, you can come back to this after you read chapter 8.
6. For the yearly interest rate, the drop-down list should display values from 4 to 12 incremented by 5.
7. Test the application to make sure it works correctly.
