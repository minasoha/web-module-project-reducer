# Understanding Questions:

1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

- The user presses the 1 button.
- ...
  Step 1. A user clicks on 1
  Step 2. OnClick function executes which then will go to addOne function in actions.
  Step 3. It will then go to reducers and look for the corresponding case which is ADD_ONE
  Step 4. It will run the ADD_ONE case and returns the outcome of it then it puts it back to addOne and it displays On screen.

- TotalDisplay shows the total plus 1.
