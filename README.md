# student_resul
#include <stdio.h>

structure Student { 
int roll;
float marks;
}

int main(){
structure Student s[5];
int i;

for (i=0,i<5,i++)
printf("Enter roll number and marks:");
scanf("%d %f", &s[i].roll,&s[i].marks);
}

printf("\n  Result  \n");

for (i=0,i<5,i++){
printf("Roll number : %d", s[i].roll);
printf("Result : %s\n",(s[i].marks>=40)? "Pass": "Fail");
}
return 0;
}
