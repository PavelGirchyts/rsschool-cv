Pavel Girchits
Contacts for communication: telegram @gpldm email pashagirchyts@gmail.com
Brief information about me: A student of BNTU, I did a little programming at the university, I want to connect my life with this and learn something new.
I know a little C++ C# syntax
English Level A1
task with codewars: If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.
Finish the solution so that it returns the sum of all the multiples of 3 or 5 below the number passed in. Additionally, if the number is negative, return 0 (for languages that do have them).
code:
int solution(int number) 
{
    if (number<0) return 0;
    int sum=0;
    for(int i=0; i<number; i++)
    {
        if (i % 3 == 0 || i % 5 ==0) sum+=i;
    }
    return sum;
}
