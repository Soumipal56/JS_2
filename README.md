# Basic Operators (Arithmetic, Assignment, Increment, Decrement, Comparison, Logical, Bitwise)
##### Create two numbers a = 10 and b = 3. Perform and log: a + b, a - b, a * b, a / b, a % b.
#### Answer: 13, 7, 30, 3.3333333333333335, 1
##### Write: let x = 5; x = x + 3; Now rewrite the same using +=. Do the same for -=, *=, /=.
#### Answer: 
            let x = 5;
            x += 3;
            x -= 3;
            x *= 3;
            x /= 3;
##### let count = 5; Use count++ and log value before and after. Repeat for count--.
#### Answer: 5, 7, 7, 5
##### Compare two values: 5 == "5" and 5 === "5". Observe difference.
#### Answer: true, false. 5 == "5" -> not strict. Do not check the type, only the value. 5 === "5" -> strict. Checks both the type and value.
##### Check if 10 is greater than 5, less than 20, and equal to 10.
#### Answer: true, true, true
##### Try logical AND and OR: true && false, true || false, !(true)
#### Answer: false, true, false
##### Predict the result of: (5 > 3 && 10 > 8), (5 > 3 || 10 < 8)
#### Answer: true, true
##### Bitwise (light intro): Evaluate 5 & 1 and 5 | 1. Write result and your observation.
#### Answer: 1, 5. The bitwise &, | are used to perform operations as the numbers are first converted into bits.

# Variable Hoisting in JavaScript
##### Predict output of: console.log(a); var a = 10
#### Answer: undefined
##### Predict output of: console.log(b); let b = 10
#### Answer: ReferenceError
##### Predict output of: test() function test() { console.log("Hello") }
#### Answer: Hello
##### Try writing a function expression before initialization and call it:
##### hello() var hello = function() { console.log("Hi) } Write what happened and why.
#### Answer: TypeError. During hoisting, JS moves variable declarations to the top of the scope but not assignments.
##### Write one sentence: What gets hoisted? What does not get hoisted fully?
#### Answer: functions get hoisted var,let,const gets hoisted whereas var doesn't get initialized. 

# Conditional Operators (if, else, else-if, ternary, switch)
##### Take input using prompt for age. if age > 18 -> log "Adult". Else -> log "Minor"
##### Write a program: if marks >= 90 -> "A grade" Else if marks >= 75 -> "B grade" Else if marks >= 50 -> "C grade" Else -> "Fail"
##### Create a variable city = "Bhopal". "If city is “Bhopalˮ → log “MPˮ Else if city is “Delhiˮ → log “Capitalˮ Else → log “Unknown Cityˮ
##### Use ternary operator: Let score = 40. If score > 35  “Passˮ else “Failˮ using a ternary.
##### Convert this if-else into a ternary: if (temperature > 30) { "Hot" } else { "Pleasant" }
##### Write a switch case: Take day number (1 to 7). Print the day name. Default case: "Invalid Day".
      
