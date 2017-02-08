#include <iostream>
#include <string.h>
#include <iomanip>
#include <time.h>
#include <windows.h>
using namespace std;
int main()
{
	//for info https://www.youtube.com/watch?v=__o1jE0JSiE;
	/* points are
	1.> no. of characters(done)   // +(n*2) where n=count ginti=n //done
	2.>uppercase(done)		//+((no of letters-n)*2)  no of letters=up //  // total 5 and sum=20 s from 100 this rating is given
	3.>lowercase(done)		//+((no of letters-n)*2)  no of letters=lo
	4.>numbers(done)   //+(6*n)
	5.>symbols(done)	//+(n*8)	
	6.>middle no. or symbols
	7.>rating
	*/
	/*deduction
	1.>letters only // -n //done
	2.>no. only // -n //done
	3.>consecutive uppercase // -(n*2)
	4.>consecutive lowercase // -(n*2)
	5.>consecutive numbers // -(n*2)
	6.>Sequential Letters (3+) // -(n*3)
	7.>Sequential Numbers (3+) // -(n*3)
	8.> Sequential Symbols (3+) // -(n*3)
	*/
	/*
	Bugs:
	1.> character entring during choice. //done
	2.>include or exclude whitespaces during insertion of password. //done
	3.>remove spaces from auto generator.
	4.> character entring during 2nd choice. //done
	5.> generate function for removing whitespaces from array.//done
	6.>clear memory after every singal execution.//done
	7.>after taking whitespace (2nd option)//done
	*/
while(1)
{
	int i,v,j,m,y,as,k,x,r,b,o,n,cho,u,z,flag=0,count=0,temp=0,ginti=0,coun=0,up=0,lo=0,strenght,nu=0,sy=0,upp=0,gintii=0;
	char c[1000];
	char al[27]={'a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z'};	//j
	char la[27]={'A','B','C','D','E','F','G','H','I','J','K','L','M','N','O','P','Q','R','S','T','U','V','W','X','Y','Z'};	//m
	char kl[10]={'0','1','2','3','4','5','6','7','8','9'};	//k
	char qw[35]={'`','~','!','@','#','$','%','^','&','*','(',')','-','_','+','=','{','[','}',']','|',':',';','"','<','>',',','.','?','/'}; //o
	f:
		system("cls");
		cout<<setw(85)<<":Password generator and checking tool:"<<endl;
		cout<<":Lets see what you choose:"<<endl;
		cout<<"1. Check your password"<<endl;
		cout<<"2. Auto-Generate password"<<endl;  //Balance
		cout<<"3. Exit"<<endl;
		cout<<setw(50)<<"Your choice->>";
		cin>>r;
	while (!cin) 
	{
		system("cls");
		
        cout<<"ERROR!! Enter a number"<<endl;
        cout<<"Opening Options--"<<endl;
        Sleep(2000);
        system("cls");
        cout<<"1. Check your password"<<endl;
		cout<<"2. Auto-Generate password"<<endl;  //Balance
		cout<<"3. Exit"<<endl;
        cin.clear();
        cin.ignore(10000,'\n');  //it will see if input is letter by confirming it's end with '\n', because cin leaves '\n' at end of everyinput or it takes input till single whitespace.
        			// another way to use it is: cin.ignore(no. of character to leave, '$' means it will stop after it finds $); 
		// so what happens is that every consecutive cin wil get an info there there already exist data in it whic is previous cin '\n' newline character.
        cout<<endl;
        cin>>r;
    }
    if(r>=4||r==0)
		{
			system("cls");
			cout<<"ERROR!! Input from above sequence of digits only:"<<endl;
			Sleep(2000);
			goto f;
		}
				system("cls");
		switch(r)
		{
            case 1:
            {
            	fgh:
            		int jk=0;
 					cout<<"Enter Password:-> ";
					cin.ignore();	// used because cin>> leaves the newline character (\n) in the iostream.  If getline is used after cin>>, the getline sees this newline character as leading whitespace, thinks it is finished and stops reading any further.
					// best reference http://mathbits.com/MathBits/CompSci/APstrings/APgetline.htm
					cin.getline(c,1000);
						cout<<"checking";
						for(int ti=0;ti<4;ti++)
						{
						Sleep(500);	
						cout<<".";
						}
						system("cls");
					for(i=0;c[i]!='\0';i++)									// enter minimum no of 8(rating is not there)
					{
						gintii++;				
					}
					for(i=0;c[i]!='\0';i++)
					{
						if(c[i]==' ')
						{
							jk=1;
						}
					}
					if(jk==1)
						{
							cout<<"-:There is space in ur password (what u prefer):-"<<endl;
							cout<<"1. Automatic Remove Spaces"<<endl;
							cout<<"2. Create new password"<<endl;
							cout<<"Enter Your Choice:-> ";
							cin>>cho;
					while (!cin) 
						{
					        cout<<"ERROR!! Enter a number";
					        cin.clear();
					        cin.ignore(10000,'\n');
					        cout<<endl;
					        cin>>cho;
					    }
						switch(cho)
							{
								case 1:
									system("cls");
									goto bnm;
								case 2:
									system("cls");
									goto fgh;
							}	    
						}
					bnm:
						cout<<"processing";
						for(int tim=0;tim<4;tim++)
						{
						Sleep(500);	
						cout<<".";
						}
						system("cls");
					for(i=0;c[i]!='\0';i++)
					{
						if(c[i]==' ')
						{
							
						}
					}
					for(as=0;as<gintii;as++)
					{
						for(i=0;c[i]!='\0';i++)
						{
							if(c[i]==' ')
							{
								b=i+1;
								temp=c[b];
								c[b]=c[i];
								c[i]=temp;
							}
						}
					}
					for(i=0;c[i]!='\0';i++)
					{
						ginti++;
					}
					for(i=0;c[i]!='\0';i++)									
					{
						for(j=0;j<27;j++)			//lowercase
						{
							if(c[i]==al[j])
							{
								lo++;
								flag=1;
							}
						}
					}
					for(i=0;c[i]!='\0';i++)
					{
						for(m=0;m<27;m++)			//uppercase
						{
							if(c[i]==la[m])
							{
								up++;
								temp=1;
							}
						}
					}
					for(i=0;c[i]!='\0';i++)
					{
						for(k=0;k<10;k++)			//digit
						{
							if(c[i]==kl[k])
							{
								nu++;
								count=1;
							}
						}
					}
					for(i=0;c[i]!='\0';i++)
					{
						for(o=0;o<35;o++)			//symbols	
						{
							if(c[i]==qw[o])
							{
								sy++;
								coun=1;
							}
						}
					}
		if(flag==1&&temp==1&&count==1&&ginti>=8&&coun==1)
				{
						strenght=((ginti*2)+((ginti-up)*2)+((ginti-lo)*2)+(nu*6)+(sy*8));
							cout<<"Your Password is-> "<<c<<endl;
							if(strenght>=100)
								{
									cout<<"Pasword strenght-> "<<"100%"<<endl;
								}
							else
								{
									cout<<"Pasword strenght-> "<<strenght<<"%"<<endl;
								}
									cout<<"Password Nature-> ";			
							if(strenght>=1&&strenght<=10)
								{
									cout<<"Very Weak";
								}
							else if(strenght>=11&&strenght<=20)
							{
								cout<<"Very Weak";
							}
							else if(strenght>=21&&strenght<=30)
							{
								cout<<"Very Weak";
							}
							else if(strenght>=31&&strenght<=40)
							{
								cout<<"Weak";
							}
							else if(strenght>=41&&strenght<=50)
							{
								cout<<"Weak";
							}
							else if(strenght>=51&&strenght<=60)
							{
								cout<<"Weak";
							}
							else if(strenght>=61&&strenght<=70)
							{
								cout<<"Medium";
							}
							else if(strenght>=71&&strenght<=80)
							{
								cout<<"Strong";
							}	
							else if(strenght>=81&&strenght<=90)
							{
								cout<<"Strong";
							}
							else if(strenght>=91&&strenght<=100)
							{
								cout<<"Very Strong";
							}
							else if(strenght>=101)
							{
								cout<<"Very Strong";
							}
								goto q;
				}
		if(flag==1||temp==1||count==1)			//only for letters and digit
				{
						strenght=(((ginti*2)+((ginti-up)*2)+((ginti-lo)*2))-(ginti));
						cout<<"Your Password is-> "<<c<<endl;
						if(strenght>=100)
								{
									cout<<"Pasword strenght-> "<<"100%";
								}
							else
								{
									cout<<"Pasword strenght-> "<<strenght<<"%";
								}
						cout<<endl<<"Password Nature-> ";
							if(strenght>=1&&strenght<=10)
							{ 
								cout<<"Very Weak"<<endl;
							}
							else if(strenght>=11&&strenght<=20)
							{
								cout<<"Very Weak"<<endl;
							}
							else if(strenght>=21&&strenght<=30)
							{
								cout<<"Very Weak"<<endl;
							}
							else if(strenght>=31&&strenght<=40)
							{
								cout<<"Weak"<<endl;
							}
							else if(strenght>=41&&strenght<=50)
							{
								cout<<"Weak"<<endl;
							}
							else if(strenght>=51&&strenght<=60)
							{
								cout<<"Weak"<<endl;
							}
							else if(strenght>=61&&strenght<=70)
							{
								cout<<"Medium"<<endl;
							}
							else if(strenght>=71&&strenght<=80)
							{
								cout<<"Strong"<<endl;
							}	
							else if(strenght>=81&&strenght<=90)
							{
								cout<<"Strong"<<endl;
							}
							else if(strenght>=91&&strenght<=100)
							{
								cout<<"Very Strong"<<endl;
							}
							else if(strenght>=101)
							{
								cout<<"Very Strong"<<endl;
							}
				}
					cout<<endl<<"Hints to improve password:->"<<endl;
							if(ginti<8)
							{
								cout<<"--Plz make sure ur password lenght is equal to or greate than 8"<<endl;
							}
							if(flag==0)
							{
								cout<<"--Plz insert atleast one lowercase alphabet"<<endl;
							}
							if(temp==0)
							{
								cout<<"--Plz insert atleast one uppercase alphabet"<<endl;
							}
							if(count==0)
							{
								cout<<"--Plz insert atleast one integer"<<endl;
							}
							if(coun==0)
							{
								cout<<"--Plz insert atleast one symbol"<<endl;
							}
							q:
									cout<<endl;
									system("pause");
										  break;
            }

    		case 2:
  	       {
                  int n;
				    char pwd[] ="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890!@#$%^&*()_+-=[]{}|:;'?.,<>";
				    char password[92];
				    srand(time(NULL));
					 cout<<"Enter Lenght of your password to be generated it should be greate than '8'- ";
				     b:
					 cin>>n;
					 cout<<"Verfying Conditions:"<<endl;
					 Sleep(1000);
				     	while (!cin) 
							{
						        cout<<"ERROR, enter a number";
						        cin.clear();
						        cin.ignore(10000,'\n');
						        cout<<endl;
						        cin>>n;
						    }
				     if(n<8)
				     {
				     	system("cls");
				     	cout<<"Password lenght is less than '8' try again ->"<<endl;
				     	cout<<"Input lenght-> ";
				     	goto b;
					 }
				    for(int i=0;i<n;i++) 
					{
				        password[i]=pwd[rand()%92];
				    }
				    cout<<"Generating";
						for(int timers=0;timers<4;timers++)
						{
						Sleep(500);	
						cout<<".";
						}
						system("cls");
				    cout<<"your password is: "<<endl<<endl;
				    for(int y=0;y<n;y++) 
					{
				        cout<<password[y];
				    }
				    cout<<endl<<endl;
				    system("pause");
				    break;
			}
			case 3:
				{
					string bn;
					cout<<"Are Sure you want to exit(Y/N): "<<endl;
					cin>>bn;
					if(bn=="Y"||bn=="y")
					{
						system("cls");
						cout<<"Closing";
						for(int timer=0;timer<4;timer++)
						{
						Sleep(500);	
						cout<<".";
						}
						system("cls");
						cout<<"See you next time";
					goto end;
					}
					else if(bn=="N"||bn=="n")
					{
						cout<<"Opening";
						for(int m=0;m<4;m++)
						{
						Sleep(500);	
						cout<<".";
						}
						goto f;
					}
				}
		}
}
end:
return 0;
}
