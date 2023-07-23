# Some JavaScript exercises solved by me
## From CodeWars
***
exercise: [https://www.codewars.com/kata/55f9bca8ecaa9eac7100004a/train/javascript](https://www.codewars.com/kata/55f9bca8ecaa9eac7100004a/train/javascript)

```
function past(h, m, s){
  return h * 3600000 + m * 60000 + s * 1000;
}
```
***
exercise: [https://www.codewars.com/kata/56676e8fabd2d1ff3000000c](https://www.codewars.com/kata/56676e8fabd2d1ff3000000c)
```
let hayst = ["hay", "junk", "hay", "hay", "moreJunk", "needle", "randomJunk"];
function findNeedle(haystack) {
  return `found the needle at position ${haystack.findIndex((word) => {return word == "needle"})}`;
}
```
***
exercise: [https://www.codewars.com/kata/57a429e253ba3381850000fb/train/javascript](https://www.codewars.com/kata/57a429e253ba3381850000fb/train/javascript)
```
function bmi(weight, height) {
  let x = weight / Math.pow(height, 2);
  switch (true){
    case x <= 18.5: return "Underweight";
    case x <= 25.0: return "Normal";
    case x <= 30.0: return "Overweight";
    case x > 30: return "Obese";
  }
```
***
exercise: [https://www.codewars.com/kata/53369039d7ab3ac506000467/train/javascript](https://www.codewars.com/kata/53369039d7ab3ac506000467/train/javascript)
```
function boolToWord( bool ){
  if (bool == true){return 'Yes'};
  if (bool == false){return 'No'};
}
```

exercise: [https://www.codewars.com/kata/5769b3802ae6f8e4890009d2/train/javascript](https://www.codewars.com/kata/5769b3802ae6f8e4890009d2/train/javascript)
```
function removeEveryOther(arr){
  for (let i=1; i<arr.length; i++){
    arr.splice(i, 1);
  }
  return arr;
}
```

***
exercise: [https://www.codewars.com/kata/53ee5429ba190077850011d4/train/javascript](https://www.codewars.com/kata/53ee5429ba190077850011d4/train/javascript)
```
function doubleInteger(i) {
  i = i * 2;
  return i;
}
```
***
exercise: [https://www.codewars.com/kata/5772da22b89313a4d50012f7/javascript](https://www.codewars.com/kata/5772da22b89313a4d50012f7/javascript)
```
function greet(name, owner) {
  if (name == owner){return 'Hello boss';}
  else {return 'Hello guest';}
}
```
***
exercise: [https://www.codewars.com/kata/55cb632c1a5d7b3ad0000145/train/javascript](https://www.codewars.com/kata/55cb632c1a5d7b3ad0000145/train/javascript)
```
function hoopCount(n) {
  if (n >= 10) {return "Great, now move on to tricks"} else {return "Keep at it until you get it"};
}
```
***
exercise: [https://www.codewars.com/kata/57a0556c7cb1f31ab3000ad7/train/javascript](https://www.codewars.com/kata/57a0556c7cb1f31ab3000ad7/train/javascript)
```
function makeUpperCase(str) {
  return str.toUpperCase();
}
```
***
exercise: [https://www.codewars.com/kata/555086d53eac039a2a000083/train/javascript](https://www.codewars.com/kata/555086d53eac039a2a000083/train/javascript)
```
function lovefunc(flower1, flower2){
 if (flower1 % 2 == 0 && flower2 % 2 == 0){
  return false;
 } else if (flower1 % 2 == 1 && flower2 % 2 == 0){
  return true;
 } else if (flower1 % 2 == 1 && flower2 % 2 == 1){
  return false;
 } else if (flower1 % 2 == 0 && flower2 % 2 == 1){
  return true;
 }
}
```
***
exercise: [https://www.codewars.com/kata/56b1f01c247c01db92000076/javascript](https://www.codewars.com/kata/56b1f01c247c01db92000076/javascript)
```
function doubleChar(str) {
  return str.split("").map(c => c + c).join("");
}
```
***
exercise: [https://www.codewars.com/kata/57a0885cbb9944e24c00008e/train/javascript](https://www.codewars.com/kata/57a0885cbb9944e24c00008e/train/javascript)
```
function removeExclamationMarks(s) {
  let result = "";
  for (let i = 0; i < s.length; i++) {
    if (s[i] == '!'){result = result + ""}
    else {result = result + s[i]}
  }
  return result;
}
```
***
exercise: [https://www.codewars.com/kata/5966e33c4e686b508700002d/javascript](https://www.codewars.com/kata/5966e33c4e686b508700002d/javascript)
```
function sumStr(a,b) {
  return String(Number(a)+Number(b));
}
```
***
exercise: [https://www.codewars.com/kata/5ad0d8356165e63c140014d4/train/javascript](https://www.codewars.com/kata/5ad0d8356165e63c140014d4/train/javascript)
```
function finalGrade (exam, projects) {
  if (exam > 90 || projects > 10){return 100}
  else if (exam > 75 && projects >= 5){return 90}
  else if (exam > 50 && projects >= 2){return 75}
  else {return 0};
}
```
exercise: [https://www.codewars.com/kata/5265326f5fda8eb1160004c8/train/javascript](https://www.codewars.com/kata/5265326f5fda8eb1160004c8/train/javascript)
```
function numberToString(num) {
  return String(num);
}
```
***
exercise: [https://www.codewars.com/kata/53dbd5315a3c69eed20002dd/train/javascript](https://www.codewars.com/kata/53dbd5315a3c69eed20002dd/train/javascript)
```
function filter_list(l) {
  let l2 = [];
  for (let i=0; i<l.length;i++){
    if (typeof l[i] == 'number'){
      // l.splice(i, 1);
      l2.push(l[i]);
    }
  };
  return l2;
}
/* alternative
function filter_list(l) {
  return l.filter(function(v) {return typeof v == 'number'})
}
*/
```
***
exercise: [https://www.codewars.com/kata/5ab6538b379d20ad880000ab/train/javascript](https://www.codewars.com/kata/5ab6538b379d20ad880000ab/train/javascript)
```
const areaOrPerimeter = function(l , w) {
  if (l == w){return Math.pow(l, 2);}
  else {return 2*l+2*w;};
};
/* alternative
const areaOrPerimeter = function(l , w) {
  return l == w ? l*w : 2*(l + w)
};*/
```
***
exercise: [https://www.codewars.com/kata/5b853229cfde412a470000d0/train/javascript](https://www.codewars.com/kata/5b853229cfde412a470000d0/train/javascript)
```
function twiceAsOld(dadYearsOld, sonYearsOld) {
  if (dadYearsOld == 2*sonYearsOld){return 0;}
  else {return dadYearsOld > 2*sonYearsOld ? dadYearsOld-2*sonYearsOld : 2*sonYearsOld-dadYearsOld};
}
/* alternative
function twiceAsOld(dadYearsOld, sonYearsOld) {
  return Math.abs(dadYearsOld - 2 * sonYearsOld);
}*/
```
***
exercise: https://www.codewars.com/kata/53dc23c68a0c93699800041d/train/javascript
```
function smash(words) {
   return words.join(' ');
};
```
***
exercise: https://www.codewars.com/kata/5672a98bdbdd995fad00000f/javascript
```
const rps = (p1, p2) => {
  if (p1=='paper' && p2=='scissors'){return 'Player 2 won!';}
  else if (p1=='paper' && p2=='rock'){return 'Player 1 won!';}
  else if (p1=='paper' && p2=='paper'){return 'Draw!';}
  else if (p1=='rock' && p2=='paper'){return 'Player 2 won!';}
  else if (p1=='rock' && p2=='scissors'){return 'Player 1 won!';}
  else if (p1=='rock' && p2=='rock'){return 'Draw!';}
  else if (p1=='scissors' && p2=='rock'){return 'Player 2 won!';}
  else if (p1=='scissors' && p2=='paper'){return 'Player 1 won!';}
  else if (p1=='scissors' && p2=='scissors'){return 'Draw!';}
};
```
***
exercise: https://www.codewars.com/kata/57356c55867b9b7a60000bd7/train/javascript
```
function basicOp(operation, value1, value2){
  return eval(value1 + operation + value2);
}
```
***
exercise: https://www.codewars.com/kata/582cb0224e56e068d800003c/train/javascript
```
function litres(time) {
  return Math.floor(time * 0.5);
}
```
***
exercise: https://www.codewars.com/kata/54c27a33fb7da0db0100040e/train/javascript
```
var isSquare = function(n){
   return Number.isInteger(Math.sqrt(n));
}
```
***
exercise: https://www.codewars.com/kata/5502c9e7b3216ec63c0001aa/javascript
```
function openOrSenior(data){
  return data.map(x => x[0]>=55 && x[1]>7 ? "Senior" : "Open");
  /* alternative:
  let outp = [];
  for (let i=0; i<data.length; i++){
    if (data[i][0]>=55 && data[i][1]>7){
      outp = outp.push("Senior");
    } else {outp = outp.push("Open");};
  }
  return outp;
  */
}
```
***
exercise: https://www.codewars.com/kata/5513795bd3fafb56c200049e/javascript
```
function countBy(x, n) {
  let z = [];
  for (let i=1;i<=n;i++){z.push(x*i)};
  return z;
}
```
***
exercise: https://www.codewars.com/kata/56747fd5cb988479af000028/train/javascript
```
function getMiddle(s){
  s = s.split("");
  if (s.length % 2 == 0){
    return s[s.length/2 - 1] + s[s.length/2];
  } else {return s[(s.length + 1)/2 -1];};
}
```
***
exercise: https://www.codewars.com/kata/551b4501ac0447318f0009cd/train/javascript
```
function booleanToString(b){
  return String(b);
}
```
***
exercise: https://www.codewars.com/kata/55d24f55d7dd296eb9000030/javascript
```
var summation = function (num) {
  return num*(1+num)/2
}
```
***
exercise: https://www.codewars.com/kata/52fba66badcd10859f00097e/train/javascript
```
function disemvowel(str) {
  return str.replace(/[aeiou]/ig,'');
};
```
***
exercise: https://www.codewars.com/kata/542c0f198e077084c0000c2e/javascript
```
function getDivisorsCnt(n){
  let arr01 = [];
  for (let i=0; i<=n; i++){
    if (n%i == 0){
      arr01.push(i);
    };
  };
  return arr01.length;
};
```
***
exercise: https://www.codewars.com/kata/57a083a57cb1f31db7000028/javascript
```
function powersOfTwo(n){
  let ar01 = [];
  for (let i=0; i<=n; i++){
    ar01.push(Math.pow(2, i));
  };
  return ar01;
};
```
***
exercise: https://www.codewars.com/kata/523b623152af8a30c6000027/train/javascript
```
function square(i){return Math.pow(i, 2)};
```
***
exercise: https://www.codewars.com/kata/51f2b4448cadf20ed0000386/javascript
```
function removeUrlAnchor(url){
  return url.split('#')[0];
}
```
***
exercise: https://www.codewars.com/kata/558fc85d8fd1938afb000014/javascript
```
function sumTwoSmallestNumbers(numbers) {  
  return numbers.sort((a, b) => a-b)[0] + numbers.sort((a, b) => a-b)[1];
}
```
***
exercise: https://www.codewars.com/kata/529eef7a9194e0cbc1000255/train/javascript
```
var isAnagram = function(test, original) {
  return original.toLowerCase().split('').sort().join('') == test.toLowerCase().split('').sort().join('')?true:false;
};
```
***
exercise: https://www.codewars.com/kata/57a1fd2ce298a731b20006a4/train/javascript
```
function isPalindrome(x) {
  return x.toLowerCase() == x.toLowerCase().split('').reverse().join('')?true:false;
}
```
***
exercise: https://www.codewars.com/kata/5547929140907378f9000039/train/javascript
```
function shortcut (string) {
  return string.replace(/[aeiou]/gi,'');
}
```
***
exercise: https://www.codewars.com/kata/568dcc3c7f12767a62000038/train/javascript
```
function setAlarm(employed, vacation){
  return (employed == true && vacation == false) ? true : false;
}
```
***
exercise: https://www.codewars.com/kata/59441520102eaa25260000bf/javascript
```
function unusualFive() {
  return 'funny'.length;
}
```
***
exercise: https://www.codewars.com/kata/57ea5b0b75ae11d1e800006c/train/javascript
```
function sortByLength (arr) {
  return arr.sort((a, b) => a.length - b.length);
};
```
***
exercise: https://www.codewars.com/kata/55908aad6620c066bc00002a/javascript
```function XO(str) {
  let ar1 = str.split('').filter(word => word.match(/[x]/ig)).length;
  let ar2 = str.split('').filter(word => word.match(/[o]/ig)).length;
  return ar1 == ar2?true:false;
}
```
***
exercise: https://www.codewars.com/kata/578553c3a1b8d5c40300037c/train/javascript
```
function binaryArrayToNumber(arr02) {
  arr02 = arr02.reverse();
  let result = 0;
  for (let i=0; i<=arr02.length; i++){
    if(arr02[i] == 1){result = result + Math.pow(2, i)}
  }
  // return arr02.reverse().map(x => Math.pow(x, arr02));
  return result;
};
```
***
exercise: https://www.codewars.com/kata/55fab1ffda3e2e44f00000c6/javascript
```
function cockroachSpeed(s) {
  return Math.floor(s*1000*100/3600);
}
```
exercise: https://www.codewars.com/kata/576bb71bbbcf0951d5000044/javascript
```
function countPositivesSumNegatives(input) {
return input && input.length ? [input.filter(a => a>0).length, input.filter(b => b<0).reduce((c,d) => c+d, 0)] : [];
}
```
***
exercise: https://www.codewars.com/kata/5949481f86420f59480000e7/train/javascript
```
function oddOrEven(array) {
  return (array.reduce((a, b) => a+b, 0) % 2 == 0) ? "even": "odd";
}
```
***
exercise: https://www.codewars.com/kata/57eae20f5500ad98e50002c5/javascript
```
function noSpace(x){
return x.replace(/\s/g, '');
}
```
***
exercise: https://www.codewars.com/kata/54e6533c92449cc251001667/train/javascript
```
function uniqueInOrder(iterable){
  return Array.from(iterable).filter((a, b) => a != Array.from(iterable)[b+1]);
}
```
***
exercise: https://www.codewars.com/kata/563a631f7cbbc236cf0000c2/train/javascript
```
function move (position, roll) {
  return position + roll*2;
}
```
***
exercise: https://www.codewars.com/kata/55d1d6d5955ec6365400006d/javascript
```
function roundToNext5(n){
  return n % 5 == 0 ? n : Math.ceil(n/5)*5;
}
```
***
exercise: https://www.codewars.com/kata/577a98a6ae28071780000989/train/javascript
```
function min(list){
    return list.sort((a,b) => a-b)[0];
};
function max(list){
    return list.sort((a,b) => b-a)[0];
};
```
***
exercise: https://www.codewars.com/kata/577bd026df78c19bca0002c0/train/javascript
```
function correct(string){
	return string.replace(/0/g, "O").replace(/5/g, "S").replace(/1/g, "I");
};
```
***
exercise: https://www.codewars.com/kata/58cb43f4256836ed95000f97/train/javascript
```
function findDifference(a, b) {
  return a[0]*a[1]*a[2] > b[0]*b[1]*b[2]?a[0]*a[1]*a[2] - b[0]*b[1]*b[2]:b[0]*b[1]*b[2] - a[0]*a[1]*a[2];
};
```
***
exercise: https://www.codewars.com/kata/559ac78160f0be07c200005a/train/javascript 
```
function nameShuffler(str){
  return str.split(' ')[1] + ' ' + str.split(' ')[0];
};
```
***
exercise: https://www.codewars.com/kata/55ad04714f0b468e8200001c/javascript
```
function getChar(c){
  return String.fromCharCode(c);
};
```
***
exercise: https://www.codewars.com/kata/57a4d500e298a7952100035d/train/javascript
```
function hexToDec(hexString){
  return parseInt(hexString, 16);
};
```
***
exercise: https://www.codewars.com/kata/5b077ebdaf15be5c7f000077/train/javascript
```
var countSheep = function (num){
  let str01 = "";
  for (let i=1; i<=num; i++){str01 = str01 + i + " sheep..."}
  return str01;
};
```
***
exercise: https://www.codewars.com/kata/57a55c8b72292d057b000594/train/javascript
```
function reverse(string){
  return string.split(' ').reverse().join(' ');
};
```
***
exercise: https://www.codewars.com/kata/57fb09ef2b5314a8a90001ed/javascript
```
function replace(s){
  return s.replace(/[aeiouAEIOU]/g, "!");
};
```
***
exercise: https://www.codewars.com/kata/55b42574ff091733d900002f/javascript
```
function friend(friends){
  return friends.filter(x => x.length == 4);
};
```
***
exercise: https://www.codewars.com/kata/52f3149496de55aded000410/train/javascript
```
function sumDigits(number) {
  return Math.abs(number).toString().split('').reduce((a, b) => Number(a) + Number(b), 0);
};
```
***
exercise: https://www.codewars.com/kata/568d0dd208ee69389d000016/train/javascript
```
function rentalCarCost(d) {
  return d>=3 ? (d>=7 ? d*40-50 : d*40-20) : d*40;
};
```
***
exercise: https://www.codewars.com/kata/576757b1df89ecf5bd00073b/javascript
```
function towerBuilder(nFloors) {
  return Array.from({length: nFloors}, (a, b) => {return ' '.repeat(nFloors - b - 1) + '*'.repeat(b + b + 1) + ' '.repeat(nFloors - b - 1);});
};
```
***
exercise: https://www.codewars.com/kata/58b8c94b7df3f116eb00005b/javascript
```
function reverseLetter(str) {
  return [...str].reverse().filter(x => x.match(/[a-z]/ig)).join(''); 
}
```
***
exercise: https://www.codewars.com/kata/54ff0d1f355cfd20e60001fc/javascript
```
function factorial(n){
  if (n < 0 || n > 12)
    throw new RangeError();
  return n <= 1 ? 1 : n * factorial(n - 1);
};
```
***
exercise: https://www.codewars.com/kata/559590633066759614000063/javascript
```
function minMax(arr){
  return [Math.min(...arr), Math.max(...arr)];
};
```
***
exercise: https://www.codewars.com/kata/554b4ac871d6813a03000035/javascript
```
function highAndLow(numbers){
  return String(Math.max(...numbers.split(' ')) + ' ' + Math.min(...numbers.split(' ')));
};
```
***
exercise: https://www.codewars.com/kata/54ff3102c1bad923760001f3/javascript
```
function getCount(str) {
  return str.match(/[aeiou]/g) == null ? 0 : str.match(/[aeiou]/g).length;
};
```
***
exercise: https://www.codewars.com/kata/546e2562b03326a88e000020
```
function squareDigits(num){
  return Number(String(num).split('').map(x => x**2).join(''));
}
```
***
exercise: https://www.codewars.com/kata/5467e4d82edf8bbf40000155
```
function descendingOrder(n){
  return Number(String(n).split('').sort((a,b) => b-a).join(''));
}
```
***
exercise: https://www.codewars.com/kata/5667e8f4e3f572a8f2000039
```
function accum(s) {
  return s.split('').map((c, i) => (c.toUpperCase() + c.toLowerCase().repeat(i))).join('-');
}
```
***
exercise: https://www.codewars.com/kata/54ba84be607a92aa900000f1/train/javascript
```
function isIsogram(str){
  return new Set(str.toLowerCase()).size == str.length;
};
```
***
exercise: https://www.codewars.com/kata/55f2b110f61eb01779000053/javascript
```
function getSum(a, b){
  return (Math.min(a,b)+Math.max(a,b))/2 * (Math.max(a,b) - Math.min(a,b) + 1);
};
```
***
exercise: https://www.codewars.com/kata/56269eb78ad2e4ced1000013
```
function findNextSquare(sq) {
  return Number.isInteger(Math.sqrt(sq)) == true ? Math.pow(Math.sqrt(sq) + 1, 2) : -1;
};
```
***
exercise: https://www.codewars.com/kata/551f37452ff852b7bd000139
```
function addBinary(a,b) {
  return (a+b).toString(2);
};
```
***
exercise: https://www.codewars.com/kata/56606694ec01347ce800001b
```
function isTriangle(a,b,c){
   return (a+b)>c?(b+c)>a?(a+c)>b?true:false:false:false;
}
```
***
exercise: https://www.codewars.com/kata/55fd2d567d94ac3bc9000064
```
function rowSumOddNumbers(n) {
  return Math.pow(n, 3);
};
```
***
exercise: https://www.codewars.com/kata/51f2d1cafc9c0f745c00037d
```
function solution(str, ending){
  return new RegExp(ending + "$").test(str);
}
```
***
exercise: https://www.codewars.com/kata/5259b20d6021e9e14c0010d4
```
function reverseWords(str) {
  return str.split(' ').map(x => x.split("").reverse().join("")).join(" ");
}
```
***
exercise: https://www.codewars.com/kata/554e4a2f232cdd87d9000038
```
function DNAStrand(dna){
  return [...dna].map(x => x == "A" ? "T" : x == "T" ? "A" : x == "C" ? "G" : x == "G" ? "C" : "?").join('');
};
```
***
exercise: https://www.codewars.com/kata/5813d19765d81c592200001a
```
function dontGiveMeFive(start, end){
  return new Array(end - start + 1).fill().map((_, i) => start + i).filter(x => !/5/.test(String(x))).length;
};
```
***
exercise: https://www.codewars.com/kata/534ea96ebb17181947000ada
```
function breakChocolate(n,m) {
  return n<1 || m<1 ? 0 : (n-1) + n * (m-1);
}
```
***
exercise: https://www.codewars.com/kata/5412509bd436bd33920011bc
```
function maskify(cc) {
  cc = cc.toString().split('');
  if (cc.length > 4){
    for (let i=0; i<cc.length - 4; i++){
    cc[i] = '#';
  }
  }
  return cc.join('');
}
```
***
***
### License
Copyright (c) 2023, heEXDe All rights reserved. Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. The views and conclusions contained in the software and documentation are those of the authors and should not be interpreted as representing official policies, either expressed or implied, of the FreeBSD Project.