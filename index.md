# Part 1: Web Server  
<img width="620" alt="Screenshot 2023-01-29 at 12 16 29 AM" src="https://user-images.githubusercontent.com/122418243/215314081-5c5e8d10-6cb5-45ab-80aa-14ee158d53f3.png">
  
Running the server and using "add-message?s":  
<img width="534" alt="Screenshot 2023-01-28 at 11 39 30 PM" src="https://user-images.githubusercontent.com/122418243/215312672-a2965a40-ade2-4f15-9dd3-60fac35cd643.png">  
In the above screenshot I am using "add-message?s" to put "Hello World" on the screen. First the code checks the path of the url. If it sees that the directory path is "add-messages" it will execute the else if statement that has the condition "/add-messages" in code. Inside the else if statement the code store whatever is on the right side of equal sign in an array. Then it adds those information to a string variable. Which is why the value of "result" in the code gets updated to the elements in the array. I have added a dummy value in the beginning of the else if statement because it helps the code avoide any errors. Finally the code returns the value of "result" for the user to see.  
Another example of using "/add-message?s":  
<img width="602" alt="Screenshot 2023-01-28 at 11 39 56 PM" src="https://user-images.githubusercontent.com/122418243/215313877-1fa51ff0-1f1e-450a-acb6-b5c6d9e874b7.png">
In this screenshot I have used "/add-message?s" again. However instead of showing just the message I have input at the moment, the screen showed the previous one as well. This is because the value of "result" is whatever is stored in the array "collection". Previously collection only had whatever was given but the second time collection has the first input and second input. So second time the result value gets updated to the first and the second input. It does this using the for loop in the code. The loop stores information into "result" untill it reaches the last index of "collection". This is why the user sees the first and the second input.
# Part 2  
The method reversed in ArrayExamples has bug in it. The output of this method is always an array that has all zero in it.  
**Here is a screenshot of Symptom and test code**  
<img width="1143" alt="Screenshot 2023-01-28 at 9 46 31 PM" src="https://user-images.githubusercontent.com/122418243/215308320-7cef5999-795c-4f5a-adf4-82abbbf53e45.png">  
As you can see the only tests that are passing are the ones whose array is either empty or zero. This is because when there are no element in the array, so the code does nothing. However, when there are elements in the array, the code turns all of them into zeros. Which is why the arrays with zeros pass and the arrays containing non zero numbers fails.  
**Fixing the bug**  
TO fix the bug, first we must know the purpose of the method. In this case the purpose is to put the given array in reverse order. So for example if it was given this array:[1,2,3] the program must return this array[3,2,1]. What I noticed in the code is that, it was not copying the element from the old array to the new array its creating. So in order to fix the problem I had to create another for loop to copy all the elements of the previous array to the new array. Now the bug is fixed.  
  
  
**Here are screenshots of before and after the fix:**  
Before:  
<img width="332" alt="Screenshot 2023-01-28 at 9 38 58 PM" src="https://user-images.githubusercontent.com/122418243/215308444-bca467b4-1308-4d4c-ab96-af9d9f667a39.png">  
After:  
<img width="687" alt="Screenshot 2023-01-28 at 9 48 31 PM" src="https://user-images.githubusercontent.com/122418243/215308665-10403cfe-7a7a-4c76-83c5-763f49cfe7ba.png">   
The fix addresses the issue because instead of just creating another array will all zero element, it creates the array then copies the element from the previous array. As you can see in the after screenshot there is another for loop copying the elements from the previous array. So now the new array will not contain all zero. It will contain whatever was in the previos array.  

Here is a the test result after the fix:  
<img width="637" alt="Screenshot 2023-01-28 at 9 48 22 PM" src="https://user-images.githubusercontent.com/122418243/215314715-c83d21e7-e94e-4ba5-bd02-b752008c27c2.png">  
From the lab from week 2, I have learned how to create a search engine. Which helped me do this lab report with great efficiency. Knwoing how to Store data in a website is very important because any app you try to create, they will require you to store some types of variable. So learning this in lab from week 2 will help me a lot in the future as well.
