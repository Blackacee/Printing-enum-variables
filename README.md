# Printing-enum-variables
 
// Define the enum
var ColorsEnum = { WHITE: 0, GRAY: 1, BLACK: 2 }
Object.freeze(ColorsEnum);
// Define the variable and assign a value
var color = ColorsEnum.BLACK;
if(color == ColorsEnum.BLACK) {
 console.log(color); // This will print "2"
 var ce = ColorsEnum;
 for (var name in ce) {
 if (ce[name] == ce.BLACK)
 console.log(name); // This will print "BLACK"
 }
}
