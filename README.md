
ticketPrice = 15.0; 
discountAmount = 5.0; 
Console.WriteLine("Enter the number of people in your group: ");
int numberOfPeople = int.Parse(Console.ReadLine());
totalCharge = numberOfPeople * ticketPrice;
        if (numberOfPeople >= 6)
        {
            totalCharge -= discountAmount;
        }
        Console.WriteLine("The total charge for your group of" +numberOfPeople+ "people is:" +totalCharge+");
    }
