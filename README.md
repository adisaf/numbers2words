# Numbers to Words (JavaScript) - Original project : https://github.com/Kibo/numbers2words/
It converts a numeric value to words. 

You can use it as [standalone js library](https://github.com/adisaf/numbers2words/tree/master/build) or as **Node module**. 

##Example
```
var translator = new T2W("EN_US");
// one thousand two hundred thirty-four
translator.toWords(1234)
```
 - en_US	(0...999999999)
 - cs_CZ	(0...999999999)

##Now available locales
 - fr_FR	(0...999999999)

**You can implement your locale vocabulary**. For additional locale send pull request with locale file + tests.
 
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
