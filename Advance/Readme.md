<pre>
  
const students=[{
    id: 1, name: 'Alice', score: 85
},{id: 2, name: 'Bob', score: 90},
 { id: 3, name: 'Charlie', score: 75 },
  { id: 4, name: 'Diana', score: 82 }
]
   


function getHighAchievers(students,passingScore){
    return students
    .filter(student=>student.score>=passingScore)
    .map(student=>student.name.toUpperCase());
}
const res=getHighAchievers(students,80);
console.log(res);


</pre>

**GAME**

<pre>
  
function createGame(){
    const secretNumber=Math.floor(Math.random()*10)+1;
    function guess(number){
        if(number===secretNumber){
            console.log("you guessed it");
        }else if(number>secretNumber){
            console.log("To high");
        }else{
            console.log("To low");
        }
    }
    return guess;
}
const play = createGame();
play(5)
</pre>
