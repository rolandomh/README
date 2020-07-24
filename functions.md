# functions
#
#Requirements
Add at least 3 dynamic components to your web page. These can be based on user input, or other dynamic input data.

At least one dynamic component should be based on user input.

At least one dynamic component should use a conditional statement to determine the output.
$$$$

`what follows is my full .js code page...note the addition of a double negative with a BANG!`

`var userName = prompt('whats your username?');

while(!( userName == '')){
    userName = prompt('type 4!');
}

function confirmAskQuestions(){
    confirm(userName + ' I am going to ask you some questions!');
}
confirmAskQuestions();

function askQuestion(){
    var userCodeAnswer = prompt('Do you enjoy writing code? (yes or no)');
    if (userCodeAnswer == "yes"){
        alert('I do too');
        
    }else if (userCodeAnswer == "maybe"){
        alert('to bad so sad');
    }
    
    
    
    else {
        alert('That is too bad.  It is so much fun');
    }
}
askQuestion();


function askTime(){
    var userTimeInFunction = prompt('What hour is it in military time 0-24?');
    return userTimeInFunction;
}
var userTime = askTime();


function checkTime(){
    if(userTime < 12){
        alert('Good Morning');
    } else if (userTime >= 12 && userTime < 18){
        alert('Good Afternoon');
    } else {
        alert('Good Evening');
    }
}
checkTime();
   

var wannaPlay = prompt('Do you want to play a guessing game, enter 1, if not enter 2');

var correctAnswer = 12;


while(wannaPlay == 1){
    for (var i = 0; i < 10; i = i + 1){
        var userAnswer = prompt('Please enter a number between 1 and 20');
        if(userAnswer == correctAnswer){
            wannaPlay = prompt('DING DING DING.  You got it right. Wanna play again?1 for yes, 2 for no');
            break;
        }
        // if( userAnswer == (''))
        
        
        else {        
            if (userAnswer < correctAnswer){
                alert('Incorrect, to low.  Try Again.');
            } else {
                alert('Incorrect, to high.  Try Again.');
            }
        }
    }
}


 alert(userName + 'your fly is down.');

function alertMe(){
    alert('heres a massage');
}
for(var x = 0;x < 6 ; x = x + 1){
    alertMe();
}`