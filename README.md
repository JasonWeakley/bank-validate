BANKING FORM EMAIL VALIDATION
This is an exercise from Cohort 12 of the Nashville Software School designed to teach me how to validate a specific input field named "email" that will turn the field background green if a valid email is entered, and red if an invalid entry is made.

What I learned:
I learned that giving a valid input field a class is very linear, and the CSS follows the HTML. Styling the HTML with CSS requires that the input be followed by the ".email" which would normally begin the CSS command. In this case it immediately follows "input" without spaces, and then is followed by ":valid" or ":invalid" without spacing.

input.email:valid {
	background-color: lightgreen;
}