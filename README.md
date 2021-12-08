# test
Program 1
#include<iostream.h>
#include<conio.h>
int getnumber (int a[],int n,int sum)
{
   int count=0;
   for(int i=0;i<n;i++)
   for(int j=i+1;j<n;j++)
        if(a[i]+a[j]==sum)
          count++;
   return count;
}
void main()
{
  int a[]={4,5,6,4,2,3};
  int n=sizeof(a)/sizeof(a[0]);
  int sum=8;
  count<<”count of  pair=”<<getnumber(a,n,sum);
  getch();
}
Program 2
#include<iostream.h>
#include<conio.h>
int sum(int n)
{
   if(n==0)
     return 0;
else 
     return (n%10+sum(n/10));
}
void main()
{
     int num=1234;
     int results=sum(num);
     count<<”sum of digits of “<<num<<results;
     getch();
}

Program 5
#include<iostream.h>
#include<conio.h>
int change(int num)
{
     int rev num=0;
     while(num>0)
     {
        revnum =revnum*10+num%10;
        num=num/10;
      }
     return revnum
}
void main()
{
     clrscr();
     int num=123;
     cout<<”reverse of”<<n<<”=”<<change(num);
     getch();
}

Program 6
#include<iostream.h>
#include<conio.h>
int btd(int n)
{
   int dec=0;base=1,temp=n;
   while(temp)
   {
       int lnum=temp%10;
       temp=temp/10;
       dec=dec+lnum*base;
       base=base*2;
   }
   return Dec ;
}
void main
{
    int num;
    cout <<”enter binary num”;
    cin>>num;
    cout<<”decimal form of”<<num<<”=”<<btd(num);
    getch();
}


Program 8
#include<iostream.h>
#include<conio.h>
#include<studio.h>
void main()
{
    char a[100];
    int u,l,d,sy,space;
    u=l=d=sy=space=0;
    cout<<”enter string”;
    cin>>a;
     for(int i=0;i<100;i++)
     {
       if(a[i]>=’A’ && a[i]<=’Z’)
         u++;
       elseif(a[i]>=’a’ && a[i]<=’z’)
         l++;
       elseif(a[i]>=0 && a[i]<=9)
         d++;
      elseif(a[i]==” “)
         space++;
      else
         sy++;
     }
   cout<<”No. of upper case =”<<u;
   cout<<”No. of lower case=”<<l;
   cout<<”No. of digit=”<<d;
   cout<<”No. of space=”<<space;
   cout<<”No. of special characters =”<<sy;
   getch();
}

Program 10
#include<iostram.h>
#include<conio.h>
void main()
{
   int a[100],pos,value;
   cout<<”enter no. of ele in array”;
   cin>>n;
   cout<<”enter array”;
   for(int i=0;i<n;i++)
   cin>>a[i];
   cout<<”position wanted to update”;
   cin>>pos;
   cout<<”enter value”;
   cin>>value;
   for(i=n-1;i>=pos-1;i--)
   a[c+1]=a[c];
   a[pos-1]=value;
   cout<<”new array”;
   for(i=0;i<=n;i++)
   cout<<a[i];
   getch();
}


Program 11
#include<iostream.h>
#include<conio.h>
int pos(int a[],int n,int x)
{
    for(int i=0;i<n;i++)
     if(a[i]==x)
       count<<”num is at “<<i;
     else 
       count<<”num not found”;
}
void main()
{
   int a[]={10,20,30,40};
   int x =10;
   int n=sizeof(a)/sizeof(a[0]);
   count<<”situation is”<<pos(a,n,x);
   getch();
}

Program 13
#include<iostream.h>
#include<conio.h>
#include<string.h>
void main()
{
   char a[100];
   int len;
   clrscr ();
   cout<<”enter string”;
   gets(a);
   len=strlen(a);
   for(int i=0;i<len;i++)
   {
      if(a[i]==’a’||a[i]==’e’||a[i]==’i’||a[i]==’o’||a[i]==’u'||a[i]==’A’||a[i]==’E’||a[i]==’I’||a[i]==’O’||a[i]==’U’)
      {
          for(int j=i;j<len;j++)
          {
             a[j]=a[j+1];
           }
         len--;
      }
    }
   cout<<”new string is”<<a;
   getch();
}

Program 14
#include<iostream.h>
#include<conio.h>
void change(int a[],n)
{
   int count=0;
   for(int i=0;i<n;i++)
   if(a[i]!=0)
   a[count++]=a[i];
   while(count<n)
   a[count++]=0;
}
void main()
{
   int a[]={1,0,2,0,3,0};
   int n=sizeof(a)/sizeof(a[0]);
   change(a,n);
   cout<<”new array=”;
   for(int i=0;i<n;i++)
   cout<<a[i]<<” “;
   getch();
}

Program 15
#include<iostream.h>
#include<conio.h>
void zipzapzoom(int n)
{
    if(n%3==0 && n%5==0)
      count<<”zoom”;
    elseif(n%3==0)
      count<<”zip”;
    elseif(n%5==0)
      count<<”zap”;
    else
      count<<”invalid num”;
}
void main()
{
   clrscr();
   int x;
   count<<”enter num to play”;
   cin>>x;
   zipzapzoom(x);
   getch();
}
