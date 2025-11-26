# Bug List

> Make a list of the things that don't work as expected. Keep a list of things that you have fixed and try to document how you solved them.

1. <!--Problem: the prompt for a name displays the question in the console log and not the name input-->
2. <!--the loop doesnt work and the console log inside does nothing
3. <!--Less of a problem n more of a pet peeve, id like to move the buttons so they are centered underneath the dialogue

4. i want the user to be able to use the buttons over and over again but if i use document.write for the functions they dissapear, and if i use confirm() then the output for the intendedn second click of the 1st button appears anyway.

5. when the user presses option 1 button, the dialogue for option 4 comes too since the condition has been met, have to come up with a way to make it not appear until the button is clicked again.

6. the document write in the if and if else statements isnt working as they should, probably because i havent made a clear enough condition for when it should happen

7. trying to make the buttons reusable, starting w button 1 BUUUUT now the 1st button isnt working at all...

8. <!--if a name isnt in the box already the name is kept empty and even when input a name it will still read as <empty string>. but it works if you input a name and reload the page becuase it stays there for some reason.-->

9. having a lot of trouble with the arrays inside the arrays, current problem is weird, on line 29:32 theres an error Uncaught TypeError: can't access property "You are really social", [...]["Something happens, what do you do? 1. 2. 3."] is undefined. but that doesnt make sense to me, its litteraly reading out the contents of it to me, but in a weird order.

10. im having a weird paradox where the should be first since its a variable and so the function knows what to draw from for the introduction but since they contain the name the user put in then it should be lower down so the function can get it and use it but then it wont have the dialogue array.. god this is giving me a  headache. ill remove the name from the array for now and find a use for it later maybe?

11. The intro confirm boxes appear even though the textbox is left empty, not what i want for obvious reasons. 

12. <!--the intro text built into the confirm button function isnet appearng->
13. similar problem but now its only the else if part that isnt working.



# Fixed Bug List
1. Fixed: used an input form instead of a prompt()
2. Fixed: the user now inputs their name by input form so not sure how to make it loop any more or if its even necessary. debating on making a loop for the entirety of the "game" so users dont need to refresh the page, or maybe just give a prompt or  alert to restart the whole thing
3. 
4. semi-fixed: the buttons dont dissapear anymore but the 1st button still makes both choice1 and choice4 appear after each other
5. when pressin the buttons, no mattter which one it says the one belonging to the first. have no idea how it fixed itself.

6.


7. Fixed: disabled the code for option4 as it caused the button 1 function not to work at all.
8. it works better now since i moved 
<!--var data = document.getElementById("type in name");
console.log(data.value)
//saves the input name as a variable 
var name = data.value
console.log(name)-->
into the function for the text box, buuut now i cant access the name variable since it excists only inside the function. could i make a function inside the function? ok i tried that buut it didnt really work as id like to


9. fixed sort of , the arrays need a , between them to separate them apparently


11. fixed, changed the else if statement

12. i feel so big brain smart rn i just changed the username==true to (username!==false) and now it works.