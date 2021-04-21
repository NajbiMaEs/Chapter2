# Chapter5
Exercises from Chapter 5 of the book "Practical C Programming"
## Exercise 5-1: Write a program that converts Centigrade to Fahrenheit.
```c
int main(void) {
float C;
float F = C * 9/5 + 32;

  printf("Introduce temperature in Celsius (to Farenheit): ");
  scanf("%f", &C );

F = C * 9/5 + 32;

  printf("%f° Celsius are %f° Farenheit", C , F);
  
  return (0);

}
```
## Exercise 5-2: Write a program to calculate the volume of a sphere.
```c
#include <stdio.h>
float radius;   
float volume;              
const float PI = 3.141592;

int main() {
	printf("Introduce radius of the sphere : ");
  scanf("%f",&r);
	
	volume = (4/3) * PI * (radius * radius * radius);  /* volumn=(4/3) * pi * r^3*/
	printf("The volume of sphere is %f.\n", volume);

	return(0);
}
```
## Exercise 5-3: Write a program that prints the perimeter of a rectangle given its height and width.
```c
#include <stdio.h>
int main(void) {
int perimeter, height, width;

  printf("Introduce the height: ");
  scanf("%d", &height);

  printf("Introduce the width: ");
  scanf("%d", &width);

perimeter = (2 * height) + (2 * width);

  printf("The perimeter of the rectangle is: %d", perimeter);

  return (0); 
}
```
## Exercise 5-4: Write a program that converts kilometers per hour to miles per h our.
```c
#include <stdio.h>
float km/h;              
float mi/h;              

int main()
{
	printf("Introduce kilometers per hour: ");

	mi/h = (km/h * 0.6213712);
	printf("%f miles per hour\n", miph);

	return(0);
}
```
## Exercise 5-5: Write a program that takes hours and minutes as input, and then outputs the total number of minutes.
```c
#include <stdio.h>
int main(void) {
int h;
int m;
int total_time;

  printf("Introduce hours (no fractions): ");
  scanf("%d", &h);

  printf("Introduce minutes (no fractions): ");
  scanf("%d", &m);

total_time = (h * 60) + m;

  printf("The total time in minutes is: %d", total_time);

  return 0;
}
```
## Exercise 5 -6: Write a program that takes an integer as the number of minutes, and outputs the total hours and minutes.
```c
#include <stdio.h>
int main(void) {
int h;
int m;
int total_time;

  printf("Introduce minutes (no fractions): ");
  scanf("%d", &m);

h = m / 60;

total_time = m % 60;

  printf("In %d minutes there are %d hours and %d minutes", m, h, fm);
  
  return 0;
}
```
