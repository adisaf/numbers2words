# Numbers to Words (JavaScript)
Original project : https://github.com/Kibo/numbers2words/
It converts a numeric value to words. 

You can use it as [standalone js library](https://github.com/adisaf/numbers2words/tree/master/build) or as **Node module**. 

##Example
```
var translator = new T2W("FR_FR");
// mille deux cent et trente-quatre
translator.toWords(1234)

##Now available locales
 - fr_FR	(0...999999999)

```
 - en_US	(0...999999999)
 - cs_CZ	(0...999999999)


**Locale object**
The locale object must implement method **translate**.
```
/**
 * Translate numbers to words
 * @public
 * @param {array} numbers
 * @param {number} index
 * @return {string}
 */
translate( numbers, index){
 // implement it
};
```
