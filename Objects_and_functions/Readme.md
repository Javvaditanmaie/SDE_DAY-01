### Objects & Functions

1. **[Easy]** Create an object named `movie` with properties for `title`, `director`, and `releaseYear`. Print the `title` of the movie to the console.
   <pre>
     const movie={
    title:"Avengers",
    director:"Anthony Russo",
    releaseYear:2012
}
console.log(movie["title"]);
   </pre>
   OUTPUT
  ![image](https://github.com/user-attachments/assets/68df5c19-12a3-4877-81d6-9e1067418fdb)

3. **[Medium]** Write a function called `printUserDetails` that takes a user object as an argument. The user object will have `name`, `email`, and `age` properties. The function should use object destructuring in its parameters to print a string like: `"User's name is [NAME], and they are [AGE] years old."`
   <pre>
     const info={
    name:"Tanmaie",
    email:"tanmaie@gmail.com",
    age:20
}
     function printUserDetails({name,email,age}){
    console.log(`User's name is ${name}, and they are ${age} years old.`)
}
printUserDetails(info);

   </pre>
   OUTPUT
   ![image](https://github.com/user-attachments/assets/656ee37d-e5f2-447e-a03c-cf38d3d5beb8)

   
5. **[Medium]** Create an array of user objects. Each object should have an `id` and a `username`. Use the `find` method to find the user with a specific `id`.
<pre>
  const user=[
    {id:123,username:"Tanmaie"},
    {id:124,username:"ramya"},
    {id:125,username:"niharika"}

]
const search = user.find(function(user){
    return user.id===123
});
console.log(search);

</pre>
OUTPUT
![Uploading image.png…]()
