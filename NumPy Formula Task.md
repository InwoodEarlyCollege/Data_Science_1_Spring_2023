# NumPy Formula Task

For this task...

* Use Jupyter Notebook to write and execute your code.
* Thoroughly comment all code.
* Include an appropriate title and subtitles.
* Upload your work to your Data Science 1 Spring 2023 repository on GitHub.
* As you work, remember to periodically update and commit your work (including a short comment for each commit).



### Part 1: Begin by selecting a formula to use for this task.

**Note:** For this task, be sure to select a formula that can be written explicitly (*i.e., one variable in terms of all other variables*).

Consider selecting one of the following types of formulas:

* Geometric formula for area, surface area, or volume (*e.g. The formula for find the surface area of a rectangular prism is SA = 2WL + 2WH + 2LH, where W = width, L = length, and H = height.*)
* Conversion formula (*e.g. The formula to convert temperature measured in degrees Celcius to the temperature measured in degrees Fahrenheit is F = (9/5)c + 32, where C = temperature measured in degrees Celcius and F = temperature measured in degrees Fahrenheit.*)
* Formula from a specific discipline (*e.g. In Physics, Newtown's second law states, F = ma, where F = Force, m = mass, and a = acceleration.*)

If you need some inspiration in selecting a formula, check out the following resources:

* https://www.matematica.pt/en/useful/math-formulas.php
* https://www.easycalculation.com/formulas/health.html
* https://owlcation.com/stem/Top-Ten-Beautiful-Physics-Equations

### Part 2: For each input variable in your formula, generate a list of at least ten random data points.

Example 1/ Given the formula to find the surface area of a rectangular prism, SA = 2WL + 2WH + 2LH, generate the following lists:

* List of at least ten randomly generated widths.
* List of at least ten randomly generated lengths.
* List of at least ten randomly generated heights.

Example 2/ Given the formula to find Body Mass Index, BMI = weight / height^2^, generate the following lists:

* List of at least ten randomly generated weights.
* List of at least ten randomly generated heights.

These data sets will be used to test your program.

### Part 3: Without using NumPy, generate a list of output values based on the input values generated earlier in your program.

Example 1/ Given the formula to find the surface area of a rectangular prism, SA = 2WL + 2WH + 2LH, generate a list of surface areas based on the lists of widths, lengths, and heights randomly generated earlier in the program.

Example 2/ Given the formula to find Body Mass Index, BMI = weight / height^2^, generate a list of BMIs based on the lists of weights and heights randomly generated earlier in the program.

Test your code by displaying your list of output values.

### Part 4: This time, use NumPy to generate a NumPy array of output values based on the input values generated earlier in your program.

If you need some help completing this part of the task, refer back to Data Camp > Introduction to Python > NumPy > Video 1.

Test your code by displaying your NumPy array of output values.

### Part 5: Write a function that accepts all input variables as arguments and returns the output variable.  Then apply, the function to generate a NumPy array of output values based on the input values generated earlier in your program.

If you need some help completing this part of the task, refer back to Data Camp > Introduction to Python > NumPy > Video 1.

Test your code by displaying your NumPy array of output values.

### Part 6: Conduct some basic data analysis.

1. Generate a NumPy array of boolean values by testing a given condition on your NumPy array of output values.  
	* Example 1/ Surface Areas
		* NumPy array of surface areas: [10  8  4  15  9  7  11  10  5  17]
		* Condition: "Surface area is greater than or equal to 10."
		* NumPy array of boolean values: [True  False  False  True  False  False  True  True  False  True]
	* Example 2/ BMIs.
		* NumPy array of BMIs: [22  19  24  25  28  33  21  29  30  24]
		* Condition: "BMI is healthy (i.e. between 25 and 30 (inclusive))."
		* NumPy array of boolean values: [False  False  False  True  True  False  False  True  True  False]
	* Display your results.

2. Generate a NumPy array of all values that meet a specific condition.
	* Example 1/ Surface Areas
		* NumPy array of surface areas: [10  8  4  15  9  7  11  10  5  17]
		* Condition: "Surface area is greater than or equal to 10."
		* NumPy array of values that meet the given condition: [10  15  11  10  17]
	* Example 2/ BMIs
		* NumPy array of BMIs: [22  19  24  25  28  33  21  29  30  24]
		* Condition: "BMI is healthy (i.e. between 25 and 30 (inclusive))."
		* NumPy array of values that meet the given condition: [25  28  29  30]
	* Display your results.
		
3.  Determine the minimum or maximum value in your NumpyArray.
	* Display your results.
