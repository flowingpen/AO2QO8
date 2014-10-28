AO2QO8
======
void loop(struct node * head)
{
struct node * fast, *slow;
while(slow)
{
slow=slow->next;
fast=fast->next->next;
if(slow==fast)
printf("loop found");
}
printf("loop not found");
}
