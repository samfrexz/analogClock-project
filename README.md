# analogClock-project:

https://samfrexz.github.io/analogClock-project/

Infinite loop

An infinite loop, as the name suggests, is a loop that will keep running forever. If you accidentally make an infinite loop, it could crash your browser or computer. An example is:

const myNumber = 5;
while(myNumber > 0) {
console.log('hey there!')
}

For loop
A for loop repeats until a specified condition evaluates to false.

var txt = "";
var i;
for (i = 0; i < 5; i++) {
txt += "The number is " + i + "<br>";
}
console.log(txt);

for each loop:

The forEach() method calls a function once for each element in an array, in order.
let carTypes = ['volvo', 'benz', 'audi','acura']

carTypes.forEach(carType => console.log(carType))

for of loop
The JavaScript for/of statement loops through the values of an iterable object.
example:
let carTypes = ['volvo', 'benz', 'audi','acura'];
let txt = '';
for (let car of carTypes) {
txt += car + ','
}
console.log(txt)

foreach loop to loop through an array of objects

let laptopFeatures = [
{
chargerPort: true,
chargerType: 'type c',
screenSize: '14inches',
usbPorts: 3
},
{
keyboardLight: true,
chargerType: 'pin mouth',
operatingSystem: 'windows 8'
}
];
laptopFeatures.forEach(laptopFeature => {
console.log(laptopFeature.chargerType)
});
