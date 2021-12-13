# myStory
import java.util.Scanner;  // Import the Scanner class
public class stroy {
	

	  public static void main(String[] args) {
	    Scanner myChar = new Scanner(System.in);  // Create a Scanner object
	    System.out.println("Are you ready to write a story about a lying shepherd with me?");
	    System.out.println();
	    System.out.println("If, YES! Enter The main Character of the Story:");

	    String my_Char = myChar.nextLine();
	    
	    String myStory1="Once upon time a shepres named ";
	    String myStory2=" lived in a village far away. This shepherd had no other work to do. He was very boring.That's why he wanted to make fun of the villagers";
	    String myStory3="He lies because my sheep are burned.So The villagers immediately rushed to the resuce. But When they got there was nothing burning.";
	    String myStory4="He lies because my homes are burned.So The villagers immediately rushed to the resuce. But When they got there was nothing burning.";
	    String myStory5="The villagers were very angry to ";
	    String myStory6 =" He wanted to apologize to the villages and thought about giving them a gift. ";
	    
	    System.out.print(myStory1 + my_Char + myStory2);
	    
	    System.out.println();
	    System.out.println();
	    
	    
	    System.out.println("For the continuation of the story please enter number");
	    System.out.println("If you choose is bigger then 100, he will say my sheep are burned.");
	    System.out.println("If you choose is smaller then 100, he will say my home are burned.");
	    System.out.println("Please enter your number:");
	    
	    Scanner sc= new Scanner(System.in);
	    int yourChoice= sc.nextInt();
	   
	    while(true){
	    	
		         if (yourChoice > 100 )
			    	System.out.print(myStory3 + myStory5 + my_Char + myStory6);
			      
			 
			      else if (yourChoice <= 100)
			    	System.out.print(myStory4 + myStory5 + my_Char + myStory6);
		         
			    	
		         break;
			    
			    }
	    	
	      
	 
	    
	    System.out.println();
	    System.out.println();
	    System.out.println("For the continuation of the story please enter number. ");
	    System.out.println();
	    System.out.println("If you choose is bigger then 100, he will buy followers with them");
	    System.out.println("If you choose is smaller then 100, he will help them with village affairs.");
	    System.out.println("Please enter your number:");
	    
	    String myStory7 = "He bought them flowers";
	    String myStory8 = "He helped them for willage affairs.";
	    String myStory9 = "The villagers forgave him,but";
	    String myStory10= " wanted to joke again.This time, he said that his sheep had been killed and wanted the villagers for money. The villagers helped him, but a few days later, " ;
	    String myStory11 = "one person saw his sheep in the valley and told the villagers about it";
	    String myStory12= "The villagers were very angry with him";
	    String myStory13= "Many months have passed, and on a cold winter night his sheep were really decapitated and the thief burned down his barn.";
	    String myStory14= "He wanted to help from villagers. ";
	    
	    
	    
	    
	    Scanner sc2= new Scanner(System.in);
	    int yourChoice2= sc2.nextInt();
	    
	    while(yourChoice > 100){
	    	
	    		if (yourChoice2 > 100 ){
		    	System.out.print(myStory1 + my_Char + myStory2 + myStory4 + myStory5 + my_Char + myStory6 + myStory7);
		        System.out.println( myStory9 + myStory10 + myStory11 + myStory12 + myStory13 + myStory14  );
		     }
		      else if (yourChoice2 <= 100){
		    	System.out.println(myStory1 + my_Char + myStory2 + myStory4 + myStory5 + my_Char + myStory6 + myStory8);
		    	System.out.print(myStory9 + myStory10 + myStory11 + myStory12 + myStory13 + myStory14 );
		    	
	    	  }
	    	break; 
	    }
	    while (yourChoice <= 100){
		    	 if (yourChoice2 > 100){
		    		 System.out.println(myStory1 + my_Char + myStory2 + myStory4 + myStory5 + my_Char + myStory6 + myStory7);
		    		 System.out.print( myStory9 + myStory10 + myStory11 + myStory12 + myStory13 + myStory14  );
		    	 }
		    	 else if (yourChoice2 <= 100){
		    		 System.out.println(myStory1 + my_Char + myStory2 + myStory4 + myStory5 + my_Char + myStory6 + myStory8);
		    		 System.out.print(myStory9 + myStory10 + myStory11 + myStory12 + myStory13 + myStory14 );
		    	 }
	     
		  
		    break;
		    
		}
	    
	    
	    
	    
	    System.out.println();
	    System.out.println("So, What do you think, Did the villagers believe in the shepherd?");
	    System.out.println("I think ..");
	  
	    String Answer ="no";
	    
	    Scanner sc3= new Scanner(System.in);
	    String yourAnswer= sc3.next();
	    
	    if (yourAnswer == Answer){
	    	System.out.println("Correct answer!If you lie all the time, no one will believe you.");
	    }
	    else 
	    	System.out.println("They didn't believe. Because If you lie all the time, no one will believe you.");
	 }
	  
	  
}

	  
	  
	

