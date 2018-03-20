# Regular Expressions

## Solutions
* Python: [Jupyter Notebook](answers/python/regex-solution.ipynb)  || [HTML](answers/python/regex-solution.html)


## A - Easy

### A1: Determine if a string has any numbers in it?
'hello123' -> yes
'abc' --> no

### A2: Determine if a string has only alpha-numeric characters (a..z or 0-9)
'hello123' --> yes
'hello!' --> no

## B - Medium

### B1: check if a string is a valid phone number.
For simplicity let's assume a valid phone number has the format of xxx-xxx-xxxx  

### B2: Check if a string is a valid email
- An email has the format  of    USER@DOMAIN.EXTENSION.   
- Valid characters for USER are any alpha numberic character (a-z 0-9) and dash(-) and underscore ( _ ) and dot (.)
- Valid characters for DOMAIN are any alpha numberic character (a-z 0-9) and dash(-) and underscore ( _ )
- Valid characters for EXTENSION is only alpha characters


### B3 : Extract all phone numbers from  string
Build on above solution.  
You need to extract and print all phone numbers.

e.g.  
input:   
"hello, our customer service number is 800-123-456.  For press inquiries 877-123-4567"

output:
- 800-123-456
- 877-123-4567

### B4 : Extract username and DOMAIN name from emails in text
Input:  
"work email is user1@company.com  and personal email is user2@gmail.com"

Output:   
- email1 : user1@company.com
    - user : user1
    - domain : company.com
- email2 : user2@gmail.com
    - user : user2
    - domain : gmail.com
