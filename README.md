# Project :

Building a simple calculator using Html Css and Javascript.

# requirements:

- The calculator should look like the above image

- The calculator should function like a normal calculator

- Do not implement % or .. You can assume everything will be an integer.

- C means clear. When a user clicks it, it should clear everything and go back to the first state it was in when the page loaded.

- Doing the back arrow is extra credit. It's like pressing backspace; it'll delete the last character typed. If it's clicked when there's only one digit, it sets the current number to be 0.

- Calculators tend to have some special behavior when you hit equals: if you type another number it erases the results and starts over. Feel free to do that but also free free (like me) to just treat it normally and make the user hit C if they want to clear it,Let's keep it simple.

# HTML and CSS Tips and Hints:

- Programming is all about taking large problems and breaking them into smaller problems. If you're trying to tackle too much at once, break it into two smaller problems and try to solve one of those.

- Personally, I wrote the HTML and CSS first. Once that's all taken care of, then I do the JavaScript,For the font of the "result screen" I'd just use monospace.

- There are so many ways to write this. There is no one right way. My solution is not the only nor is it the best solution. Experiment. Try. Fail. Succeed. It's all about learning here.

- Good idea to use <button></button> for the buttons. You have to deal with some extra styling stuff but it will make your code work pretty much automatically for disabled people. In general when writing HTML, if something serves the function of a button, make it a <button></button>.

- Sometimes I do the math to get things right. Sometimes I just guess-and-check to see if it looks okay.

- You can add a class to get the orange buttons. Or you could try :last-child (assuming you have row div.)

# Types:

- A brief note on what is called types in JavaScript. We've danced the idea already and I want to make it a little more concrete for you. Strings, booleans, objects, arrays, numbers, these are different types of types (lol). JavaScript is a language where you don't have to concern yourself a lot with types since it doesn't strictly enforce them (other languages do) but in this problem you are definitely going to have to deal with it.


Whatever you put into the DOM and whatever you get out it are going to strings, every time. If I do:
```javascript
const num = 10;
const div = document.querySelector(".number-target"); // the div right above this block
console.log(num, typeof num); // this is a number here
div.innerText = num;
console.log(div.innerText, typeof div.innerText); // it's a string here
```
```javascript
- result :
  10 "number"
 "10" "string"
  undefined
