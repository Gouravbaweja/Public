package project1;

public class Student 
{      //Class Define
	int rollno= 10;
	int age= 55;
	
	public void rollno()
	{            //Method 1
		System.out.println("welcome1");
	}
	public void age()
	{              //Method 2
		System.out.println("welcome2");
	}
    public static void main(String [] args)
    {             //Main 
    	Student gourav = new Student();
    	Student baweja= new Student();
    	gourav.rollno();
        baweja.age();
    	System.out.println(gourav.age);
        System.out.println(baweja.rollno); 	
    }   
}
