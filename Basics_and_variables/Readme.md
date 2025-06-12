
/*1. **[Easy]** Declare a variable named `favoriteFood` using `const` and assign it a string value of your favorite food. Print it to the console.
2. **[Easy]** Create two variables, `numA` and `numB`, and assign them number values. Write an `if/else` statement to print which number is larger or if they are equal.*/
const favoriteFood="panipuri";
console.log(favoriteFood);

<pre>let numA=10;
let numB=29;
if(numA>numB){
    console.log(numA);
}else{
    console.log(numB);
}
if(numA===numB){
    console.log("true");
}else{
    console.log("false");
}</pre>

output

![image](https://github.com/user-attachments/assets/197149a1-9e1f-4cdb-af31-3f01bf078a16)

/**[Medium] Write a for loop that prints the numbers from 1 to 20. For multiples of 3, print "Fizz" instead of the number. For multiples of 5, print "Buzz". For numbers which are multiples of both 3 and 5, print "FizzBuzz" */
<pre>for(let i=0;i<=20;i++){
    if(i%3===0 && i%5===0){
        console.log("Fizz");
    }else if(i%5===0){
        console.log("Buzz");
    }else if(i%3===0){
        console.log("FizzBuzz");
    }else{
        console.log(i);
    }

}</pre>

Output
![image](https://github.com/user-attachments/assets/ac73460b-4673-4b46-93b2-375b2bb7db7e)
