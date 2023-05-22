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
***
### License
Copyright (c) 2023, heEXDe All rights reserved. Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. The views and conclusions contained in the software and documentation are those of the authors and should not be interpreted as representing official policies, either expressed or implied, of the FreeBSD Project.