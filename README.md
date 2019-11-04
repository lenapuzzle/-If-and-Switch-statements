# -If-and-Switch-statements









int userAge;
            Console.Write("Please enter your age: ");
            userAge = Convert.ToInt32(Console.ReadLine());

            if (userAge < 0 || userAge > 100)
            {
                Console.WriteLine("Invalid Age");
                Console.WriteLine("Age must be between 0 and 100");
            }
            else if (userAge < 18)

                Console.WriteLine("Sorry, you are underage");

            else if (userAge < 21)

                Console.WriteLine("You need parental consent");
            else
            {
                Console.WriteLine("Congratulations! " + "You may sign up for the event!"); 
            }

    

            Console.Write("Enter your grade: ");
            string userGrade = Console.ReadLine();

            switch (userGrade)
            {
                case "A+":
                case "A":
                    Console.WriteLine("Distinction");
                    break;

                case "B":
                    Console.WriteLine("B Grade");
                    break;

                case "C":
                    Console.WriteLine("C Grade");
                    break;

                default:
                    Console.WriteLine("Fail");
                    break;
            }
  
