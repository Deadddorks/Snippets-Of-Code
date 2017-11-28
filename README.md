# Snippets-Of-Code
Web repository for coding examples that focus on covering multiple aspects of a topic in order to create an environment for users to find well-rounded examples of code.  

# Origin of Idea
Overall, this all comes from many struggles with stack-overflow, where I am never able to find what I am looking for. 
## Issues with Stack-Overflow
- One aspect I find lacklustor is the whole idea that it is this discussion-board
  - Creates an environment where answers are less than well-rounded examples focused specifically on the original persons question
  - Other people looking for similar answers are left searching through a whole slew of Questions & Answers looking for just a few lines of code
  - Even if you finally find the example you are looking for, you will probably have to have to go on another wild goose chase in order to find your next question, even though its related. But since the Question->Answer model is so specific, it was not included there
- Stack focuses on the problems as opposed to the solutions
  - Insead of being able to search `how to` do `x`, you have to find someone elses question, which was probably `why is x` `broken` in `my specific code`
  - And when other people come in saying, I wanted a slightly different answer, then you have even more conversation to read through coming in as another user at a future date
  - Because the focus is on the questions, the answers are focused on the quesetions, therefore giving specific examples that dont help other cases. For someone trying to learn about this topic, they dont know what is necessary to the topic, and what is specific to the other persons question
## Issues with tutorials
- Tutorials focus on a linear progression through ideas
  - You are forced to find a starting point on your own
  - Only forward progress is supported
  - Doesnt support skipping forward
- Tutorials are not a dynamic environment
  - If someone makes a youtube video series, they post the video, and then cant really change it to add things
  - If someone makes a blog style tutorial post, there is no real intent for the post to ever be updated by the poster

# Generalization of the Idea
## Learn at your own rate, in your own way
- Not bounded by a linear progression to learning
  - Start with an idea you want to learn
  - Easily find all the topics you need to learn that
  - Easily progress in whatever direction your mind desires
- Examples are given to provide an all-encompassing explaination
  - Removes the environment of a discussion, so that all context must be stated directly in the example, not scattered throughout comments
  - Users are encouraged (and even forced) to update their post when questions occur, rather than throwing in a quick answer in a comment
- Not limited to parse through someone elses question to simply get some example code
  

# Sample Post: String Method Examples
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
