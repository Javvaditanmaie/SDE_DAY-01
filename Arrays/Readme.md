### Arrays

1. **[Easy]** Create an array named `colors` with three of your favorite colors.
    - Add a fourth color to the end of the array.
    - Add a new color to the beginning of the array.
    - Print the final array to the console.
<pre>
  let colors=["red","green","Blue"];
colors.push("yellow");
colors.unshift("pink");
console.log(colors);
</pre>

OUTPUT
[ 'pink', 'red', 'green', 'Blue', 'yellow' ]
S
2. **[Medium]** Given the array `let numbers = [10, 20, 30, 40, 50];`, use the `map` method to create a new array where each number is increased by 5.
<pre>
  let numbers = [10, 20, 30, 40, 50];
const double=numbers.map(function(number){
    return number+5;
})
console.log(double);
</pre>
output
![image](https://github.com/user-attachments/assets/2233f46a-4341-4032-a373-cf9ab2508d0a)

3. **[Medium]** Given the array `let scores = [25, 80, 45, 95, 60, 75];`, use the `filter` method to create a new array containing only the scores that are 70 or higher.
   <pre>
     let scores = [25, 80, 45, 95, 60, 75];
const higherscore=scores.filter(function(scores){
    return scores>=70;

});
console.log(higherscore);
   </pre>
   
output
   ![image](https://github.com/user-attachments/assets/8f353803-f11e-4098-b82d-946bf763c6d5)

4. **[Hard]** Use the `reduce` method on the `scores` array from the previous question to calculate the average score. (Hint: sum all scores and then divide by the number of scores).
<pre>let scores2 = [25, 80, 45, 95, 60, 75];
const total=scores2.reduce(function(accumulator,currentVale){
    return accumulator+currentVale;

},0)
console.log(total/scores2.length);
</pre>
output
63.333333333333336
