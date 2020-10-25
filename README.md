# Java Types
### Primitive Types

Type    | Byte |   Range    
------- | ---- | ----------
byte    |  1   | [-128,127]
short   |  2   | [-32K,32K]
int     |  4   | [ -2B, 2B]
long    |  8   | 
float   |  4   | 
double  |  8   | 
char    |  2   | A, B, C, ..
boolean |  1   | true/false

### Reference Types 
For complex objects. (ex: **Date**)

### Strings
* **String**: Immutable (unmodified), when string changed a new string object is created.
  * ![Methods](https://www.w3schools.com/java/java_ref_string.asp)
* **StringBuffer**: Mutable + Synchronized (thread safe) / start 16 char / capacity increase (2 * old_capacity + 2)
* **StringBuilder**: Mutable + Non-Synchronized / start 16 char / capacity increase (2 * old_capacity + 2)
