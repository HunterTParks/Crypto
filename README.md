# Cryptosquare

#### An Epicodus exercise on BDD model creation and differing between business-end an user-interface logic, 05.04.17

#### **By Anabel Ramirez, Hunter Parks, Jun Fritz**

## Description

This web page will create a cryptosquare from a sentence and output the 5-letter coded words.

Specs:<br>

|  behavior | input  | output  |
|---|---|---|
| remove spaces from sentence  | Hello there.  | Hellothere.  |
| remove punctuation  | Hellothere.  | Hellothere  |
| change to downcase | Hellothere  | hellothere  |
| create an array of the individual characters from input |  hellothere | ["h", "e", "l", "l", "o" , "t", "e", "r", "e"] |
| determine the square root of the total number of elements in the array |  ["h", "e", "l", "l", "o"  "t", "e", "r", "e"] | sqrt(10) |
| create rows of the square root of the total number of elements in the array | "h", "e", "l", "l", "o"  "t", "e", "r", "e" | "h" "e" "l"  / "l" "o" "t" /  "h" "e" "r" /  "e" |
| If remainder, choose the number of columns that correspond to smallest square that is larger that the number of characters in the message. | "h" "e" "l" "l" "o" "t" "h" "e" "r" "e' | sqrt(10)= 3.2, use 4 |
| Create a variable of the array in strings the length of the square root. |  "h" "e" "l" | "h, e, l"  |
| Read the strings by index | "h" "e" "l"  / "l" "o" "t"  / "h" "e" "r" / "e" | 012, 012, 012, 0  |
| create an array by matching index position | "h" "e" "l" / "l" "o" "t"/ "h" "e" "r" /"e" | ["hlheeoeltr"] |
| break the new array into words 5-letters long |  ["hlheeoeltr"] | "hlhee""oeltr" |
| join and add spaces between the words | "hlhee""oeltr"  | "hlhee oeltr"  |
| output the 5-letter words | "hlhee" "oeltr" | "hlhee" "oeltr" |


## Setup/Installation Requirements

Clone this repository.
Open the index page in a web browser.

## Known Bugs

No known bugs.

## Support and contact details

If you have any issues or have questions, ideas, concerns, or contributions please contact anabel@apparentinc.com.

## Technologies Used

* HTML
* CSS
* Javascript
* Bootstrap

### License
This software is licensed under the MIT license.

Copyright (c) 2017 **Anabel Ramirez** **Hunter Parks** **Jun Fritz**
