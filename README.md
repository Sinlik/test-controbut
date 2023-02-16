
function ask ()
{
    let again = prompt("Try another problem?");

    if (again == "yes")
    {
        run();
    }

    if (again == "no")
    {
        console.log("Okay, well you could see your answer above. Refresh the page if you want to try again.");
    }
    
}

function run ()
{
    let v1 = prompt("What is your number?");
    let con = v1 * 1;
    let choice = con;

    let v2 = prompt("What should you add that number by?");
    let con_2 = v2 * 1;
    let add = con_2;

    let out = con + add;
    console.log("You chose: " + choice);
    console.log("Now, " + choice + " + " + add + " = " + out);
    ask();
}

run();
