**Name:**  Tamar Bigvava

**email:** bigvava0205@gmail.com

**My goal** is to become front-end Developer

**Skills:** Resposive web design,  javascript basics.

**code exemple** in Javascript:
*Solution for Telephone Number Validator*
```javascript
   function telephoneCheck(str) {
    const re = /^1?\s?(\(\d{3}\)[- ]?|\d{3}[- ]?)\d{3}[- ]?\d{4}$/;
    console.log(re.test(str));

    if(re.test(str)){
      return true;
    } else {
      return false;
    }
   }

   telephoneCheck("1 (555) 555-5555");
```


**another code exemple** in Javascript:

*Caesar-cipher*
```javascript
   function rot13(str) {
   let newArr = Array.from(str);
   for(let i = 0; i <newArr.length; i++){
      switch(newArr[i]){
         case "N":
         newArr[i] = "A";
         break;
         case "O":
         newArr[i] = "B";
         break;
         case "P":
         newArr[i] = "C";
         break;
         case "Q":
         newArr[i] = "D";
         break;
         case "R":
         newArr[i] = "E";
         break;
         case "S":
         newArr[i] = "F";
         break;
         case "T":
         newArr[i] = "G";
         break;
         case "U":
         newArr[i] = "H";
         break;
         case "V":
         newArr[i] = "I";
         break;
         case "W":
         newArr[i] = "J";
         break;
         case "X":
         newArr[i] = "K";
         break;
         case "Y":
         newArr[i] = "L";
         break;
         case "Z":
         newArr[i] = "M";
         break;
         case "A":
         newArr[i] = "N";
         break;
         case "B":
         newArr[i] = "O";
         break;
         case "C":
         newArr[i] = "P";
         break;
         case "D":
         newArr[i] = "Q";
         break;
         case "E":
         newArr[i] = "R";
         break;
         case "F":
         newArr[i] = "S";
         break;
         case "G":
         newArr[i] = "T";
         break;
         case "H":
         newArr[i] = "U";
         break;
         case "I":
         newArr[i] = "V";
         break;
         case "J":
         newArr[i] = "W";
         break;
         case "K":
         newArr[i] = "X";
         break;
         case "L":
         newArr[i] = "Y";
         break;
         case "M":
         newArr[i] = "Z";
         break;
      }
 }
return newArr.join('');
}
 rot13("SERR YBIR?");
```

**Experience** in responsive web design:
project for photopgrapher site.  custom html template for wordpress.
(https://www.rajebashvili.ge/about/)

project for social agency site.  custom html template for wordpress.
(https://www.motomo.ge)
