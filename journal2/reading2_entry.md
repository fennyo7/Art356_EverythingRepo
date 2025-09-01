# Chapter 1 of Eloquent JavaScript

In the world of computers, there is only data. Bits are the things that are in 1's and 0's in computers. A modern computer is composed of more than 30 billion bits in its volatile data storage (memory) while nonvolitile (hard drive) is significantly less. To work with that many bits, these bits are simplified into chunks of information and in JavaScript, those chunks are called values. Some of these values are numbers, some are pieces of text, some are functions, etc. 

For numbers, JavaScript uses 64 bits to store a single value. Back then, old computers had much smaller memory with it using 8 or 16 bits, making it easy to overflow small numbers. With modern computers, only truly enormous numbers make the memory overflow. There are 3 special numbers in JavaScript that are considered numbers but don't behave like normal numbers. First 2 are Infinity (Gojo mentioned!!!) and negative Infinity. Do too much funny stuff with Infinity and it will quickly lead to NaN (think Naan bread) or Not a Number. 

Next value is a string, which represents text. You can use single or double quotes as long as they are the same quotes and go at the beginning and end of a string. Almost anything can go between quotes though few characters are more difficult (the book never mentions what). Whenever you use a backslash (Xenoblade reference) inside quoted text, it indicates the text has special meaning. For example n after a backslash is a new line while t after a backslash is tab. Strings can't be affected by mathemathical operators in the traditional sense but the addition operator could be used to glue two strings together for example "among" + "us" equals "amongus". 

Next value is a boolean, which is the true and false value. With this greater than, less than, and equal signs are used, which are binary operators. Uppercase letters are less than lowercase letters and even special characters (!, =, and so on) are included in the ordering (book doesn't say where they go yet again :( ) The only value that isn't equal to itself is NaN because it is nonsensical and as such, isn't equal to any other nonsensical values. 

For booleans, the three logical operators are and, or, and not. And is true only if all of the conditions are true, or is true if any of the conditions are true, and not is true if the condition is not true. 

Special values are null and undefined, which are values that show when there isn't a valid value. They are values but carry no information. The difference between these two values don't matter most of the time so they are for the most part interchangeable. 

When an operator is given the wrong type of value, JavaScript corrects you and converts the value to the type it needs. This is type coercion. If the correction isn't obvious, you get NaN and further operations produce more NaNs. If you want to know if your value is the real one, you can compare it to null with the = operator. 
