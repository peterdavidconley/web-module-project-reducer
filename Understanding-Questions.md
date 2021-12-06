# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* The handleNumber(1) function fires
* applyNum() function is used via dispatch
* Dispatch updates the state.total
* Total is rendered in <TotalDisplay /> component
...

* TotalDisplay shows the total plus 1.
