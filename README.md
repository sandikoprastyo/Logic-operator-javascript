# Logic-operator-javascript, [*Visit page*](https://javascript.info/logical-operators)

## OR || 

### result = a || b;


__alert( true || true );   // true
  alert( false || true );  // true
  alert( true || false );  // true
  alert( false || false ); // false__
  
  
## Example
  
__let hour = 9;
if (hour < 10 || hour > 18) {
  alert( 'The office is closed.' );
}__

  ============================================================================================================================
  
  
  ## AND && 

### result = a && b;


__alert( true && true );   // true
alert( false && true );  // false
alert( true && false );  // false
alert( false && false ); // false__


## Example

__let hour = 12;
let minute = 30;
if (hour == 12 && minute == 30) {
  alert( 'The time is 12:30' );
}__




============================================================================================================================

## NOT ! 
### result = a ! b;

## Example not !

__alert( !true ); // false
alert( !0 ); // true__



**note 0 = false, 1 = true**




## Example Double not !!
  
__alert( !!"non-empty string" ); // true
alert( !!null ); // false__




