# scientific-calculator
here its mentions all the important operators and more features .
#include<iostream>
#include<cmaths>
#include<cstdlib>

int main(){
    int choice;
    double num,num1,num2;
    while(true){
        cout<<"=====scientific-calculator====="<<endl;
        cout<<"Addition (+)"<<endl;
         cout<<"substraction (-)"<<endl;
          cout<<"multiplication (*)"<<endl;
           cout<<"division (/)"<<endl;
            cout<<"power pow(x^y)"<<endl;
             cout<<"square root ()"<<endl; 
              cout<<"Sine (sin x) "<<endl;
              cout<<"choice the Number"<<endl;
              cin>>choice;
        switch(choice){
            case 1:
            cout<<"Enter your tow number">>
            cin>>num1,num2;
            cout<<"Result"<<num1+num2<<endl;
            break;
             case 2:
             cout<<"Enter your two number">>
             cin>>num1,num2;
             cout<<"Result"<<num1-num2<<endl;
             break;

              case 3:
              cout<<"Enter  your two number">>
              cin>>num1,num2;
              cout<<"Result"<<num1*num2<<endl;
              break;
               case 4:
               cout<<"Enter your two number">>
               cin>>num1,num2;
               cout<<"Result"<<num1/num2<<endl;
               break;
                <!-- case 5:
                cout<<"Enter your two number">>
                cin>>num1,num2;
                cout<<"Result"<<num1,num2<<endl;
                break;
                 case 6:
                 cout<<"Enter your two number">>
                 cin>>num1,num2;
                 cout<<"Result"<<num1+num2<<endl;
                 break;
                  case 7:
                  cout<<"Enter your two number">> -->
                  <!-- cin>>num1,num2;
                  cout<<"Result"<<num1+num2<<endl;
                  break;
                   case 8:
                    cout<<"Enter your two number">>
                    cin>>num1,num2;
                    cout<<"Result"<<num1+num2<<endl;
                    break;

                    case 9:
                     cout<<"Enter your two number">>
                     cin>>num1,num2;
                     cout<<"Result"<<num1+num2<<endl;
                     break;
                     case 10:
                      cout<<"Enter your two number">>
                      cin>>num1,num2;
                      cout<<"Result"<<num1+num2<<endl;
                      break; -->


         }   
          

            

        

      
    }

}