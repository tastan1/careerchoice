var user = prompt("You have just graduated Highschool as an All American Athlete! Congradulations! Now its time to pick your Professional sports path(Football, Basketball, Baseball, or Soccer )...Good luck!","Enter your career choice here").toLowerCase();

switch(user){
    case 'football':
        var stong = prompt("Are you strong enough? 'yes' or 'no'!").toLowerCase();
        var fast = prompt("Are you fast? yes/no ").toLowerCase();
        if (stong === 'yes' && fast === 'yes'){
            console.log("You will be an excellent football player! Congradulations");
        } else {
            console.log("You should choose a different career path!");
        }
        break;
    case  'basketball':
        var dunk = prompt("Can you dunk? 'yes' or 'no'!").toLowerCase();
        var dribbleBall = prompt("Can you dribble a basketball? yes/no ").toLowerCase();
        if (dunk === 'yes'&& dribbleBall=== 'yes'){
            console.log("You will be an excellent basketball player! Congradulations");
        } else {
            console.log("You should choose a different career path!");
        }
        break;
    case  'baseball':
        var coordinate = prompt("Do you have good hand eye coordiantion? 'yes' or 'no'!").toLowerCase();
        var hitBall = prompt("Can you hit a ball? yes/no ").toLowerCase();
        if (coordinate === 'yes' && hitBall === 'yes'){
            console.log("You will be an excellent baseball player! Congradulations");
        } else {
            console.log("You should choose a different career path!");
        }
        break;
    case  'soccer':
        var kickball = prompt("Can you kick a ball? 'yes' or 'no'!").toLowerCase();
        var fast = prompt("Are you fast? yes/no ").toLowerCase();
        if (kickball === 'yes'|| fast === 'yes'){
            console.log("You will be an excellent soccer player! Congradulations");
        } else {
            console.log("You should choose a different career path!");
        }
        break;
        default:
            console.log("I dont like sports! I will become a lawyer!");
        
    
}