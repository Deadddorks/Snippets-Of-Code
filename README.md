# Snippets-Of-Code
Web repository for coding examples that focus on covering multiple aspects of a topic in order to create an environment for users to find well-rounded examples of code.  



Sample `Post`:
# String Method Examples
Examples for an assortment of the methods in the String class
## Base
#### Base Code
```java
public class StringMethodExamples
{
  public static void main(String[] args)
  {
    String initial = "A,B,c,d,E";
    String output = "";
    
    // $CHECKPOINT_1$
    
    System.out.println(output);
  }
}
```
#### Base Output
```
```
## Snippets
### Substring 1 - $Checkpoint_1$
#### Code
```java
output = initial.toString(0,3);
```
#### Output
Note how `0` is the first index, and index `3` (`','`) is not included
```
A,B
```
### Substring 2 - $Checkpoint_1$
#### Code
```java
output = initial.toString(2,3);
```
#### Output
Again, note how the start index is `inclusive` and the end index, is the first index to be `excluded`
```
B
```
### Substring 3 - $Checkpoint_1$
#### Code
```java
output = initial.toString(4);
```
#### Output
Note how if you only include a start index, it will be considered the `inclusive` start index, and will include the rest of the String
```
c,d,E
```
### ToUpperCase
#### Code
```java
output = initial.toUpperCase();
```
#### Output
Pretty simple, turns all letters to upper case, whether they were upper case or not in the first place
```
A,B,C,D,E
```
### ToLowerCase
#### Code
```java
output = initial.toLowerCase();
```
#### Output
Pretty simple, turns all letters to lower case, whether they were lower case or not in the first place
```
a,b,c,d,e
```
