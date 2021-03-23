# DOM Atomic 02: Hide Many Elements

## Questions

---

> How did you go about selecting the DOM elements to hide? Describe the "contract" for that function.

For hiding DOM elements was used querySelectorAll with .hide_me class.This function goes through all the sub-objects of the element and returns each element containing the specified selector as a list. 

---

> Describe how you were able to hide each element. Were you able to do it as one operation, or did you use a loop of some kind? Describe the "contracts" that were utilized to accomplish your goal.

To hide the elements, ForEach was used, which made it possible to make the function.