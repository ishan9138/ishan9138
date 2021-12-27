- 👋 Hi, I’m @ishan9138
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ishan9138/ishan9138 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include<stdio.h>
#include<conio.h>

void main()
{
	int x,d,s,username1=1283,password1=3421,username2,password2,mob,otp=1989,eotp,username4,password4,username5,password5;
	printf("WELCOME TO THE OFFICIAL RESERVATION APP OF INDIAN RAILWAYS :-)\n");
	printf("Dear user! press 0 for login or press 1 for signup\n");
	scanf("%d",&x);
	
	switch(x)
	{
		case 0:
		printf("Enter your username:\n");
		scanf("%d",&username2);
		printf("Enter your password:\n");
		scanf("%d",&password2);
		
		if(username1==username2&&password1==password2)
		printf("You successfully logged in\n");
		else
		printf("Please enter the valid username or password\n");
		break;
		
		case 1:
		printf("Please enter your 10 digit mobile number:\n");
		scanf("%d",&mob);	
		printf("Please enter the OTP we sent you on this number:\n");
		scanf("%d",&eotp);
		
		if(otp==eotp)
		printf("Your number is verified\n");
		else
		printf("Please enter the valid OTP\n");
		
		printf("Create your username:\n");
		scanf("%d",&username4);
		printf("Create your password:\n");
		scanf("%d",&password4);
		
		printf("Confirm your username:\n");
		scanf("%d",&username5);
		printf("Confirm your password:\n");
		scanf("%d",&password5);
		
		if(username4==username5&&password4==password5)
		printf("Your account has been created:-)\n");
		else
		printf("OPPS ! Unable to match the username or password:-(\n");
	}
	    printf("Select your origin and destination by selecting the choice given below\n");
	    printf("\n2.NEW DELHI TO ALIGARH ON TOMORROW\n3.NEW DELHI TO ALIGARH ON DAY AFTER TOMORROW\n4.NEW DELHI TO CHANDIGARH ON TOMORROW\n5.NEW DELHI TO CHANDIGARH ON DAY AFTER TOMORROW\n");	    
        scanf("%d",&d);
		
		switch(d)
		{
		    case 2:
			printf("HERE ARE THE AVAILABLE TRAINS AND SEATS FROM NEW DELHI TO ALIGARH ON TOMORROW\n");
			printf("(12420 - GOMTI SUPERFAST EXPRESS with 2S=540,CC=100)\n");
			printf("(12876 - NEELANCHAL SUPERFAST EXPRESS with SLEEPER=23,3A=10)\n");
			break;
			
			case 3:
			printf("HERE ARE THE AVAILABLE TRAINS AND SEATS FROM NEW DELHI TO ALIGARH ON DAY AFTER TOMORROW\n");
			printf("(12420 - GOMTI SUPERFAST EXPRESS with 2S=1000,CC=110)\n");
			printf("(12004 - LUCKNOW JUNCTION SWARN SHATABDI EXPRESS with CC=555,ANUBHUTI=15)\n");
			break;
			
			case 4:
			printf("HERE ARE THE AVAILABLE TRAINS AND SEATS FROM NEW DELHI TO CHANDIGARH ON TOMORROW\n");
			printf("(13678 - PUNJAB MAIL with SLEEPER=540,CC=100)\n");
			printf("(12004 - CHANDIGARH WEEKLY SHATABDI SPECIAL with CC=530,ANUBHUTI=10)\n");
			break;
				
			case 5:
			printf("HERE ARE THE AVAILABLE TRAINS AND SEATS FROM NEW DELHI TO CHANDIGARH ON DAY AFTER TOMORROW\n");
			printf("(12420 - PUNJAB MAIL with SLEEPER=640,CC=109)\n");
			printf("(12004 - CHANDIGARH GAREEB RATH  with 1A=530,2A=90)\n");
			break;
	    }
	       printf("Press 6 if you want ticket on TOMORROW : GOMTI EXPRESS : 2S\n");
		   printf("Press 7 if you want ticket on TOMORROW : GOMTI EXPRESS : CHAIR CAR\n");
		   printf("Press 8 if you want ticket on DAY AFTER TOMORROW : GOMTI EXPRESS : 2S\n");
		   printf("Press 9 if you want ticket on DAY AFTER TOMORROW : GOMTI EXPRESS : CHAIR CAR\n");
		   printf("Press 10 if you want ticket on TOMORROW : NEELANCHAL EXPRESS : SLEEPER\n");
		   printf("Press 11 if you want ticket on TOMORROW : NEELANCHAL EXPRESS : 3A\n");
		   printf("Press 12 if you want ticket on DAY AFTER TOMORROW : LUCKNOW SHATABDI : CC\n");
		   printf("Press 13if you want ticket on DAY AFTER TOMORROW : LUCKNOW SHATABDI : ANUBHUTI\n");
		   printf("Press 14 if you want ticket on TOMORROW : PUNJAB MAIL : SLEEPER\n");
		   printf("Press 15 if you want ticket on TOMORROW : PUNJAB MAIL : CHAIR CAR\n");
		   printf("Press 16 if you want ticket on DAY AFTER TOMORROW : PUNJAB MAIL : SLEEPER\n");
		   printf("Press 17 if you want ticket on DAY AFTER TOMORROW : PUNJAB MAIL : CHAIR CAR\n"); 
	       printf("Press 18 if you want ticket on TOMORROW : CHANDIGARH WEEKLY SHATABDI : CC\n");
		   printf("Press 19k if you want ticket on TOMORROW : CHANDIGARH WEEKLY SHATABDI : ANUBHUTI\n");
		   printf("Press 20 if you want ticket on  DAY AFTER TOMORROW : GAREEB RATH : 1A\n");
		   printf("Press 21 if you want ticket on DAY AFTER TOMORROW : GAREEB RATH : 2A\n");				    
}
