# Researching Commands

## grep -c

```` grep -c ```` counts the quoted words.

Why is it useful: When we place a -c after the grep and quoted a string of word or phrase within a specific file. We see the count that matches with the quoted string of word or phrase. Such as the first example, it looks like trivia was found only once within the ./techical/911report/chapter-11 and the rest of the files have zero counts indicating that it was not used within the file. This is very helpful to know how many words containing that specific string since it will make things easier with a possible scavenger hunt.

### Example 1:
### Command:
````
grep -c "trivia" ./*/911report/*.txt
````

### Output
````
./technical/911report/chapter-1.txt:0
./technical/911report/chapter-10.txt:0
./technical/911report/chapter-11.txt:1
./technical/911report/chapter-12.txt:0
./technical/911report/chapter-13.1.txt:0
./technical/911report/chapter-13.2.txt:0
./technical/911report/chapter-13.3.txt:0
./technical/911report/chapter-13.4.txt:0
./technical/911report/chapter-13.5.txt:0
./technical/911report/chapter-2.txt:0
./technical/911report/chapter-3.txt:0
./technical/911report/chapter-5.txt:0
./technical/911report/chapter-6.txt:0
./technical/911report/chapter-7.txt:0
./technical/911report/chapter-8.txt:0
./technical/911report/chapter-9.txt:0
./technical/911report/preface.txt:0
````

### Example 2:
### Command:
````
grep -c "die" ./*/911report/*.txt
````

### Output: 
````
./technical/911report/chapter-1.txt:3
./technical/911report/chapter-10.txt:2
./technical/911report/chapter-11.txt:0
./technical/911report/chapter-12.txt:5
./technical/911report/chapter-13.1.txt:1
./technical/911report/chapter-13.2.txt:1
./technical/911report/chapter-13.3.txt:6
./technical/911report/chapter-13.4.txt:9
./technical/911report/chapter-13.5.txt:11
./technical/911report/chapter-2.txt:8
./technical/911report/chapter-3.txt:6
./technical/911report/chapter-5.txt:11
./technical/911report/chapter-6.txt:5
./technical/911report/chapter-7.txt:3
./technical/911report/chapter-8.txt:1
./technical/911report/chapter-9.txt:13
./technical/911report/preface.txt:2
````

### Example 3:
### Command:
````
grep -c "hospital" ./*/911report/*.txt
````
### Output:
````
./technical/911report/chapter-1.txt:0
./technical/911report/chapter-10.txt:0
./technical/911report/chapter-11.txt:1
./technical/911report/chapter-12.txt:0
./technical/911report/chapter-13.1.txt:0
./technical/911report/chapter-13.2.txt:0
./technical/911report/chapter-13.3.txt:0
./technical/911report/chapter-13.4.txt:0
./technical/911report/chapter-13.5.txt:0
./technical/911report/chapter-2.txt:0
./technical/911report/chapter-3.txt:0
./technical/911report/chapter-5.txt:0
./technical/911report/chapter-6.txt:0
./technical/911report/chapter-7.txt:0
./technical/911report/chapter-8.txt:0
./technical/911report/chapter-9.txt:3
./technical/911report/preface.txt:0
````



## grep -o

```` grep -o ```` displays the word repeatedly in ordered as used.

Why is it useful: The display of -o is very interesting that it displays that specific word that is typed in. They are repeating the strings we have quoted within specific files. This is very helpful to know how many words are repeated within the text and within different files. Makes things easier when doing a match pattern survey.

### Example 1:
### Command:
````
grep -o "foot" ./*/911report/*.txt
````

### Output
````
./technical/911report/chapter-1.txt:foot
./technical/911report/chapter-11.txt:foot
./technical/911report/chapter-11.txt:foot
./technical/911report/chapter-13.2.txt:foot
./technical/911report/chapter-13.2.txt:foot
./technical/911report/chapter-13.5.txt:foot
./technical/911report/chapter-13.5.txt:foot
./technical/911report/chapter-13.5.txt:foot
./technical/911report/chapter-13.5.txt:foot
./technical/911report/chapter-13.5.txt:foot
./technical/911report/chapter-13.5.txt:foot
./technical/911report/chapter-13.5.txt:foot
./technical/911report/chapter-13.5.txt:foot
./technical/911report/chapter-13.5.txt:foot
./technical/911report/chapter-13.5.txt:foot
./technical/911report/chapter-13.5.txt:foot
./technical/911report/chapter-13.5.txt:foot
./technical/911report/chapter-13.5.txt:foot
./technical/911report/chapter-13.5.txt:foot
./technical/911report/chapter-13.5.txt:foot
./technical/911report/chapter-2.txt:foot
./technical/911report/chapter-3.txt:foot
./technical/911report/chapter-3.txt:foot
./technical/911report/chapter-6.txt:foot
./technical/911report/chapter-6.txt:foot
./technical/911report/chapter-9.txt:foot
./technical/911report/chapter-9.txt:foot
````

### Example 2:
### Command:
````
grep -o "bird" ./*/911report/*.txt
````

### Output: 
````
./technical/911report/chapter-13.5.txt:bird
````

### Example 3:
### Command:
````
grep -o "tree" ./*/911report/*.txt
````
### Output:
````
./technical/911report/chapter-10.txt:tree
./technical/911report/chapter-11.txt:tree
./technical/911report/chapter-11.txt:tree
./technical/911report/chapter-13.1.txt:tree
./technical/911report/chapter-13.3.txt:tree
./technical/911report/chapter-13.4.txt:tree
./technical/911report/chapter-13.5.txt:tree
./technical/911report/chapter-3.txt:tree
./technical/911report/chapter-3.txt:tree
./technical/911report/chapter-3.txt:tree
./technical/911report/chapter-6.txt:tree
./technical/911report/chapter-7.txt:tree
./technical/911report/chapter-7.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
./technical/911report/chapter-9.txt:tree
````



## grep "^"

```` grep "^" ```` displays the phrase that starts with the word within the "^" and after ^

Why is it useful: When we add ^ within the quoted word. We see the line that starts with that specific word. The ^ expression specifies the start of a line. This is very helpful to know where to start reading when teachers are giving use quotes to read or poems.

### Example 1:
### Command:
````
grep "^The" ./*/911report/*.txt
````

### Output
````
./technical/911report/chapter-1.txt:The FAA and NORAD
./technical/911report/chapter-1.txt:The Agencies Confer
./technical/911report/chapter-1.txt:The Pentagon Teleconferences. Inside the National Military Command Center, the deputy director for operations immediately thought the second strike was a terrorist attack. The job of the NMCC in such an emergency is to gather the relevant parties and establish the chain of command between the National Command Authority-the president and the secretary of defense- and those who need to carry out their orders.
````

### Example 2:
### Command:
````
grep -c "^The" ./*/911report/*.txt
````

### Output: 
````
./technical/911report/chapter-1.txt:3
./technical/911report/chapter-10.txt:0
./technical/911report/chapter-11.txt:0
./technical/911report/chapter-12.txt:0
./technical/911report/chapter-13.1.txt:0
./technical/911report/chapter-13.2.txt:0
./technical/911report/chapter-13.3.txt:0
./technical/911report/chapter-13.4.txt:0
./technical/911report/chapter-13.5.txt:0
./technical/911report/chapter-2.txt:0
./technical/911report/chapter-3.txt:0
./technical/911report/chapter-5.txt:0
./technical/911report/chapter-6.txt:0
./technical/911report/chapter-7.txt:0
./technical/911report/chapter-8.txt:0
./technical/911report/chapter-9.txt:0
./technical/911report/preface.txt:0
````

### Example 3:
### Command:
````
grep -o "^The" ./*/911report/*.txt
````
### Output:
````
./technical/911report/chapter-1.txt:The
./technical/911report/chapter-1.txt:The
./technical/911report/chapter-1.txt:The

````
