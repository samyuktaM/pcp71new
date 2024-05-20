Quiz screen with Gestures
==========================

In this activity, you will learn to create a quiz interface in which you can select and answer using gestures.

<img src= "https://media.slid.es/uploads/1525749/images/10515976/PCP__1_.gif" width = "480" height = "320">


Follow the given steps to complete this activity:

1. ### Generate questions.

* Open the main.py file.

*  Delcare variable `equation` and call the function `generate_equation()` as its value to generate a random equation .
 
    `equation = generate_equation()`

* Declare a variable `solution` and call the `calculate_solution(equation)` as its value to generate the correct solution.
 
     `solution = calculate_solution(equation)`

* Declare a variable `wrong_solution` and call the `generate_wrong_solution(equation)` as its value to generate the wrong solution.
 
      `wrong_solution = generate_wrong_solution(solution)`

2. ### Select option

* Check if finger is over the choice area i.e y-axis value is less then 100.

      `if (indexFingerTop[1] < 100):`
      
 * There are only two options so check if x-axis of fingerTop is less then wWidth/2.
  
      `if (indexFingerTop[0] < wWidth/2):`
      
 * Set choice variable to option 1.
 
    `choice = option1`
    
 * Else set the choice variable to option2.
  
    `else:`
    
        `choice = option2`

* Save and run the code to check the output.






