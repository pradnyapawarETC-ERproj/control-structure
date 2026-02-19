#include <iostream>
using namespace std;
/* there are 3 types of loop
1.for loop
2.while loop
3.do-while loop
*/
//----------for loop----
// int i=1;
// cout<<i;
// i++;
/*syntax for for loop
for (initializaton;condition;updation)
{
    loop body (c++ code);
}
*/

int main() {
    // for (int i=0;i<=40;i++)
    // {
    // cout<<i<<endl;
   
    // }
    // 
    
    // >>>-----------while loop in c++-------
    /*syntax;
    while(conditon);
    {
        c++ statements
    }
   printing 1 to 40 using while loop
   */
//   int i=1;
//   while(i<=40){
//       cout<<i<<endl;
//       i++;
//   }

//infinite while loop
//   int i=1;
//   while(true){
//       cout<<i<<endl;
//       i++;
//   }

/*do while loop

 syntax;
 do
 {
 c++ statements;
 }
    while(conditon);
   printing 1 to 40 using while loop
   */
   --------------->>>>>>table of 6<<<<<<<<<<<------
int i=1;
do{
     cout <<  i << " = " << 6 * i << endl;
        i++;
    

}
while(i<=10);

    return 0;
}
