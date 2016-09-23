#include "stdio.h"

int main(void) {
  int a, b, c, aux;
  scanf("%d %d %d", &a, &b, &c);
  	if (a > b && b > c){
  		aux = a;
  		a = b;
  		c = b;
  		c = aux;
	 }
 	printf("%d %d %d\n", a, b, c);
 	return 0;
}
