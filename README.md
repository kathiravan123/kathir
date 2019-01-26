#include <stdio.h> 
  
int main() 
{ 
    int A; 
  
    scanf("%d", &A); 
  
    if (A > 0) 
        printf(" positive.", A); 
    else if (A < 0) 
        printf(" negative.", A); 
    else if (A == 0) 
        printf(" zero.", A); 
  
    return 0; 
} 
