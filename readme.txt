void main(void)
{
   int i = 0;
   int j = 0;
   int sum = 0;
   int sum1 = 0;
   for(i=0;i<10;i++)
   {
      sum = sum+i;
      printf("sum = %d  i= %d \n",sum,i);
   }
   for(j=0;j<10;j++)
   {
      sum1 = sum1+j;
      printf("sum1 = %d  j= %d \n",sum1,j);
   }
   sum  = sum + sum1;
   printf("sum = %d  sum1= %d \n",sum,sum1);
   printf("git  test \n");
}