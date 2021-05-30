#include<stdio.h>
 main()
 {




 	int num=0;


 	printf("Enter any number from 1 to 5\n");
 	scanf("%d",&num);

	printf("Food item- food1\nFood item- food2\nFood item- food3\nFood item- food4\nFood item- food5\n");




 	switch(num)
 	{
 		case  1:
 			printf("You selected Pizza\n Price-Rs 179\n");
 			break;
 		case  2:
 			printf("You selected Burger\n Price-Rs 129\n");
 			break;
 		case  3:
 			printf("You selected Pasta\n Price-Rs 179\n");
 			break;		
        case  4:
 			printf("You selected French Fries\n Price-Rs 99\n");
 			break;			
 	    case  5:
		    printf("You selected Sandwich\n Price-Rs 149\n");
 			break;
 			default : printf("Invalid Choice");

 	}


}
