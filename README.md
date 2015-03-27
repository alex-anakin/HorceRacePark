# HorceRacePark
Simulation for a automated teller machine for Horse Race Park.


The teller machine has only two responsibilities.
The first is to allow a park employee to set the number of the winning horse.
The second is to allow patrons to determine if the horse they have already bet on won,
and then collect their winnings if it did.

Upon startup, the machine display a list of its current inventory of money,
followed by a list of horses and current race results.
At this point the program accepts user input.

The machine dispense the minimum number of bills to complete a payout,
constrained by its current inventory. If the machine can't dispense a payout
due to insufficient funds, an error message is displayed.

The machine can be restocked to its initial state at any time.
Restocking the machine should restore each denomination to the initial inventory amount.


Valid commands are as follows:

'R' or 'r' - restocks the cash inventory

'Q' or 'q' - quits the application

'W' or 'w' [1-7] - sets the winning horse number

[1-7] <amount> - specifies the horse wagered on and the amount of the bet
