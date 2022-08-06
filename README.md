# JS- // way of capitalize first latter of a string without predefine method

var str='string is  way of wtiting Words';
var word= str.split(' ')
console.log(word)

for (let i=0;i<word.length;i++){

 word[i]=word[i].charAt(0).toUpperCase() + word[i].slice(1)
}

var newStr = word.join(' ')
console.log(newStr)
