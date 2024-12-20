# c_project_gagan
#include<stdio.h>
int main() {
    int secret_number;
    int guess_number;

  secret_number = 9;
    int i;
    int guess_limit;

   guess_limit = 4;

  for(i=1;i<guess_limit;i++)
    {
        printf("Guess number %d : ",i);
        scanf("%d",&guess_number);

  if(guess_number==secret_number)
        {
            printf("YOU WON");
            break;
        }
    }
    if(guess_number!=secret_number)
    {
        printf("YOU LOST");
    }
    return 0;
}
