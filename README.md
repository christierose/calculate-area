#include <stdio.h>
#include <math.h>

int main()
{
 double volume, radius;

 printf("Enter radius to calculate volume of a sphere:\n");
 scanf("%lf", &radius);

if (radius>0)
 {
 volume=((pow(radius,3))*M_PI*(4/3));
 printf("Volume of a sphere is %4.2f\n", volume);
 }
else
 printf("Enter positive value for radius\n");


return 0;
}
