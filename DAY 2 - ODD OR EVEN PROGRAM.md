ODD OR EVEN PROGRAM 

-------------------------------------------------

\#include <stdio.h>

int main() {

    int num;



    // Input from user

    printf("Enter a number: ");

    scanf("%d", \&num);



    // Check odd or even

    if (num % 2 == 0) {

        printf("%d is Even.\\n", num);

    } else {

        printf("%d is Odd.\\n", num);

    }



    return 0;

}

---------------------------------------------------

OUTPUT :

**Enter a number: 3456**

**3456 is Even.**

