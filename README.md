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
exercise: https://www.codewars.com/kata/56541980fa08ab47a0000040
```
function printerError(s) {
    return `${[...s].filter(x => x.match(/[n-z]/)).length}/${s.length}`
}
```
***
exerceise: https://www.codewars.com/kata/5648b12ce68d9daa6b000099
```
var number = function(busStops){
  let num = 0;
  for (let i=0; i<busStops.length; i++){
    num = num + busStops[i][0] - busStops[i][1];
  }
  return num;
}
```
***
exercise: https://www.codewars.com/kata/563cf89eb4747c5fb100001b
```
function removeSmallest(numbers) {
  let numbers2 = numbers.slice(0);
  numbers2.splice(numbers.indexOf(Math.min(...numbers)), 1);
  return numbers2;
}
```
***
exercise: https://www.codewars.com/kata/583f158ea20cfcbeb400000a
```
function arithmetic(a, b, operator){
  return operator == 'add' ?
  a + b :
  operator == 'subtract' ?
  a - b :
  operator == 'multiply' ?
  a * b :
  operator == 'divide' ?
  a / b :
  0;
}
```
***
exercise: https://www.codewars.com/kata/5174a4c0f2769dd8b1000003
```
function solution(nums){
return nums !== null ? nums.sort((a,b) => a-b) : [];
}
```
***
exercise: https://www.codewars.com/kata/514b92a657cdc65150000006
```
function solution(number){
 let res = [];
 for (let i=1; i<number; i++){
  if (i * 3 < number){
    res.push(i * 3);
  }
  if (i * 5 < number){
    res.push(i * 5);
  }
 }
 return number >= 0 ? [... new Set(res)].reduce((a, b) => a + b, 0) : 0;
}
```
***
exercise: https://www.codewars.com/kata/5266876b8f4bf2da9b000362
```
function likes(names) {
  return names.length == 1 ?
  `${names[0]} likes this` :
  names.length == 2 ?
  `${names[0]} and ${names[1]} like this` :
  names.length == 3 ?
  `${names[0]}, ${names[1]} and ${names[2]} like this` :
  names.length > 3 ?
  `${names[0]}, ${names[1]} and ${names.slice(2).length} others like this` :
  `no one likes this`;
}
```
***
exercise: https://www.codewars.com/kata/525f50e3b73515a6db000b83
```
function createPhoneNumber(numbers){
  return `(${numbers[0]}${numbers[1]}${numbers[2]}) ${numbers[3]}${numbers[4]}${numbers[5]}-${numbers[6]}${numbers[7]}${numbers[8]}${numbers[9]}`
}
```
***
exercise: https://www.codewars.com/kata/54da5a58ea159efa38000836
```
function findOdd(A) {
  let a = A.reduce(function (acc, curr) {return acc[curr] ? ++acc[curr] : acc[curr] = 1, acc}, {});
  for (let i=0; i<Object.keys(a).length; i++){
    if (Object.values(a)[i] % 2 == 1){return Number(Object.keys(a)[i]);}
  }
}
```
***
exercise: https://www.codewars.com/kata/541c8630095125aba6000c00
```
function digitalRoot(n) {
if (n < 10) return n;
return digitalRoot(String(n).split('').reduce((partialSum, a) => partialSum + Number(a), 0));
}
```
***
exercise: https://www.codewars.com/kata/54bf1c2cd5b56cc47f0007a1
```
function duplicateCount(text){
return new Set([...text].filter((item, index) => {return [...text].indexOf(item.toLowerCase()) != index}).map(x => x.toLowerCase())).size;
}
```
***
exercise: https://www.codewars.com/kata/5264d2b162488dc400000001
```
function spinWords(string){
  return string.split(' ').map(x => x.length >= 5 ? x.split('').reverse().join('') : x).join(' ');
}
```
***
exercise: https://www.codewars.com/kata/5526fc09a1bbd946250002dc
```
function findOutlier(integers){
  if (integers.filter(a => Math.abs(a)%2 ==0).length > integers.filter(b => Math.abs(b)%2 ==1).length){
    return integers.filter(b => Math.abs(b)%2 ==1)[0]
} else {
  return integers.filter(c => Math.abs(c)%2 ==0)[0]
}};
```
***
exercise: https://www.codewars.com/kata/55bf01e5a717a0d57e0000ec
```
function persistence(num){
  let r = 0;
  while(num >= 10){
    r++;
    num = [...String(num)].reduce((a, b) => a*b, 1);
  };
  return r;
}
```
***
exercise: https://www.codewars.com/kata/545cedaa9943f7fe7b000048
```
function isPangram(string){
  let regex1 = 'abcdefghijklmnoqprstwvyuxz';
  for (let i=0; i<string.length; i++){if(new RegExp(`${regex1.charAt(i)}`, "i").test(string) === false){return false};}
  return true;
}
```
***
exercise: https://www.codewars.com/kata/55c45be3b2079eccff00010f
```
function order(words){
  return words == "" ? "" : words.split(" ").sort((a,b) => Number(a.match(/[0-9]/g)) - Number(b.match(/[0-9]/g))).join(' ');
}
```
***
exercise: https://www.codewars.com/kata/54da539698b8a2ad76000228
```
function isValidWalk(walk) {
 if (walk.length == 10){
  if (walk.filter(a => a == 'n').length == walk.filter(a => a == 's').length){
    if (walk.filter(a => a == 'e').length == walk.filter(a => a == 'w').length){
      return true;
    } else {return false;}
  } else {return false;}
 } else {return false;}
}
```
***
exercise: https://www.codewars.com/kata/5287e858c6b5a9678200083c
```
function narcissistic(value) {
  return String(value).split('').map(a => Math.pow(Number(a), String(value).length)).reduce((a, b) => a+b, 0) == value ? true : false;
}
```
***
exercise: https://www.codewars.com/kata/515de9ae9dcfc28eb6000001
```
function solution(str){
   return str == "" ? [] : str.match(/.{1,2}/g).map(a => String(a).length == 1 ? a.concat('', '_') : a);
}
```
***
exercise: https://www.codewars.com/kata/585d7d5adb20cf33cb000235
```
function findUniq(arr) {
arr = arr.sort((a,b) => a-b);
return arr[0] == arr[1] ? arr[arr.length - 1] : arr[0];
}
```
***
exercise: https://www.codewars.com/kata/5262119038c0985a5b00029f
```
function isPrime(num) {
  if (Number.isInteger(num) && num>1){
    for(let i=2; i<=Math.sqrt(num); i++){if(num % i === 0){return false};}
    return true;
  } else {return false;}
}
```
***
exercise: https://www.codewars.com/kata/523f5d21c841566fde000009
```
function arrayDiff(a, b) {
  for(let i=0; i<=b.length-1; i++){
    a = a.filter((x) => x !== b[i]);
  }
  return a;
}
```
***
exercise: https://www.codewars.com/kata/5208f99aee097e6552000148/javascript
```
function solution(string) {
  return string.replace(/([A-Z])/g, ' $1');
}
```
***
exercise: https://www.codewars.com/kata/526571aae218b8ee490006f4
```
function countBits(n){
  // return (n >>> 0).toString(2).split('').filter((x) => x == 1).length;
  return n.toString(2).split('').filter((x) => x == 1).length;
};
```
***
exercise: https://www.codewars.com/kata/578aa45ee9fd15ff4600090d
```
function sortArray(array) {
  let arrOdd = array.filter((a) => a % 2).sort((b,c) => b - c);
  return array.map((d) => d%2 === 0 ? d : arrOdd.shift());
}
```
***
exercise: https://www.codewars.com/kata/57eb8fcdf670e99d9b000272
```
function high(x){
let y = x.split(' ').map((a) => [...a].reduce((b, c) => b+'abcdefghijklmnopqrstuvwxyz'.split('').indexOf(c)+1, 0));
return x.split(' ')[y.indexOf(Math.max(...y))];
}
```
***
exercise: https://www.codewars.com/kata/5839edaa6754d6fec10000a2
```
function findMissingLetter(array){
  let alph = 'abcdefghijklmnopqrstuvwxyz';
  if(array[0] == array[0].toUpperCase()){alph = alph.toUpperCase();};
  let pieceOfAlph = alph.slice(alph.split('').indexOf(array[0]), alph.split('').indexOf(array[array.length - 1]) + 1);
  return pieceOfAlph.split('').find((a) => array.find((b) => b == a) == undefined);
}
```
***
exercise: https://www.codewars.com/kata/54b42f9314d9229fd6000d9c
```
function duplicateEncode(word){
  let w = word.toLowerCase().split('');
  let duplicates = w.filter((item, index) => {return w.indexOf(item.toLowerCase()) != index});
  return w.map((a) => duplicates.indexOf(a) === -1 ? "(" : ")").join('');
}
```
***
exercise: https://www.codewars.com/kata/546f922b54af40e1e90001da
```
function alphabetPosition(text) {
return text.toLowerCase().split('').map((a) => {if(/[A-Za-z]/.test(a) === true){return 'abcdefghijklmnopqrstuvwxyz'.indexOf(a) + 1} else {return '-';};}).filter((b) => b !== '-').join(' ');
}
```
***
exercise: https://www.codewars.com/kata/517abf86da9663f1d2000003/javascript
```
function toCamelCase(str){
return str.replace(/(?<=[-_])\w/g, function(match){return match.toUpperCase();}).replace(/([-_])/g, '');
}
```
***
exercise: https://www.codewars.com/kata/556deca17c58da83c0000
```
function tribonacci(signature,n){
 if (signature.length >= n){return signature.slice(0, n);}
 else {
  for(let i=3; i<n; i++){signature.push(signature[i-3] + signature[i-2] + signature[i-1])};
  return signature;
 }
}
```
***
exercise: https://www.codewars.com/kata/52efefcbcdf57161d4000091/javascript
```
function count (string) {  
  let count = {};
  [...string].map((s) => count[s] ? count[s]++ : count[s] = 1);
  return count;
}
```
***
exercise: https://www.codewars.com/kata/5592e3bd57b64d00f3000047
```
function findNb(m) {
  let currVol = 1;
  let n = 1;
  while (currVol < m){
    n++;
    currVol = currVol + n ** 3;
  }
  return currVol == m ? n : -1;
}
```
***
exercise: https://www.codewars.com/kata/52597aa56021e91c93000cb0
```
function moveZeros(arr) {
  return arr.filter((a) => a !== 0).concat(arr.filter((b) => b === 0));
}
```
***
exercise: https://www.codewars.com/kata/520b9d2ad5c005041100000f
```
function pigIt(str){
  return str.split(' ').map((a) => {
    if(/[,.?!-]/g.test(a) === false){return a.substring(1) + a.substring(0, 1) + "ay"}
    else {return a};
  }).join(' ');
}
```
***
exercise: https://www.codewars.com/kata/52685f7382004e774f0001f7/javascript
```
function humanReadable (seconds) {
  function lenOfNum(x){return String(x).length == 2 ? x : "0" + String(x);}
  return `${lenOfNum(Math.floor(seconds / 3600))}:${lenOfNum(Math.floor((seconds % 3600) / 60))}:${lenOfNum(seconds - 3600 * Math.floor(seconds / 3600) - 60 * Math.floor((seconds % 3600) / 60))}`;
}
```
***
exercise: https://www.codewars.com/kata/513e08acc600c94f01000001
```
function rgb(r, g, b){
  return [r, g, b].map(x => {
    if(x > 255){x = 255; return x.toString(16).padStart(2, '0').toUpperCase();}
    else if(x < 0){x = 0; return x.toString(16).padStart(2, '0').toUpperCase();}
    else {return x.toString(16).padStart(2, '0').toUpperCase();}
  }).join('');
}
```
***
exercise: https://www.codewars.com/kata/52449b062fb80683ec000024/javascript
```
function generateHashtag (str) {
  let result = '#' + str.split(' ').filter((a) => a !== '').map((b) => b.charAt(0).toUpperCase() + b.slice(1).toLowerCase()).join('');
  return result.length > 140 ? false :
  str.length < 1 ? false :
  result.length < 2 ? false :
  result; 
}
```
***
exercise: https://www.codewars.com/kata/530e15517bc88ac656000716
```
function rot13(message){
  let alphB = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'.repeat(2);
  let alphS = 'abcdefghijklmnopqrstuvwxyz'.repeat(2);
  return message.split('').map((a) => {
    if(/[A-Z]/.test(a) === true){
      return [...alphB][alphB.indexOf(a) + 13];
    } else if (/[a-z]/.test(a) === true){
      return [...alphS][alphS.indexOf(a) + 13];
    } else {
      return a;
    };}).join('');
}
```
***
exercise: https://www.codewars.com/kata/525f3eda17c7cd9f9e000b39/javascript
```
function zero(a) {if(a){return Math.floor(new Function('return ' + `0 ${a}`)());} else {return 0;}}
function one(a) {if(a){return Math.floor(new Function('return ' + `1 ${a}`)());} else {return 1;}}
function two(a) {if(a){return Math.floor(new Function('return ' + `2 ${a}`)());} else {return 2;}}
function three(a) {if(a){return Math.floor(new Function('return ' + `3 ${a}`)());} else {return 3;}}
function four(a) {if(a){return Math.floor(new Function('return ' + `4 ${a}`)());} else {return 4;}}
function five(a) {if(a){return Math.floor(new Function('return ' + `5 ${a}`)());} else {return 5;}}
function six(a) {if(a){return Math.floor(new Function('return ' + `6 ${a}`)());} else {return 6;}}
function seven(a) {if(a){return Math.floor(new Function('return ' + `7 ${a}`)());} else {return 7;}}
function eight(a) {if(a){return Math.floor(new Function('return ' + `8 ${a}`)());} else {return 8;}}
function nine(a) {if(a){return Math.floor(new Function('return ' + `9 ${a}`)());} else {return 9;}}

function plus(b) {return `+ ${b}`;}
function minus(b) {return `- ${b}`;}
function times(b) {return `* ${b}`;}
function dividedBy(b) {return `/ ${b}`;}
```
***
exercise: https://www.codewars.com/kata/514a024011ea4fb54200004b/javascript
```
function domainName(url){
  if(/www/.test(url)){return url.match(/\.(.*?)\./)[1];}
  else if (/www/.test(url) === false && /http/.test(url) === true) {return url.match(/\/\/(.*?)\./)[1];}
  else {return url.match(/^.*?(\.)/)[0].slice(0, -1);}
}
```
***
exercise: https://www.codewars.com/kata/54521e9ec8e60bc4de000d6c
```
function maxSequence(arr){
  let msf = arr[0];
  let cm = arr[0];
  if (arr.length === 0){return 0;}
  else if (Math.max(...arr) < 0){return 0;}
  else {
    for (let i = 1; i < arr.length; i++){
      cm = Math.max(arr[i], cm + arr[i]);
      msf = Math.max(msf, cm);
    }
    return msf;
  } 
}
```
***
exercise: https://www.codewars.com/kata/525c65e51bf619685c000059
```
function cakes(recipe, available) {
  let ans = [];
  // checking if the recipe ingredients list is longer than available ingredients list
  if(Object.keys(recipe).length > Object.keys(available).length){return 0;}
  else{
    //going through every ingredient in the recipe ingredients list
    for(let key of Object.keys(recipe)){
      // if the current ingredient from the recipe ingredients list IS NOT present in the available ingredients list
      if(available.hasOwnProperty(key) === false){return 0;}
      // if the current ingredient from the recipe ingredients list IS present in the available ingredients list
      else {
        ans.push(available[key] / recipe[key]);
      }
    }
    return Math.floor(Math.min(...ans));
  }
}
```
***
***
### License
Copyright (c) 2023, heEXDe All rights reserved. Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. The views and conclusions contained in the software and documentation are those of the authors and should not be interpreted as representing official policies, either expressed or implied, of the FreeBSD Project.