## Raman Kandratchyk
### Contacts:
+ Discord: Raman Kandratchyk#2279
+ E-mail: kondrator@gmail.com
+ Tel.: +375-29-734-49-85
+ Place of residence: Gomel, Belarus

### About myself:
Start learning JavaScript, CSS, HTML. RSSchool is a windfall for me.
Ready for new knowledge and life changes.

### Code example:
```
<script>
    'use strict';

	let arrNumber = [1, 6, 7, 8, 3, 4, 5, 6];
	const findNumber1 = 8;
	const findNumber2 = 12;
	const findNumber3 = 6;

	findIndex(arrNumber, findNumber1);
	findIndex(arrNumber, findNumber2);
	findIndex(arrNumber, findNumber3);

	function findIndex(array, value) {
	  let i = 0;
	  let indexArr = [];
	  let indexes = array.filter(function(item, index, array) {
	    if (item == value) {
		  indexArr[i++] = index;
		  return true;
		};
	  });
	  let strMultPos = indexArr.join(', ');
	  let answer = (indexes.length == 0) ? `There is no number ${value} in array` :
	    `Number ${value} has next positions in array: ` + strMultPos;
	  alert( `Initial array: ${array} \n${answer}` );  
	};
</script>
```
