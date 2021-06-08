https://jsfiddle.net/enyosolutions/74mnx9zw/3/

There set of exercies are simple functions exercises. Try to make the functions cost efficient. You have 5min per question.



## sort me plz

Write a sort function to sort an array of numbers in ascending order.


## prime or no prime

Write a function that as input a integer N return true if N is a prime number

Write a function take into as input  an array and return the position of all the prime numbers in an array


## separate numbers

Write a function that take as input an array of numbers , separate them into two arrays: one of even numbers and another one of odd numbers. Arrays must sorted descending.

The function must return AND print an object of the form `{odd: array, even: array}`.


> Extras points if you keep the complexity at O(n^2+1)


## geo coordinates

Write a function that take as input  two geo cordinates objects A and B ({lat: xxx, lon: xxx})  and a distance D (in km), and return true if the A is within D km of B.
Ex :
isInRange(A : coords, B: coords, D: number) : boolean. 

```
var paris = {lat:48.864716, lon: 2.349014}

var londres = {lat:51.509865, lon:-0.118092}

var moscow = {lat: 38.736946,   lon: -9.142685};

var d = 500
```


## Determine if two rectangles intersect.

Give an algorithm to solve this problem when rectangles are defined by their width, height, and (x, y) coordinates of their top-left corners.

Give another algorithm where rectangles are defined by their width, height, and (x, y) coordinates of their centers.
What are the behaviors of your algorithms for edge cases?

If you need a tip ask the examiner.

## Validate international phone numbers

Write a function that as input a string S return true if S is an international phone number eg. start with ++ or 00 then has a series of numbers with or without spaces, and no other characters.


## upper case ?
Write a function that determines if a string starts with an upper-case letter A-Z.
try to be efficient.

## What does this function do ?

```
const values = [1, 2, 3, 4, 5];
for (var i = 0; i < 5; i++) {
  setTimeout(() => {
		console.log('index is ' + i + ', it\'s value is => ' + values[i]);
  }, 1000);
}
```

## persistence
Write a function, persistence, that takes in a positive parameter num and returns its multiplicative persistence, which is the number of times you must multiply the digits in num until you reach a single digit.

For example:

 persistence(39) === 3 // because 3*9 = 27, 2*7 = 14, 1*4=4
                       // and 4 has only one digit
                 
 persistence(999) === 4 // because 9*9*9 = 729, 7*2*9 = 126,
                        // 1*2*6 = 12, and finally 1*2 = 2
                  
 persistence(4) === 0 // because 4 is already a one-digit number
 

## async load all
we have an array containing a list of filenames ith their full path. write a function that Asynchronously loads all the data of each  file and returns it in an array.

`loadFile(sourceList: string[]) => Promise<string[]>`
 
## Comment faire un middleware express
- Faire un middle ware qui va logger toutes les requetes d'apis qui passsent sur le serveur: 
- On souhaite faire des statistiques sur le nombre de requete par endpoint.


## Discussion :

How do i build a SaaS (one app with compagnies(team) using the it without having anytihng to with each other.. What are the important considerations in terms of : 
- security
- data storage
- Scaling. 
- Authentication.


## Discussion : 

How do i build an HR recruitment management platform ( post jobs, receive candidates, communication process, interviews, decision.
- What are the features you'll build
- What is my data model
- How do i manage the most tedious part of the process (receiving resume by emails and exchanging with clients) 
