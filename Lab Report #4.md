# Baseline  
First I logged into the ieng6 server. To do this I put my specific ieng6 email id. Which should look something like this: 
ssh cs15lwi23zz@ieng6.ucsd.edu. Instead of the "zz" I put my own specific username. Then I pressed `<enter>`. Then it asked for password. Then I provided my password.
After succesfull email and password. I got a screen that looks like this:  
<img width="586" alt="Screenshot 2023-02-25 at 11 22 36 PM" src="https://user-images.githubusercontent.com/122418243/221397702-ef5da1fa-3ffc-4a61-9740-713b4d569249.png">  
 The above screenshot shows that I have successfully loged into the ieng6 server. 
  Then I forked the given repository. After forking it, I pressed on the green code button. Then copy the given link from there using `command + c`. Then use the command "`git clone`" which is used to clone a repository in the terminal. Then I pressed `<space>` and then I pasted the link I copied from githib using `command + v`. Then I got a screen that looKed like this:  
  <img width="557" alt="Screenshot 2023-02-25 at 11 34 20 PM" src="https://user-images.githubusercontent.com/122418243/221398105-f9383030-329a-4276-a0fb-ad08dc0a203e.png">  
  As you can see in the screenshot, It showed that I have successfully cloned the files in the terminal.  
  Then I used `cd` to go into the directory "`lab7/`" so I can compile and run it. To cd into lab7/ I typed cd `<space>` la`<tab>`. After going to lab7/, i  complieD it using 
  the command: `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` `<enter>`. I copy and pasted this from week three lab page.  
  Then run the test using: `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests` `<enter>`. Which I also
  copy and pasted from week three lab page. 
  After, I get a screen which shows me that the tests that were in the file ListExamplesTests failed.  
  <img width="995" alt="Screenshot 2023-02-25 at 11 45 26 PM" src="https://user-images.githubusercontent.com/122418243/221398508-c7c10c8d-a1e8-4df7-ba38-6307c1a59ba9.png">  
  Then I typed L`<tab>`.java. I used tab to autofill the rest of the file name. Then I pressed `<enter>`. Which brought me to this screen:  
  <img width="1229" alt="Screenshot 2023-02-25 at 11 57 41 PM" src="https://user-images.githubusercontent.com/122418243/221398987-83e3df8c-13f7-4a0c-92b4-aceeed32425a.png">  
  Then I typed `ctrl + w` which brought up a search bar. In which I typed "`index1 += 1;`". This command searches for the word given. So it took me to on of the lines which contained the given input. But that was not the line I wanted to edit. Then I pressed the `<down>` key 13 times to get to the desired line. After that I pressed `<right>` key 3 times. Which borught me to the place where I wanted to edit. 
  After that I pressed `<delete>` which deleted one character. After then I pressed "2" which will fix the bug and will pass all the tests. Then I pressed
  `ctrl + x`. This comand will make me exit the current screen. Before exiting, it gave me a screen like this  
  <img width="1108" alt="Screenshot 2023-02-26 at 12 11 18 AM" src="https://user-images.githubusercontent.com/122418243/221399466-cd898ec6-9c28-4040-94d9-56bf935456d3.png">  
  Which asks if I want to save the edits I made or not. To save any edit made press `Y` if not press `N`. In my case I pressed `Y`. Which will save the edit I made.
  Then press `<enter>` Which will exited the current screen and saved the edit I made. Now if I run the same command to comple and run it will pass.
  To run and compile I pressed `<up>` three times which will give the command to compile that was in my history. Then I pressed `<enter>`. After that, I pressed `<up>` twice to get to the run command that was in my history. Then press `<enter>`. After that it shows me a screen like this:  
    <img width="996" alt="Screenshot 2023-02-26 at 12 21 37 AM" src="https://user-images.githubusercontent.com/122418243/221399875-d1feb1eb-0eb3-40db-adea-6d4fb59fdded.png">  
Which shows that I have passed all the tests! Which means that I have fixed the bug!
To push the change into the repository in github I used the command git add, which adds the given file nad makes it ready for you to commit the changes. So, I typed git add L `<tab>` .java to make it ready to be commited. Then I typed `git commit -m "Fixed"` to push the edit made into my github account. The command `git commit` pushes the the changed made into the repository and prints out the message given inside quotation. After this it game a screen that looked like this:  
<img width="485" alt="Screenshot 2023-02-26 at 8 15 30 PM" src="https://user-images.githubusercontent.com/122418243/221472898-4df82ebd-85bd-4851-980e-afdabfd9a533.png">
Which shows how many edits I have made and prints out the messages I wanted.
