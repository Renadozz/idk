a calculator that can do basic math (+ , - , * , / ,)

Requirements:
- Use the Scanner Class for the Input. (https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Scanner.html)
- Make a own claculator class
- Seperate logic between the Main methode and the calculator class
- Think about useful PRINT(LN) texts
- The input can look like "30 + 10 * 5 / (2 - 1)"  <-- make sure it will be calculated correctly
- Use a REGEX to validate the Input
- Use this Libary for the Regex (https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/regex/Pattern.html)
- DO NOT use any other libraries!
- Make sure the input works with and without any withespaces
- Think about edge cases (at which point does a calculation fail?)
- When you start it, it only should end when you write "exit"
- Make an Custom ExceptionHandler and make usefull exceptions for cases like wrong input because of a letter.
- Think about useful data structures.

- Example:

-> Hello I am a simple calc! (wirte "exit" to leave)
-> What can I do for you today?
-> Input: 30 + 10 * 5 / (2 - 1)
-> Output: 80
-> Input: lsdifgjldfj
-> Not able to calc, cause of ...
-> Input: exit
-> Thank you for using the simple calc! - Bye!