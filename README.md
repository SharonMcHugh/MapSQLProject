MapSQLProject
=============

MapSQL is a simple in‐memory database management system for Java.   It consists of two
subsystems:
1. The core database engine
2. A shell for interacting with the database engine (this is a command line based interface)

This assignment requires that you complete a number of missing methods (listed below) in order to finish the
implementation of the database engine.

1. Basic Condition Implementations: (5% per condition)       20%
    a. GreaterThan
    b. GreaterThanOrEqual
    c. LessThan
    d. LessThanOrEqual
2. Implement Like condition (3 case % at start, % at end, or % at start and end) 10%
3. Implement Table.update() method           20%
4. Implement Table.delete() method           20%
5. Implement TableDescription.checkForNotNulls() method     10%
6. Implement DropTable.execute() method      10%
7. Implement the execute method in Sources.execute() method     10%
