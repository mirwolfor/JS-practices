confirm("Welcome to the worst version of Rock, Paper, Scissors. If you don't win you're a pussy. Press OK to continue!")
*//*

var userChoice = prompt("Do you choose rock, paper or scissors?")
    if (userChoice === "rock") {
    userChoice = "rock";
}
else if (userChoice === "paper") {
    userChoice = "paper";
}
else if (userChoice === "scissors") {
    userChoice = "scissors";
}
else {
      userChoice = prompt("Whoops! It appears you have made an invalid selection. Please choose rock, paper, or scissors");
}
var computerChoice = Math.random();
if (computerChoice < 0.34) {
    computerChoice = "rock";
} else if(0.34 > computerChoice <= 0.67) {
    computerChoice = "paper";
} else {
    computerChoice = "scissors";
} console.log("Computer: " + computerChoice);

var compare = function(choice1, choice2){
if(choice1 === choice2){
    return "The result is a tie!";
}
else if(choice1 === "rock") {

    if(choice2 === "scissors") {
        return "rock wins";
    }
    else {
        return "paper wins";
    }
}
else if(choice1 === "paper"){
    
    if(choice2 === "rock"){
        return "paper wins";
}
else {
    return "scissors wins";
}
}

else if(choice1 === "scissors"){
    if(choice2 === "paper"){
    return "scissors wins";
} else {
    return "rock wins";
}
}
}
console.log(compare(userChoice, computerChoice));




