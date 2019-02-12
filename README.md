#PRINT STRING NUM TIMES
---
##JAVASCRIPT CHALLENGE
---
in this challenge the function take two parameter,

the first parameter is a string while the second parameter

is an integer. the for loop is use to print the string num times

function str(str,num){

if(num<1){

return false

}
let arr=[]

for(var i=0; i<num;i++){

  arr[i]=str;

 document.getElementById('p').innerHTML+=arr[i]+'<br>';
 
}




}
str('max',10);
