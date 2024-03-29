<link rel='stylesheet' href='assets/css/main.css'/>

# String

## Solutions
* Python: [Jupyter Notebook](answers/python/string-solution.ipynb)  || [HTML](answers/python/string-solution.html)


## Other References
- http://www.w3resource.com/python-exercises/string/

## Easy (A)
* A1 - create an empty string
* A2 - create a string `s1` with "hello world"
* A3 - print the length of `s1`
* A4 - slicing : print first 3 chars in 'hello world'
* A5 - slicing : print last 2 chars in 'hello world'
* A6 - slicing : print characters at from position 2 to 4 in 'hello world'
* A7 - reverse the string `s1`
* A8 - iterate through the string `s1` and print one char at a time
* A9 - create a multiline string as follows
```
hello world
good bye
cruel world!
```
* A10 - convert string 'Hello World' to lower case / upper case
* A11 - trim white spaces front & back of the string '  hello world  '  (result is : 'hello world')
* A12 - find the index of 'world' in 'hello world'
* A13 - Find if 'llo' is a substring of string 'hello world'
* A14 - concat two strings
combine 'hello' and 'world' , output => 'helloworld'

## Medium (B)

### B1 - compute the hash functions md5 and sha1 of a string

### B2 - Tokenize a sentence into words

```code
"I love Java";
```

The above sentence should be split into 3 words : `I,  love, Java`

How about if the sentence has multiple spaces 

```text
"I        love Java";
```

Will your code work?

#### Hints:

* Look at `String.split` function.
* Delimiter can be a regex: `\\s` - signifies a whitespace (space, tab, newlie ..etc)

### B3 - find the longest word in a sentence

### B4 - find number of occurrences of string `s1` in string `s2`  

For example, 'xx' occurs in string 'hello xx yy xxx xxxx' 4 times

### B5 - swap comma(,) and dots(.) in a string

input : "10,300,321.900.8"  
output: "10.300.321,900,8"

#### B6 - Strip all non alpha-num characters from a string
input : 'hello123!#.'   
output : 'hello123'

#### B7 - Determine if String is a palindrome
Ignore case and non-alpha chars (you can use the function you defined above).  
e.g.  
input = 'madam', reverse the string = 'madam' ,  is_palindrome = yes
