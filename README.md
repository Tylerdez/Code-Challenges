## I've taken college level courses in Statistics, Finite Mathematics, and Java Programming

## What I hope to gain from Computer Science:
* how to formulate a plan before trying to solve a problem
* how to know if there is a problem
* how to solve problems efficiently
* recognizing patterns in data and when to use it to your advantage

Big O notation is a mathematical notation that describes the limiting behavior of a function

Big O is a family of notations

In computer science, big O notation is used to classify algorithms according to how their run time or space requirements grow as the input size grows

Constant Time Complexity O(1) Example: Input has no time affect on run time. Size of input does not affect execution time - Input has no affect on time

```
var arr = [ 1,2,3,4,5];

function findIndex() {

                arr[2]; // => 3, prints output 1 time

}
```

vs

Linear Time Complexity O(n) Example: Input affects run time but run time is proportional to size of input. Execution time grows linear depending on size of input - Input proportionally affects time

var arr1 = [orange, apple, banana, lemon]; //=> 4 steps

```
function findLength(arr1) {

                for (var i = 0; i < array.length; i++) { 

                                console.log(array[i]);} //=> prints output 4 times

}
```

vs

Polynomial Time Complexity O(n^2) Example: Execution time is proportional to the polynomial of the input size or input held to a certain exponent

Here input is raised to an exponent

Say you have O(n^2) - input raised two the 2nd power. Imagine you have to find a page in a book, you have to first find the book you're looking for and then find the specific page in the book

```
function containsDuplicates(elements)

{

    for (var x = 0; x < elements.Count; x++)

    {

        for (var i = 0; i < elements.Count; i++)

        {

            // Don't compare with self

            if (x == i) continue;

 

            if (elements[x] == elements[i]) return true;

        }

    }

 

    return false;

}
```
 
O(N^k) represents an algorithm whose performance is directly proportional to the size carried to an exponent.

This is common with algorithms that involve nested iterations over the data set.

Deeper nested iterations will result in O(N3), O(N4) etc.
