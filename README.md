# Designing a Public Library
Learn DB design by building a public library

## version: 0.0.1


## Goal
- Design the class diagram for a public library

----------

## Step 2: List a set of use cases.

## Features:
- Define LLI = Lendable library item, ex. Books, movie, audiobook
- define Patron = Customer

### Employee - library employee

### Patron - User of a library
- Checkout a LLI
- How many checked out LLI a for patron?
- Due date for a parton's checked out item?
- how many checked out LLI are overdue

### Library card - A card that enables a patron to check out LLIs
- A parton can register with a library for a library card
- Update patron's info
- Renew lirbary card

### Library - Store that contains LLIs
- List patrons at a library
- How many LLI a library own?
- Does a library own a LLI?
- How many LLI a library needs to move to another library?
- order LLI?
- A patron returns a LLI to a library

### LLI Exchange - History of LLI exchanges between a patron and library
### Reserves - Events of a patron requesting / ordering a LLI

### Search engine
- Search for a LLI by name, author and ISBN
- How many copies the library owns of a LLI?

- Reserved a LLI at a library
- 

---------
### Useful resources:
- [Design Your Own Database Concept to Implementation](https://www.dartmouth.edu/~bknauff/dwebd/2004-02/DB-intro.pdf)
- [Database Answers](http://www.databaseanswers.org/data_models/)

### Data Modeling tools:
- Online: [SQL DBM](https://app.sqldbm.com/SQLServer/Draft/)
- Online: [draw.io](https://www.draw.io/), [example](https://about.draw.io/entity-relationship-diagram-erd/)
- Desktop App: [MySql Workbench](https://www.mysql.com/products/workbench/)
- Desktop App: [Oracle data modeler](https://www.oracle.com/database/technologies/appdev/datamodeler.html)
