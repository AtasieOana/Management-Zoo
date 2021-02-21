# Management of a zoo chain
**Project developed in PL / SQL**

## Covered features 
* functions;
* procedures;
* cursors;
* triggers;
* simple data structures: record, array, indexed table, nested table;
* multilevel collections.

## Description of the database on which the entire project was built
<div align="justify"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; For a zoo chain, the aim is to create a database that, for each zoo in the chain, keeps track of the tickets sold, the employees, the animals and the type of pen in which they live, along with the food the animals eat, provided by various suppliers. Visitors to the zoo can buy tickets, keeping in the database the date on which the ticket was sold and its price. At the same time, several employees work in a zoo, each employee being assigned to a single zoo. Each employee has a certain function, and there may be several employees with the same function. A position involves several responsibilities, which differ from one position to another. As for the animals, the zoo has several animals, each animal belonging to a single zoo, not being transferable from one garden to another. Also, each animal belongs to one species, each species comprising several animals. A species falls into a single category, and a category involves several species. Animals belonging to one species live in a certain type of pen, but pens are built so that several species of animals live in them. Each species of animal feeds on several types of food, and one type of food is the food of several species of animals. The zoo chain has animal food provided by the suppliers, so that one supplier provides several dishes and one type of food is brought by several suppliers.

## Tools used
The project was built and run in SQL Developer.
