# Iv-nAlonzo-Chapter-4

EXERCISE 1
//Write a program to print your name, any number, and date of birth.

#include <stdio.h>

int main()
{
  printf("My name is Daniel Alexander Piña Gutiérrez\n");
  printf("My institutional number is 2009105\n");
  printf("My date of birth is 11-07-2002\n");

  return 0;
}

EXERCISE 2
//Write a program to print a block E using asterisks (*), where the E has a height of seven characters and a width of five characters

#include <stdio.h>

int main()
{
  printf("*****\n");
  printf("**\n");
  printf("**\n");
  printf("*****\n");
  printf("**\n");
  printf("**\n");
  printf("*****\n");

  return 0;
}
EXERCISE3
//Write a program to compute the area and perimeter of a rectanglewith a width of three inches and a height of five inches. What changes must be made to the program so that it works for a rectangle with a width of 6.8 inches and a length of 2.3 inches?

#include <stdio.h>

int main()
{
  float width;
  float height;
  float area;
  float perimeter;

  width = 6.8;
  height = 2.3;

  area = width * height;
  perimeter = (2 * width) + (2 * height);

  printf("The area of the rectangle is: %f inches\n", area);
  printf("The perimeter of the rectangle is: %f inches\n", perimeter);

  return 0;
}

EXERCISE 4
//Write a program to print "HELLO" in big block letters; each letter should have a height of seven characters and width of five characters.

#include <stdio.h>

int main()
{
  printf("** ** ***** **    **     *** \n");
  printf("** ** **    **    **    ** **\n");
  printf("** ** **    **    **    ** **\n");
  printf("***** ***** **    **    ** **\n");
  printf("** ** **    **    **    ** **\n");
  printf("** ** **    **    **    ** **\n");
  printf("** ** ***** ***** *****  *** \n");

  return 0;
}

EXERCISE 5
//Write a program that deliberately makes the following mistakes:
//· Prints a floating-point number using the %d conversion.
//· Prints an integer using the %f conversion.
//· Prints a character using the %d conversion.

#include <stdio.h>

int main()
{
  float x = 1.23;
  printf("%d\n", x);

  int y = 7;
  printf("%f\n", y);

  char z = 'D';
  printf("%d\n", z);

  return 0;
}
