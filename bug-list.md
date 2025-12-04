# Bug List

> Make a list of the things that don't work as expected. Keep a list of things that you have fixed and try to document how you solved them.

1. <!--Problem: the prompt for a name displays the question in the console log and not the name input-->
2. <!--the loop doesnt work and the console log inside does nothing
3. <!--Less of a problem n more of a pet peeve, id like to move the buttons so they are centered underneath the dialogue

4. <!--i want the user to be able to use the buttons over and over again but if i use document.write for the functions they dissapear, and if i use confirm() then the output for the intendedn second click of the 1st button appears anyway.-->

5. <!--when the user presses option 1 button, the dialogue for option 4 comes too since the condition has been met, have to come up with a way to make it not appear until the button is clicked again.-->

6. <!--the document write in the if and if else statements isnt working as they should, probably because i havent made a clear enough condition for when it should happen-->

7. <!--trying to make the buttons reusable, starting w button 1 BUUUUT now the 1st button isnt working at all...-->

8. <!--if a name isnt in the box already the name is kept empty and even when input a name it will still read as <empty string>. but it works if you input a name and reload the page becuase it stays there for some reason.-->

9. <!--having a lot of trouble with the arrays inside the arrays, current problem is weird, on line 29:32 theres an error Uncaught TypeError: can't access property "You are really social", [...]["Something happens, what do you do? 1. 2. 3."] is undefined. but that doesnt make sense to me, its litteraly reading out the contents of it to me, but in a weird order.-->

10. <!--im having a weird paradox where the should be first since its a variable and so the function knows what to draw from for the introduction but since they contain the name the user put in then it should be lower down so the function can get it and use it but then it wont have the dialogue array.. god this is giving me a  headache. ill remove the name from the array for now and find a use for it later maybe?-->

11. The intro confirm boxes appear even though the textbox is left empty, not what i want for obvious reasons. 

12. <!--the intro text built into the confirm button function isnet appearng->
13. <!--similar problem but now its only the else if part that isnt working. the one thats suposed to prompt the user to input a name if they havent already.-->

14. <!--the pink button works but only for the else if at the end, the rest are left unused-->

15. <!--The pink if function works as should but the else if s under it pull from the green and then blue arrays instead.-->
16. opposite problem to no 14. the last else if doesnt appear at all

17. the click tracker currently makes an infinte loop of constantly outputting the contents of the arrays.
function clickTracker (){
   //function to keep track how many times the buttons are pressed and increase the number variable when the button is pressed
   if
   (Pink()) {
      number++
      console.log("Pink as pressed "+ number +" of times")
      console.log("clickTracker is currently at "+number)
   }
  if
   (Green()) {number++
      console.log("Green as pressed "+ number +" of times")
   console.log("clickTracker is currently at "+number)}
 if
      (Blue()) {number++
      console.log("Blue as pressed "+ number +" of times")
   console.log("clickTracker is currently at "+number) }
else {console.log("No buttons been pressed")}
}. currently left unused as its not very helpful


# Fixed Bug List
1. Fixed: used an input form instead of a prompt()
2. Fixed: the user now inputs their name by input form so not sure how to make it loop any more or if its even necessary. debating on making a loop for the entirety of the "game" so users dont need to refresh the page, or maybe just give a prompt or  alert to restart the whole thing
3. fixed sort of, also given them colors and changed font sizes for the text above
4. Fully fixed, the buttons now have if and else if statements to let them be used over and over again.
5. when pressin the buttons, no mattter which one it says the one belonging to the first. have no idea how it fixed itself.

6. not relevant anymore.


7. Fixed: disabled the code for option4 as it caused the button 1 function not to work at all.
8. it works better now since i moved 
<!--var data = document.getElementById("type in name");
console.log(data.value)
//saves the input name as a variable 
var name = data.value
console.log(name)-->
into the function for the text box, buuut now i cant access the name variable since it excists only inside the function. could i make a function inside the function? ok i tried that buut it didnt really work as id like to


9. fixed , the arrays need a , between them to separate them apparently.


10. the name variable is possible to change and to acess if you dont do what i did where i wrote var before the name variable cuz then it is seen as an entirely new variable. 

11. fixed, changed the else if statement

12. i feel so big brain smart rn i just changed the username==true to (username!==false) and now it works.

13. turns out id given [] to the dialogue part where it wastnt needed confirm(dialogue[PINKroute][0])

14. fixed, by changing the route back to no.1 again inside the if and else if.

15. fixed by redefining route to = 1 again before the rest happens

16.

17.