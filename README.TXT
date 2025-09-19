Project: naive-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate the basics of fields, constructors, and methods.
How to start this project: Create one or more TicketMachine objects.

Q1: I tried out the get price method and got a value of 1. 
    I used the InsertMoney method and added some money inside and then used method getBalance and
I got the amount I put inside
    I inserted a random amount and then used the method printTicket and all the money in the balance was gone
and was sent down to zero.
    
Q2: It would be zero

Q3: When I add a negative amount the amount goes down.
    When I added too much money the amount then went to a negative amount.
    Even after putting in so much money and it going to negative, I did not get my refund.
    When I put 1 and print ticket it still went through
    
Q5: Yes it looks different. The price of the ticket is different.

Q6: public class Student
    public class LabClass
    
Q7: Yes it does matter, because the class has to be in the middle or else public will be interpreted as class
while class will be interpreted as public.

Q8: Yes it is possible to leave out the word public from the outer wrapper of the TicketMachine class

Q9: No it did not work, a lot of errors arised once I removed it.

Q10: price, balance, total. TicketMachine. getPrice, getBalance, insertMoney, printTicket

Q11: It did not seem to have a class right after public and the class seemed to be after the method

Q12:The type is int, Student and Server

Q13:The name is alive, tutor and game

Q14:It's Student, Server, Person, Game

Q15:It does matter what order clas private int price; is in otherwise it's gonna give an error
    The appearance of the class diagram after each chance does give me a clue as to 
    whether other ordering are possible, and it seemed like it wasn't.

Q16: Yes it is or else it's gonna give an error

Q17: private int status;

Q18: Student

Q19: There are 3 parameters called book, string title and double price

Q20: Yes they will need to be stored in a field. 

Q21: public Pet(String petsName)
{
    name = petsName
}

Q22: public int getDate()

Q23: The difference in the header would be what is it called, and in the body it
     would be what they are returning
    
Q24: How much money is there?

Q25: No, the return statement still work, this tells me that the getBalance here acts more
     like a name for what you want to do.

Q26: I have done added the getTotal method and it works

Q27: It says missing return statement

Q28: The different between the two is that the getPrice returns a value while the printTicket
     prints out a small text that can contain numbers, letters and other symbols
    
Q29: No because for printTicket you aren't getting, so is for the insertMoney

Q31: public void increaseScore(int points) { 
        
        score = score + points;
    }
    
Q32: Yes it is a mutator. it is because of the part credit += additionalPoimts;

Q33: /**
* Reduce price by the given amount.
*/
public void discount(int amount)
{
    price= price-amount;
// TODO: Subtract amount from price.
}

Q34: public void setAge(int currentAge) {
            this.age= currentAge;
}

Q35: public void setAlive (boolean alive) {
    this.alive=alive;
}

Q36: It seems like the amount I initially put in did not register

Q37: My cat has green eyes.

Q38: 

Q39: it says 

##################
# The BlueJ Line
# Ticket
# price cents.
##################

Q40:It says 

##################
# The BlueJ Line
# Ticket
#  + price  cents.
##################

Q43: It prints the same output

Q44: What it does is that it changes the previous price of 0 cents to 1000 cents