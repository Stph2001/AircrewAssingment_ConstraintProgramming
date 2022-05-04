# AircrewAssingment_ConstraintProgramming
 
Aircrew assignment

The problem consists in assignment of the aircrew (air hostesses and stewards) to flights of an air company.

• There are 20 employees.<br>
– Stewards : Tom, David, Jeremy, Ron, Joe, Bill,Fred, Bob, Mario, Ed<br>
– air hostesses : Carol, Janet, Tracy, Marilyn, Carolyn, Cathy, Inez, Jean, Heather, Juliet.

• There are 10 flights.
• Number of employees assigned to each flight is fixed:

!(images/1.png)

• Aircrew of each flight should include at least a certain number of air hostesses and stewards:

!(images/2.png)

• Aircrew of each flight should include at least one person who speaks french, at least one person who speaks spanish, and at least one person who speaks german. Knowledge of languages :

Francais Inez, Bill, Jean, Juliet
Espagnol Tom, Jeremy, Mario, Cathy, Juliet
Allemand Bill, Fred, Joe, Mario, Marilyn, Inez, Heather

• If we assign somebody to a flight, we cannot assign him (or her) to two following flights.

Project aim. Model this problem as a CSP and solve it using a solver of your
choice. Try to use more global constraints.
