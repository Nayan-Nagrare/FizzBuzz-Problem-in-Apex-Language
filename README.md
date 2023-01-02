# FizzBuzz-Problem-in-Apex-Language
Integer num=0;
do
{
 if(math.mod(num,3)==0 && math.mod(num,5)==0)
 {
     system.debug('fizzbuzz');
 }
    else if(math.mod(num,3)==0)
 {
     system.debug('fizz');
 }
    else if(math.mod(num,5)==0)
 {
     system.debug('buzz');
 }
    else
    {
        system.debug(num);
    }
    num++;
}
while(num<=100);
