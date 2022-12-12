his code segment has several logical errors as well as several syntax errors. If you've forgotten, logical errors are errors where the output is different from the expected output and syntax errors occur when the requirements of the language are not respected.
This question is split into two parts - in the first part, select all the syntax errors and in the second part, select all the logical errors.
<!DOCTYPE html>
<html>

<head>
    <title> Milkshake time!</title>
</head>

<body>
    <script type="text/javascript">
        document.write("You're going to create your own milkshake!");
        var price = 0, taxRate = 0.03;
        milk_type = window.prompt("Please enter the type of milk you would like(regular, almond or oat): ");

        if (milk_type == "regular");
            price = 1.00;
        else if (milk_type == "almond" && milk_type == "oat")
            price = 1.50

        var choice;
        window.prompt("veggies or fruits or both: ");

        /* price of fruits is 2.00, price of veggies is 1.95 /*
        if (choice == "veggies")
            price = price + 1.95;
        if (choice == "fruits")
            price = price + 2.00;
        if (choice == "both")
            price = price + 1.95 + 2.00;
        price = (price + price) * taxRate;
        window.alert("Your total price is: "+ price + " Enjoy!");
    </script>
</body>

</html>

——————————————————————————

Select all the syntax errors in the code above.

the first line of the 'if' statement should have a semi-colon at the end

comments in Javascript should end with a semi-colon

the variable taxRate should be declared and initialized on a separate line


missing semi-colon in 'else-if' statement

the multi-line comment was not closed correctly


missing assignment for second window prompt

Select all possible options that apply.

————————————————————————— 

Select all the logical errors in the code above.

the 'else-if' statement makes more sense if it uses || instead of &&

the taxRate should be added to the total price


there is no need to add price to itself in the the last three if-statements

the total price isn't calculated correctly


the total price is calculated correctly, but not displayed to the user correctly
Select all possible options that apply.

————————————————————————————

The piece of code below is supposed to print a 10x10 multiplication table. It currently has several critical logic and syntax errors, but all the errors are within the script tag - in other words, the HTML code is written correctly. Rewrite the code below to make it produce the desired output, you are welcome to rewrite the code in any way you like to produce the desired output (by adding, removing, or changing lines as you like).
The desired output is (without the commas): [1,2,3,4,5,6,7,8,9,10,2,4,6,8,10,12,14,16,18,20,3,6,9,...,80,90,100].
**Note: For this question, you must store the each value of the multiplication table in an array called arraylist.
<!DOCTYPE html>
<html>

<head>
    <title>Loop Coding Question</title>
</head>

<script>

    var arraylist = new Array(100);

    while (x <= 10) {
var x = 1;
        while (y <= 10) {
var y = 1;
            y++;
            arraylist[x] = x * y;
        }
        x++;

    }
    document.write(arraylist);
</script>

</html>

—————————————————————————————

Write JavaScript code that has the following features/functionality:
Specifications
	•	Prompt the user for a positive integer N using an alert.
	•	Check to see if the input value is a number using the Number.isInteger(N) function. If N is not an integer, the program should terminate with a message displayed in the HTML document indicating that the input value was not a number.
	•	Hint: You can find the documentation and usage for this function here.
	•	If N is not a positive number (i.e. is zero or negative), the program should terminate with an error message displayed in the HTML document indicating that the number should be positive.
	•	If N is positive, the program should write to the HTML document all the numbers from 1 to N, along with the string "odd" or "even" depending on whether the number is even of odd.
	•	At the end of printing out all the numbers, you should also print the sum of these numbers.
Sample Output
A) If a user enters "HelloWorld", then the output should be something like: Wrong Type! Please enter a positive integer. Program terminated.
B) If a user enters -4, then the output should be something like: Wrong Value! Please enter a positive integer. Program terminated.
C) If a user enters 3, then the output should be:
1 Odd
2 Even
3 Odd
The sum is 6.

—————————————————————————————

Write code that will take a user input and will print a triangle the with a width size that matches it.

Eg.

User Input: 4

*
**
***
**** 

———————————————————————————

Write code that creates random numbers using the random
Number generator associated with the language that you code in, then fill an array with those values and then run through that array and grab the largest and smallest number
