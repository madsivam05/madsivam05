/*insertion sort*/
void main()
{
int i,j,k,n,temp, a[20],p=0;
printf("enter total elements:");
scanf("%d",&n);
printf("enter array elements:");
for(i=0; i<n; i++)
scanf("%d",&a[i]);
for(i=1; i<n; i++)
{
temp=a[i];
j=i-1;
while((temp <a[j]) &&(j>0))
{
a[j+1]=a[j];
j=j-1;
}
a[j+1]=temp;
p++;
printf("\n after pass %d :",p);
for(k=0; k<n; k++)
printf(" %d ",a[k]);
}
printf("\n sorted list:");
for(i=0; i<n; i++)
printf(" %d ""\n",a[i]);
}

<!---
madsivam05/madsivam05 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
