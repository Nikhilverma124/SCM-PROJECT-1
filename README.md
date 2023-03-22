int Menu()
{
  int ch;
  printf("\n1. enter bus:");
  printf("\n2. enter cycle:");
  printf("\n3. enter riksha:");
  printf("\n4. show status:");
  printf("\n5. delete data:");
  printf("\n6. exit:");
  printf("\n\nenter your choice:\n");
  scanf("%d",&ch);
  return(ch);
}
void Delete()
{
 nob=0;
 noc=0;
 nor=0;
 amount=0;
 count=0;
}
void ShowDetail()
{
 printf("\nnumber of bus=%d",nob);
 printf("\nnumber of cycle=%d",noc);
 printf("\nnumber of riksha=%d",nor);
 printf("\ntotal number of vehicle=%d",count);
 printf("\ntotal gain amount=%d",amount);
}
void Riksha()
{
 printf("\nentry successful");
 nor++;
 amount=amount+50;
 count++;
}
void Cycle()
{
 printf("\nentry successful");
 noc++;
 amount=amount+20;
 count++;
}
void Bus()
{
 printf("\nentry successful");
  nob++;
  amount=amount+100;
  count++;
}
