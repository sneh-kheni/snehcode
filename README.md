// there are 2 types of header files.
// 1.system header files:it comes with a compiler
#include<iostream>
#include<iomanip>
//2.user define header files:it is written by a programmer.
// example#include<this.h>this will produce an error if this.h named
//  file will be absent in the current directory 
 using namespace std;//we can write this instead of std::
//  int c = 22;
//It is a comment 
/*
this
is
a
multiline
comment
*/ 
//using namespace std
         // int global_variable=22;
         // void sum(){
         //   std::cout<< global_variable;
         // }
int main(){
        //     std::cout<<"hello world";
            //  float a =2,b =15;
        //     float pi = 3.14;
            // int global_variable=555;
        
        //    sum();
        //    std::cout<<"for local variable"<<global_variable;
        //    std::cout<<"value of a is"<<a<<"\nand value of b is" <<b<<"\nthe value of pi is" <<pi;
        //    bool is_fals=false;
        //    std::cout<<"\nam i a failure?"<<is_fals;

// int number1,number2;
// cout<<"enter the value of number 1";//"<<"is insertion operator.
// cin>>number1;                       //">>"is extraction operator.
// cout<<"enter the value of number 2";
// cin>>number2;
// cout<<"the sum of num1 and num2 is"<<number1+number2;

// cout<<"there afre manyoperators in c++";
// cout<<"these are types of operators";



// ARITHMETIC OPERATORS

// cout<<"answer of a+b is"<<a+b;
// cout<<"\nanswer of a-b is"<<a-b;
// cout<<"\nanswer of a*b is"<<a*b;
// cout<<"\nanswer of a/b is"<<a/b;
// cout<<"\nanswer of modulo idk";
// cout<<"\nanswer of a++ is"<<a++;
// cout<<"\nanswer of a-- is"<<a--;
// cout<<"\nanswer of ++a is"<<++a;
// cout<<"\nanswer of --a is"<<--a;


// ASSIGNMENT OPERATORS

// THESE OPERATORS ARE USED TO ASSIGN THE VALUES 
// int a=3,b=4;
// char D = 'd';

// COMPARISON OPERATORS 

// cout<<"the value of a == b is"<<(a==b)<<endl;
// cout<<"the value of a != b is"<<(a!=b)<<endl;
// cout<<"the value of a <= b is"<<(a<=b)<<endl;
// cout<<"the value of a >= b is"<<(a>=b)<<endl;
// cout<<"the value of a < b is"<<(a<b)<<endl;
// cout<<"the value of a > b is"<<(a>b)<<endl;

// LOGICAL OPERATORS

// cout<<"The value of and loical operator ((a==b) && (a=<b))"<<((a!=b) && (a<=b))<<endl;
// cout<<"The value of or loical operator ((a==b) || (a=<b))"<<((a!=b) || (a<=b))<<endl;
// cout<<"The value of not loical operator ((a==b) && (a=<b))"<<(!(a==b))<<endl;


// ***************BUILT IN DATA TYPES*****************


// int a,b,c;
// cout<<"please enter the value of a"<<endl;
// cin>>a;
// cout<<"please wnter the value of b"<<endl;
// cin>>b;
// c=a+b;
// cout<<"sum of your value is"<<::c<<endl;
// cout<<"sum of your value is"<<c;


// // ***************FLOAT , DOUBLE AND LONG DOUBLE LITERALS*****************



// float x=34.45f;
// long double e =34.45l;

// cout<<"the sizeof 34.4 is"<<sizeof(34.45)<<endl;
// cout<<"the sizeof 34.4f is"<<sizeof(34.45f)<<endl;
// cout<<"the sizeof 34.4F is"<<sizeof(34.45F)<<endl;
// cout<<"the sizeof 34.4L is"<<sizeof(34.45L)<<endl;
// cout<<"the sizeof 34.4l is"<<sizeof(34.45l)<<endl;

// ***************REFERENCE VARAIABLES*****************

// float m = 34.66;
// float & x = m;

// cout<<"the value of m is"<<x;


// ***************TYPECASTING*****************

// float o = 99.77;
// float p = int(o);
 
// cout<<"but i want to write that value in int thats why i m using"<<int(o)<<endl;
// cout<<"i can also write this as"<<(int)o<<endl;

// cout<<"and if i chose variable p then"<<p;



// ***************CONSTANTS*****************
// float con1=3.48;
// cout<<"the value of con1 was"<<con1<<endl;
// con1=4.44;
// cout<<"the value of con1 now is"<<con1<<endl;
// now if i dont want change it (want to keep constant)
// const  int con2=2;
// now i cant change it 
//  ***************MANIPULATORS*****************
// int a=4,b=3,c=103;
// cout<<"the value of a without setw is"<<a<<endl;
// cout<<"the value of b without setw is"<<b<<endl;
// cout<<"the value of c without setw is"<<c<<endl;


// cout<<"the value of a with setw is"<<setw(6)<<a<<endl;
// cout<<"the value of a with setw is"<<setw(6)<<b<<endl;
// cout<<"the value of a with setw is"<<setw(6)<<c<<endl;

// endl and \n is also manipulator endl also

//  ***************ORESIDANCE AND ASSOSIATIVITY*****************
// int a=4,b=3;
// int c = a*5+b;
// cout<<c;
// CAN SEE ONLINE


// ***************SELECTION CONTROL STATEMENT IF ELSE ELSE IF LADDER*****************


// int age;
// cout<<"what is your age";
// cin>>age;


// if (age<18 && age>0)
// {
//     cout<<"you are not eligible to vote";

// }
// else if (age>18 && age<100)
// {
//     cout<<"you can vote";

// }
// else{
// cout<<"you are dead";
// }


// ***************SELECTION CONTROL STATEMENT:SWITCH CASE *****************


// switch (age)
// {
// case 0-18:
//     cout<<"you dont have mind";
//     break;
// case 18-45:
//    cout<<"you have mind";
//    break;

// default:
// cout<<"you have or little mind than case 2";

//     break;
// }



// ************** LOOPS IN C++   *****************
// There are three types of loops
// 1)for loop 
// 2)while loop 
// 3)Do-while loop


//SYNTAX FOR FOR LOOPS

// for(initialization;condition;updation){
 
//     loop body(c++ code);
  
// }


// SYNTAX FOR WHILE LOOP


// while (condition) {
//     statement(s);
// }

//SYNTAX FOR DO WHILE LOOP

// do{

//   c++ statement;

// }
// while(condition);

//lets make a multiplication table;

//  int i=1;
//  int j=6;
// do{
// cout<<i*j<<endl;

// i++;
// }

// while(i<=10);



// int j=29;
// for(int i=1;i*j && i<=10;i++){

// cout<<i*j<<endl;

// };

// LEARN BREAK AND CONTINUE STATEMENT FOR LOOPS;IT IS EASY

// int j=29;
// for(int i=1;i*j && i<=10;i++){
// if(i==3){
// break;}

// cout<<i*j<<endl;

// int j=29;
// for(int i=1;i*j && i<=10;i++){
// if(i==3){
// continue;;}

// cout<<i*j<<endl;

// };


// *************POINTER*************
// WHAT IS POINTER
// IT IS A DATATYPE WHICH HOLDS THE ADRESS OF THE OTHER DATATYPE

// int a=3;
// int* b=&a;
// HERE &=(ADRESS OF) OPERATOR
// *= (VALUE OF)DEREFERENCE OPERATOR

//  int c=a;//these holds the value of operator NOT THE ADRESS
// cout<<"value of b"<<b<<endl;
// cout<<"value of b"<<&a<<endl;
// // these both are same

// cout<<"value of c is"<<c;
// cout<<"value stored at b is"<<*b<<endl;
 // POINTER TO POINTER
// int** d = &b;
// cout<<"we use ** to find the adress of a pointer(now here pointers is already stores someones adress) "<<d;



// ***********************ARRAYS******************


int marks[5]={67,56,88,45,74};
// cout<<marks[0]<<endl;
// marks[2]=444;
// cout<<marks[2]<<endl;
// cout<<marks[3]<<endl;
// cout<<marks[4]<<endl;
//here you can also change the value of an array

// THERE IS ALSO ANOTHER METHOD TO MAKE THE ARRAY

// int mathmarks[5];
// mathmarks[0]=99;
// mathmarks[0]=97;
// mathmarks[0]=96;
// mathmarks[0]=97;
// mathmarks[0]=98;

// for (size_t i = 0; i < 4; i++)
// 

int i=0;

while(i<=4){
   

cout<<"hi"<<marks[i]<<endl;
i++;
}







    return 0;








}
