
# Grep command
[Citation](https://www.geeksforgeeks.org/grep-command-in-unixlinux/)  

**Command Option: -i**  
The command -i is ignoring the case sensitivity of you input. It will look for all the files that match the pattern, ignoring the case of the letters. This is very useful tool for searching for case sensitive file to narrow down your search. For example let's say you are looking for a file in a huge file collection but you forgot if the file you looking for have the first letter as uppercase of lower case. Thats when you can use this command to look for your file.  
In the example below we can see that without the -i commans it shows nothing but when we use the command it shows the files containing the pattern.  
<img width="655" alt="Screenshot 2023-02-12 at 10 28 06 PM" src="https://user-images.githubusercontent.com/122418243/218386581-029ddcb7-83f0-4fce-aca8-f45dee0d5031.png">  
This example we use the same patter but this time we use upper case and lower case letters for the pattern. However, we get the same output as last time. Which shows that this is not case sensative.  
<img width="661" alt="Screenshot 2023-02-12 at 10 31 31 PM" src="https://user-images.githubusercontent.com/122418243/218387052-9f7575b1-d61f-4e60-ad41-821e6531d122.png">  
**Command Option: -c**  
The command -c tells use the number of files of the given pattern. This becomes very useful if you want to know how many files you have under certain name.  For example this is useful in a situation when your computer storage is full and you want to look for duplicate files to delete. Also becomes useful when you are looking for a specific files and you don't know if the file is in that directory.  
In this example below you can see that we used the command to see if we have any files of that name. The command returns how many files we have of that pattern.  
<img width="569" alt="Screenshot 2023-02-12 at 10 47 47 PM" src="https://user-images.githubusercontent.com/122418243/218389624-1e6738ae-d1a8-44af-bb85-6d1f29f07e7d.png">  
The pattern is case sensative. In this example we can see that the same pattern was input but with lower case w. So we got 0 as a result.  
<img width="525" alt="Screenshot 2023-02-12 at 10 49 16 PM" src="https://user-images.githubusercontent.com/122418243/218389870-42ba5a29-3e37-496c-9779-657aeecf486c.png">  
**Command option: -w**  
The command -w looks for the sentence in the file that contains the given pattern. This can be useful when you are editing a very important paper and you do not want to repeat a word too many times. So you can use this command to see how many times you have used this word in a sentence.  
In this example below you can see that the command returned the lines that had the given pattern. We can see that we have not used this pattern many times in out writing. Which us good.  
<img width="564" alt="Screenshot 2023-02-12 at 11 18 57 PM" src="https://user-images.githubusercontent.com/122418243/218394795-5a6513f0-84e9-4976-910b-da6be19431db.png">  
In this example we can see that we have used the word "and" too many times and may need to change few of them if we don't want them to repeat this much.   
<img width="642" alt="Screenshot 2023-02-12 at 11 20 04 PM" src="https://user-images.githubusercontent.com/122418243/218394991-1017e6c8-ce7d-4f4d-87cb-a3767b6c7248.png">  
**Command option: -n**  
Similar to the command -w, this command gives us the line number of where the given pattern was used. This can be useful if you are looking for a keyword in a sentence. Let's say you are writing about a reading for a class and the citation is very important. You have copy and pasted a quote from the reading but you forgot what line it was one. In this situation you can use this command to find what line your quote was in and cite your paper the proper way.  
In the example below we can see that the output gave us the line number of where the given patter was used.  
<img width="647" alt="Screenshot 2023-02-12 at 11 51 51 PM" src="https://user-images.githubusercontent.com/122418243/218400688-7783d736-5211-4f89-bed8-da3c4589bf6f.png">  
In this example we used another word to show you how this command works. Notice how it does not show anything when I input "idk" this is because there was no word like that in the file. However when I typed "Though" it gave us the output of where the line was.  
<img width="596" alt="Screenshot 2023-02-12 at 11 53 51 PM" src="https://user-images.githubusercontent.com/122418243/218401113-fbf58729-9f8d-4666-8d0c-e81cb2429146.png">
