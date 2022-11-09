//projectCreator
//The code is able to calculate the hours needed from an architect to complete a certain project, considering 3 hours per project. The console is printing the architects name (input), hours needed + sum of the projects.
function projectCount(input) {
    let name = input[0];
    let pc = input[1];
    let hrs = pc * 3
    console.log(`The architect ${name} will need ${hrs} hours to complete ${pc} project/s.`)
}
