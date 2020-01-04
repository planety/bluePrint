# BluePrint


## Core 


### Data layer
- [ ] **Database Adapter**  
    Concept:  submodule of ActiveRecord,implements methods upon Nim std db libs.  
    Implementation: [https://github.com/bung87/db_adapter](https://github.com/bung87/db_adapter)
- [ ] **Relational Algebra**  
    Concept:[Relational Algebra](http://infolab.stanford.edu/~ullman/fcdb/aut07/slides/ra.pdf)  
    Implementation: [https://github.com/itsumura-h/nim-allographer](https://github.com/itsumura-h/nim-allographer)
- [ ] **ActiveRecord**  
    Concept: build upon **Database Adapter** and **Relational Algebra**, provide methods for **web framework core** and **scaffold**.


## Scaffold CLI

### Data layer

- [ ] provide methods manage schemas.
- [ ] provide methods manage migration.
- [ ] provide methods manage fixtures.