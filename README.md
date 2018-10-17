# hTask1
var a = 2 + 2
console.time(a)
switch (a) {
    case 3:
        console.log ('small');
        break;
    case 6:
        console.log ('correct');
        break;
    case 5:
        console.log ('many_value');
        break;
    default:
        console.log ('no_yet_value');
        console.timeEnd(a);


var b = 2 + 2
        console.time(b)
        if (b === 3) {
            console.log('small');
        } else if (b === 6) {
            console.log('correct');
        } else if (b === 5) {
            console.log('many_value');
        } else {
            console.log('no_yet_value')
            console.timeEnd(b)
        }
        console.log()
}
