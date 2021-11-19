# Notes 08: Databases
## Database

What is a Database? 
* A database is a shared collection of related data used to support the activities of a particular organization.

Properties:
* It is a representation of some aspect of the real world or a collection of data elements (facts) representing real-world information.
* A database is logical, coherent and internally consistent.
* A database is designed, built and populated with data for a specific purpose.
* Each data item is stored in a field.
* A combination of fields makes up a table. For example, each field in an employee table contains data about an individual employee.

Database Management System: A database management system (DBMS) is a collection of programs that enables users to create and maintain databases and control all access to them. The primary goal of a DBMS is to provide an environment that is both convenient and efficient for users to retrieve and store information.

**Characteristics and Benefits of a Database:**
* The processing power of a database allows it to manipulate the data it houses, so it can:
  * Sort
  * Match
  * Link
  * Aggregate
  * Skip fields
  * Calculate
  * Arrange
* A database can be linked to:
  * A website that is capturing registered users
  * A client-tracking application for social service organizations
  * A medical record system for a health care facility
  * Your personal address book in your email client
  * A collection of word-processed documents
  * A system that issues airline reservations

* Self-describing nature of a database system: A database system is referred to as self-describing because it not only contains the database itself, but also metadata which defines and describes the data and relationships between tables in the database. This information is used by the DBMS software or database users if needed.
* Insulation between program and data: In the file-based system, the structure of the data files is defined in the application programs so if a user wants to change the structure of a file, all the programs that access that file might need to be changed as well.
* Support for multiple views of data: A view is a subset of the database, which is defined and dedicated for particular users of the system. Multiple users in the system might have different views of the system. Each view might contain only the data of interest to a user or group of users.
* Sharing of data and multiuser system: This access is achieved through features called concurrency control strategies. These strategies ensure that the data accessed are always correct and that data integrity is maintained. 
* Control of data redundancy: In some cases, data redundancy still exists to improve system performance, but such redundancy is controlled by application programming and kept to minimum by introducing as little redudancy as possible when designing the database.
* Data Sharing: First, it allows for data sharing among employees and others who have access to the system. Second, it gives users the ability to generate more information from a given amount of data than would be possible without the integration.
* Enforcement of integrity constraints: A database constraint is a restriction or rule that dictates what can be entered or edited in a table such as a postal code using a certain format or adding a valid city in the City field.
* Restriction of unauthorized access: For example, one user might have read-only access (i.e., the ability to read a file but not make changes), while another might have read and write privileges, which is the ability to both read and modify a file. For this reason, a database management system should provide a security subsystem to create and control different types of user accounts and restrict unauthorized access.
* Data Independence:  the system data descriptions or data describing data (metadata) are separated from the application programs.
* Transaction Processing: ensures that data remains consistent and valid during transaction processing even if several users update the same information.
* Provision for multiple views of data: DBMS permits many users to have access to its database either individually or simultaneously. It is not important for users to be aware of how and where the data they access is stored
* Backup and recovery facilities:DBMS permits many users to have access to its database either individually or simultaneously. It is not important for users to be aware of how and where the data they access is stored



