# led
#include<reg51.h>
abit led1=P1;
abit led1=P2;

void madelay(unsigned int);

void main()
{
P1=0x00;

while(1)
{
led1=1;
madelay(100);
led1=0;
led2=1:
madelay(2000);
led2=0;
}
}
void madelay(unsigned int itime)
{
unsigned int i,j;
for(i=0;i<itime;i++)
for(j=0;j<1000;j++);
}
