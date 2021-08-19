Test: "It should be able to create a roman numeral for each coresponding number."
Code:
const number = [1,2,3,4,5];
expected output: [I, II, III, IV, V];

Test: "It should be able to add the value of roman numeral symbols."
Code:
const numeral = V
const newNumeral = (numeral + numeral)
expected output: newNumeral; X

Test: "It should detect when we reach four of the same symbol, subtract it by three and add one of the next subsequent symbols.
Code:
const alterNumeral = (numeral + newNumeral - (3 * numeral))

Test: "It should be able to keep ones, tens, hundreds, and thousands seperate."
Code:
if number >= 1000 
numeral = M