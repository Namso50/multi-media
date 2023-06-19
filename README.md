# Multimedia Application

## Description

Search menu
: It finds files included a group of characters. Moreover, if you enable regex option, you can use regular expressions to search

Last used date
: It indicates when a file was last used

## Explanation

Search menu
: It helps to find files easily. After clicking button to enable regex, people can find files which they do not remember all of a file name. For example, people can use ".a"  regular expression to find a file, second letter of whose name is 'a'.

Last used date
: People can see when a file was last used by them. So, people can find what files they opened last or what they never opened. 

## How my code works

Search menu
: I used `includes()` to find files. It determines whether a file name contains a user's input. For regex, I used `new Regex()` to create a regular expression from users' input. 

Last used date
: I created a `lastUsed` array includes empty strings. After the selected file is closed, I used `new Date()` to find exact time. I passed this value to where the id of this file in the `lastUsed` specifies. When a string is not empty, it will show in the screen.