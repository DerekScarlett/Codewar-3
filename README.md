# Codewars 3

Question: Convert an string to a number

Solution:

var stringToNumber = function(str){
  var num = parseInt(str);
  return num;
}

So what I did for this problem here is that I made a function expression  stringToNumber, then in my function I take in a parameter (str). In my function I creat a local varible called num that is assighed a value parseInt(str). parseInt() is a javascript method that converts a string into a number. Then I return num.

For example:

var stringToNumber = function("100"){
  var num = parseInt("100");
  return num;
}
console.log(stringToNumber); // 100
