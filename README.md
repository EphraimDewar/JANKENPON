1. explain how the game works(how the user has to press there key board r for Rock etc.. )

- in the html at the top of the page write instruction in a P tag

2. player chooses R,P,S on the keyboard

- using the document on key up event capture the the user key
- console log the key selected
- capture player selection and store in variable => playerSelection

3. computer chooses random R,P,S

- create array with computer options of "r","p","s"
- store array in variable
- get random number with javascript between 0 and including 0 all the way up to and including 2
- capture user selection and store in a variable => computerChoice

4. determine winner:

   - If user picks rock and if computer picks scissors then  
      user wins
     end

   - If user picks rock and if computer picks paper then
     user loses
     end

   - If user picks scissors and if computer picks rock then
     user loses
     end

   - If user picks scissors and if computer picks paper then  
      user wins
     end

   - If user picks paper and if computer picks rock then
     user wins
     end

   - If user picks paper and if computer picks scissors then
     user loses
     end

   - else
     user picks the same as computer then they tie
     end

5. if player ties then
   add 1 to ties
   end
6. if player losses then
   add 1 to losses
   end
7. if player wins then
   add 1 to wins
   end
8. player presses E,P,S to play again



### File

* [`rps-2`](Unsolved/rps-2.html)

### Instructions

* In groups of 4, begin the process of coding out the rock-paper-scissors game.

**Rules for rock-paper-scissors**

Rock: wins against scissors, loses to paper, and ties against itself.
Paper: wins against rock, loses to scissors, and ties against itself.
Scissors: wins against paper, loses to rock, and ties against itself.

![3-RPS-Example-Picture](Images/9-RPS-example.png)

* Do as much as you can on your own, but don't be afraid to ask for help if you feel your team is struggling.

* **NOTE:** A `for-loop` is not technically necessary to make our RPS game, but could be used. Focus on the topics we have just covered when thinking about how to build out the game.

* **NOTE:** Don’t use `document.write` as it will delete the contents of your page including your JavaScript. Use `document.querySelector` or `document.getElementById`, alongside either `innerHTML` or `textContent`, to write to the DOM.

* **NOTE:** Don't worry. We know this is a very challenging assignment. We also know that you won't know where to start. In fact, we haven't shown you EVERYTHING you need yet, but that's okay. Part of being a developer is figuring things out on your own through trial and error.
