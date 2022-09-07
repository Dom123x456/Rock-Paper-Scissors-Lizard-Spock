# **Rock papers scissors lizard spock**
## *My Goals and Description*
---
The purpose of this site is to show that i have created a functional game within Java script that holds up to a decent standard. The actual site itself is a spin on rock papare sicissors with two other options that the player can uses to play againts the computer.

the live site is linked here -
https://dom123x456.github.io/Rock-Paper-Scissors-Lizard-Spock/

# **Contents**

1. UX Design
2. My Game across different devices
3. Technologies used
4. Website Features
5. Testing 
6. Bugs and Issues
7. Material used and References

# **UX Design**
From my Game I decied to use a mixture of vibrant colors to capture the eye of the user but also to not distract them from the actual game itself.

Page Layout:
- Start Page:
  - Game Rules 
  - Supporting Image 
  - Buttons
  - Score counter

Colors Used:

- hsl(204, 73%, 41%)  Dark Blue
- hsl(0, 16%, 45%) Light Blue 
- #ffffff White
- hsl(229, 64%, 46%) Darker Blue
- hsl(229, 25%, 31%) Dark Gray/Navy Blue
- Button scissors: (hsl(4, 94%, 41%), hsl(40, 95%, 62%)) Red and Dark Yellow
- Button paper: (hsl(230, 98%, 26%), hsl(93, 89%, 65%)) Dark Blue and Light Green
- Button rock: hsl(349, 81%, 49%), hsl(59, 73%, 54%)) Dark Red and Dark Yellow
- Button Lizard: hsl(261, 97%, 35%), hsl(253, 70%, 32%)) Dark Purple and darker faded Purple
- button spock: (hsl(133, 87%, 43%), hsl(118, 46%, 28%))  Green and Dark Green

This is not including shadow box values and the button values are used as linear gradiants.

Game Page:
- rules button
- play again button
- score board
- AI and user choices
- results/score


# **My Game across different devices**
***Desktop view***

 ![image](https://user-images.githubusercontent.com/108178672/188937797-bd6d9709-6d36-4692-a418-d1b7a449b67c.png)


 ***Mobile view***



![image](https://user-images.githubusercontent.com/108178672/188955510-9bad184c-a422-4b90-b970-eb2212d1bcae.png)







***Game view mobile***




![image](https://user-images.githubusercontent.com/108178672/188938091-84c84243-d5ca-4fbe-98f9-043cc318a64d.png)




***Game view Desktop***

![image](https://user-images.githubusercontent.com/108178672/188954097-72feb849-83ad-4810-abec-1733797b7fe4.png)


All different aspects and views of the site are in with accordance with the pass critera. 
# **Technologies used**
- HTML5 - Used to structure my website

- CSS3 - Used to style my website

- JS - Used to provide logic to my website

- Github - The cloud based service for hosting repositories for over 73 million developers

- Git - Used to add, commit and push my changes to the server

- Favicon.io - Used to source my favicon icons for my website

- Google Fonts - Used to source different fonts in my css file

# **Website features**
My website contains an assortment of buttons, transitions, icons, a score board and the abillity toplay against the computer. Specifically it shows how many times you have won or lost and tallys the score on the top right box. There is a rule button on the bottom of the right hand side that shows the rules on how the game works that appears on the left.

![image](https://user-images.githubusercontent.com/108178672/188955754-e82bfd28-e957-44bd-8923-cab250309ced.png)

On the results page it shows you what the computer has chosen and tallys the score depending on a win or a loss. there is a hover function over each result showing you what was picked and a button asking to play again.
![image](https://user-images.githubusercontent.com/108178672/188956896-89e0a999-3123-4e84-8ce3-c78ac9b7bf07.png)


Below is the rules that are triggered by pressing the rule button on the right handside at the bottom
![image](https://user-images.githubusercontent.com/108178672/188962762-63f2c497-c346-419d-95bf-9479bfaa971d.png)



# **Testing**

***Validation***


![image](https://user-images.githubusercontent.com/108178672/188871330-8ec4c932-05c2-4f02-a51b-c1c37d1b4703.png)

I procceded to fix these errors by closing the div which fixed both errors at once. I also changed the first warning changing the list to all h2 elements.

![image](https://user-images.githubusercontent.com/108178672/188936007-3b576aac-9eac-4815-a566-7df9f6a5edae.png)

I had one warning that I deamed not necesary to change as I decied to a section was needed instead as I needed to add one for the buttons for my game to use so adding a h2 or any other (h element) I deemed unnecessary.

![image](https://user-images.githubusercontent.com/108178672/188935484-8a15aa98-f929-4174-bfd9-f733527e9f86.png)

The only issue that was found was a lack of smei-colons onthe first line of java script which was then swiftly correted.

# **Bugs and Issues Discovered**

I had a few issues when debugging my code such as:
- Had an issue where when correcting the relative filepaths within my code to make sure they where in an assets folder which required me to go in and manauly change all href links so that they would show on the page. this included javascript, images and my styles.
- An issue that i found was that I hadnt put my semicolons in the correct places inmy java which was easily changed and fixed by adding them.
- Had an issue when re-deploying my website through github after I had to take it down for re-deployment as the link was not showing happily it appeared to be a connection issue which resolved itself within 5-10 minutes.
# **Material used and References**
I uesed refrence material from who is a fellow student whos work I used as refrence material to help with the construction of my own game.
another would be from Competent Programming YouTube channel that i used to help construct my javascript with some helpful input. 

Links below.

https://www.youtube.com/c/CompetentProgramming

https://github.com/Robrowno/rock-paper-scissors


***aditional***

The start of my comits where bad as i didnt fully understand the commit message requirments but having recieved feedback have treid to make them more functional and easier to understand.