# __*PALINDROME*__ 
>## __*What Is A Palindrome*__
<p>
A palindrome is a type of word play in which a word or phrase spelled forward is the same word or phrase spelled backward.
 There are different types of palindromes,which are as follows:

<!--ul-->
* Characters and words
* Sentences and phrases
* Names
* Numbers

---
>### __*Characters and Words*__
Character palindromes read the same backward as forward. Noon, civic, radar, level, and kayak are good examples of character palindromes.
<!--images-->
![Characterer_and_phrases](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRsofRZQ05gb31ZufOPvMKvV0zw1z4iHivULw&usqp=CAU)

---

>### __*Sentences and Phrases*__
Palindromic sentences consist of a sentence or phrase, for example: Live on time, emit no evil.
<!--images-->
![Sentences_and_phrases](https://contenthub-static.grammarly.com/blog/wp-content/uploads/2015/08/NEVER-ODD-OR-EVEN.jpg)

---
>### __*Names*__
Some given names are palindromes, for example: Hannah, Anna, and Bob.
<!--images-->
![Names](https://uselessetymology.files.wordpress.com/2019/10/palindrome-useless-etymology-12.png?w=1088)

---

>### __*Numbers*__
A palindromic number is a number that remains the same when its digits are reversed.

---

<!--images-->
![Numbers](https://media.geeksforgeeks.org/wp-content/cdn-uploads/program-to-check-if-a-number-is-palindrome-1024x512.png)
 ---
>## __*Program*__
<!--code blocks-->
``` #c
#include <stdio.h>
int main() {
    int n, reversedN = 0, remainder, originalN;
    printf("Enter an integer: ");
    scanf("%d", &n);
    originalN = n;

    // reversed integer is stored in reversedN
    while (n != 0) {
        remainder = n % 10;
        reversedN = reversedN * 10 + remainder;
        n /= 10;
    }

    // palindrome if orignalN and reversedN are equal
    if (originalN == reversedN)
        printf("%d is a palindrome.", originalN);
    else
        printf("%d is not a palindrome.", originalN);

    return 0;
}
```
---
>## __*Checklist*__
* [x] Task-1
* [x] Task-2
* [x] Task-3
* [ ] Task-4 (In Progress)

___
>## __*Log on to the below link to know more information:*__
[Palindrome] (https://en.wikipedia.org/wiki/Palindrome)

---

# __*Thank you*__
