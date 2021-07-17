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