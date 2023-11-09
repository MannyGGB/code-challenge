# Code Review Questionnaire #2

- Given the following problem statements from the student, what would you say to advise them?
  "When I add items to my cart, everything works. Then if I go to the cart page the cart is empty"
  There must be a problem with your local storage. First of all, use console.log to see when your cart items return null or undefined. Make sure the input of your form does not appear on the URL when you refresh. Double check that you're using the right order to save items in your local storage and that you are using the correct JSON methods (stringify and parse).
- Have best practices been followed?
  One of the instructions mentions to reference elements without IDs, but IDs have been used (<div class="card" id="cartContents"></div>)
- What would you recommend they do to extend this?
  Depending on the stage of the course, learners could add an authentication system that connected a user to their shopping cart.
  As an intermediate stretch goal, learners could add a drop-down menu to show the contents of their cart.
- Are you able to identify any issues with the codebase?
  - In index.html, there is an overuse of non-semantic tags. The tag label is missing for="".
  - Although the scripts are linked at the bottom, they could be linked at the top in <head> and _defer_ added for a clearer organisation.
