# Snippets-Of-Code
Web repository for coding examples that focus on covering multiple aspects of a topic in order to create an environment for users to find well-rounded examples of code.  

# Table of contents
- [Oritin of Idea](https://github.com/Deadddorks/Snippets-Of-Code/blob/master/README.md#origin-of-idea)
  - [Issues with Stack-Overflow](https://github.com/Deadddorks/Snippets-Of-Code/blob/master/README.md#issues-with-stack-overflow)
  - [Issues with Tutorials](https://github.com/Deadddorks/Snippets-Of-Code/blob/master/README.md#issues-with-tutorials)
- [Generalization of the Idea](https://github.com/Deadddorks/Snippets-Of-Code/blob/master/README.md#generalization-of-the-idea)
  - [Learn at your own rate, in your own way](https://github.com/Deadddorks/Snippets-Of-Code/blob/master/README.md#learn-at-your-own-rate-in-your-own-way)
- [What is it](https://github.com/Deadddorks/Snippets-Of-Code/blob/master/README.md#what-is-it)
  - [Structure](https://github.com/Deadddorks/Snippets-Of-Code/blob/master/README.md#structure)
    - [Post](https://github.com/Deadddorks/Snippets-Of-Code/blob/master/README.md#post)
    - [Post Body](https://github.com/Deadddorks/Snippets-Of-Code/blob/master/README.md#post-body)
    - [Base Snippet](https://github.com/Deadddorks/Snippets-Of-Code/blob/master/README.md#base-snippet)
    - [Substitution Snippet](https://github.com/Deadddorks/Snippets-Of-Code/blob/master/README.md#substitution-snippet)
    - [Post Addition Request](https://github.com/Deadddorks/Snippets-Of-Code/blob/master/README.md#post-addition-request)
    - [Post Request](https://github.com/Deadddorks/Snippets-Of-Code/blob/master/README.md#post-request)
- [Example](https://github.com/Deadddorks/Snippets-Of-Code/blob/master/README.md#sample-post-string-method-examples)
  - [Base Snippet](https://github.com/Deadddorks/Snippets-Of-Code/blob/master/README.md#base)
  - [Substituion Snippets](https://github.com/Deadddorks/Snippets-Of-Code/blob/master/README.md#snippets)

# Origin of Idea
Overall, this all comes from many struggles with stack-overflow, where I am never able to find what I am looking for. 
## Issues with Stack-Overflow
- One aspect I find lacklustor is the whole idea that it is this discussion-board
  - Creates an environment where answers are less than well-rounded examples focused specifically on the original persons question
  - Other people looking for similar answers are left searching through a whole slew of Questions & Answers looking for just a few lines of code
  - Even if you finally find the example you are looking for, you will probably have to have to go on another wild goose chase in order to find your next question, even though its related. But since the Question->Answer model is so specific, it was not included there
- Stack focuses on the problems as opposed to the solutions
  - Insead of being able to search "`how to` do `x`", you have to find someone elses question, which was probably along the lines of "`why is x` `broken` in `my specific code`?"
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

# What is it?
## Structure
### `Post`
- Contains `Tag(s)`, `Language(s)`, `Title`, `Description`, & a `Body`
- Is the bread and butter of the organization
- Users make `Posts`, and other users can find them via `tag`, `language`, `title`, `description`, and even other ways
### `Post Body`
- Contains `Table of Contents`, `Base Snippet(s)`, & `Substitution Snippets`
- The purpose is to have `Base Snippet(s)` with holes in it, and `Substitution Snippets` that fill in the holes with different code examples, so that subtle differences can be easily represented and understood
### `Base Snippet`
- Contains the full class for whatever the example is
- All `neccessary` things going on in background should be clearly displayed
- Anything `unnecessary` to the basic understanding of the topic should be left out
### `Substitution Snippet`
- Code shoud be only the code to be substituted into the `Base Snippet`
- Contains
  - Description of what it does, and what it might do differently than a similar snippet
  - The code
  - An `Image`/`Text`, depicting what the output of the specific snippet would be
- Looking through a list of `Substitution Snippets` should clearly show how slightly changing the code allows for many options for customizing the code to your current needs
### `Post Addition Request`
- Cross between a `comment` and a github `issue`
- Directed at the user who made the `Post`, and includes what sort of information they feel is missing
- Other users can also see this, and can make what is similar to a github `pull request` with a suggested update
- User who made the `Post` has a couple different options
  - Make an addition to the `Post` and close the `request`
  - Add links to other `Post(s)` that explain the information in the `request`, and then close the `request`
  - Add it to their `todo` list, which doesn't close the `request` but moves it to their `todo` list
  - Leave the `request` open, and send it out to the public in an effort to say `"I think this is important, but I either dont have the effort or skill to answer it"`
  - Close the `request` without doing anything else. Should be avoided unless the `request` was actually garbage
- When a users `request` is closed, they are notified of it being closed, and what action was taken
### `Post Request`
- Very similar to a `Post Addition Request`, but instead of saying "I think you should add to your `Post`", its more of a "I dont think there is a good `Post` about `<Insert Topic Here>`, can someone please make a `Post` about it"
- Should include all of the specifics of what information they think should be in the `Post`, in order for the user who decides to make a `Post` about it to understand what sort of information is not understood about the topic from someone at that level's perspective
- Once a `Post` is made in reference to a `Post Request`, it is said to have an answer pending, where the user who made the request can either say
  - Yes this is what I was looking for
    - Closes the `Post Request`
  - I feel this didn't quite capture everything
    - Update the `Post Request`, and it says open for the public to see
    - User who made the `Post` that "didnt cover everything" gets a `Post Addition Request`









---
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
