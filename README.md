# TypeScript-Exercise-14
The provided TypeScript code is a simple program that demonstrates how to create a guest list and invite people, both living and deceased, to dinner. It's an example of using arrays and iteration to perform a specific task. This code can be useful for beginners learning TypeScript or programming in general.

Here's an explanation of the code:

1. **Creating the Guest List**:
   The code starts by defining an array called `guestList`. This array will hold the names of the people you'd like to invite to dinner. The list includes both living and deceased individuals, making it an interesting mix of historical figures, scientists, and modern personalities.

2. **Adding Names to the Guest List**:
   The `guestList` array is populated with various names, such as "Albert Einstein," "Marie Curie," "Nelson Mandela," "Elon Musk," "Ada Lovelace," and more. You can add additional names to the list by appending them to the array.

3. **Inviting Guests**:
   The code then utilizes a `forEach` loop to go through each name in the `guestList` array. The loop iterates over all the names and executes the code block for each element of the array.

4. **Printing Invitations**:
   Inside the loop, a personalized invitation message is constructed for each guest. The `console.log()` function is used to print the invitation message to the console. The message includes the name of the guest, regardless of whether they are living or deceased, and an invitation to join the dinner.

5. **Output**:
   When you run the code, it will produce an output where each guest will receive a personalized invitation to dinner. The console will display messages like:
   ```
   Dear Albert Einstein, you are invited to dinner. Please join us for an evening of good food and conversation.
   Dear Marie Curie, you are invited to dinner. Please join us for an evening of good food and conversation.
   Dear Nelson Mandela, you are invited to dinner. Please join us for an evening of good food and conversation.
   ...
   ```

This code is a fun and creative way to showcase the use of arrays and loops in TypeScript while inviting both historical and modern figures to an imaginary dinner. It can be a great starting point for learning about data structures, iteration, and string interpolation in TypeScript.
