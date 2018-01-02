
```javascript
/**
*Removing the First and Last Characters of a String
*/

export function removeChar(str:string):string{
	// Geting the string length
	const strLength=str.lenght;

	return str.substring(1,strLength-1);
}
const subString = removeChar('Paul');
```