## Tasks

1.
Create a variable named input that is equal to any phrase you’d like. This variable will contain the text you want to translate into “whale talk”.


Stuck? Get a hint
2.
Whales only speak in vowels so you need an array of vowels to be extracted from the input variable. Set the array equal to a variable named vowels that will not be updated.

Note: Whales don’t consider “y” a vowel.


Stuck? Get a hint
3.
Create a variable named resultArray and set it equal to an empty array: []. This will serve as a place to store the vowels from the input string.

4.
Create a loop to iterate through each letter of the input variable text. In a later step, we will compare each letter with our vowels array.


Stuck? Get a hint
5.
To check your work, log the iterator numbered position inside the for loop and run your code. This should count the number of characters in your input string.

Comment out this code when you’re ready to move on.


Stuck? Get a hint
6.
Create a nested for loop inside of the for loop you just wrote. Make the inner loop iterate through the vowels array each time the outer loop runs.

This will enable you to check each letter of input against all the vowels elements during each iteration.


Stuck? Get a hint
7.
To check your work, log the iterator number positions inside the inner for loop and run your code. You should see 0 through 4 repeatedly because vowels is 5 elements long.


Stuck? Get a hint
8.
Inside the second for loop, write a code block that compares the input letter to every letter in the vowels array.


Hint
Use the .push() method to add matching letters to the array that stores the results. To single out letters from a string use stringName[i] and compare it to the array.

stringName[i] works just like accessing an element within an array. That’s because JavaScript internally stores every character in a string at a numbered position.

9.
Whales double their e‘s and the u‘s in their language.

Write an if statement that checks if each letter in the input string is equal to 'e'. If so, .push() input[i] to the resultArray.

Note, this statement belongs after the inner for loop block inside the outer for loop. This is because you only want to perform this check once for every letter in the input.


Stuck? Get a hint
10.
Next, you want to double the letter u, so you must mimic the code from the last step. Re-create the if statement, but modify it so it pushes the letter u a second time.


Stuck? Get a hint
11.
At the bottom of the program, log resultArray to the console.

12.
Notice when we log the array, the output has commas between each letter. To produce proper whale language, we want to capitalize the array elements and put them together as one string.


Stuck? Get a hint
13.
Run the program and sing the output out loud — you officially speak whale!

To confirm, if you change the value of input to ‘turpentine and turtles’, the whale version would read: 'UUEEIEEAUUEE'.

Try other tests like 'Hi, Human' (to get IUUA) or 'a whale of a deal!' (to get 'AAEEOAEEA').
