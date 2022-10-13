## **Hello! In this lab report we will cover...**
## Part 1 - the basics of a search engine implementation
## Part 2 - dealing with bugs via JUnit testing


## **Part 1** 

- using the SearchEngine.java file, an integer value between 1024 and 49151 can be run along with the compiled file using the following commands
```
javac SearchEngine.java
java SearchEngine 2000
Server Started! Visit http://localhost:2000 to visit.
```
- the following output is observed which means that the server is now available to access at the following url (the number at the end depends on the input value that is passed as a parameter when running SearchEngine) http://localhost:2000
- our search engine contains 2 possible functionalities depending on whether the last part of the URL path is /add or /search
- /add will store in the server registry whatever query String is typed into the search bar after an = sign
- /search will search for all case sensitive occurences of the String after the = sign in the query
- here are some examples...

## After entering the URL, http://localhost:2000, use /add to add a search item to the registry
![](addapple.png)

