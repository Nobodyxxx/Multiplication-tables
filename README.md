# Multiplication-tables
Can help the elementary student to remember the basic multiplication knowledge

#include<stdio.h>
#include<stdlib.h>
int main(){
	int i, j, k;
	for (i = 1; i <= 9; i++){
		for (j = 1; j <= i; j++){
			k = j*i;
			printf("%d*%d=%d\t", j, i, k);
		}
		printf("\n");  
	}
	system("pause");
	return 0;
	
}
