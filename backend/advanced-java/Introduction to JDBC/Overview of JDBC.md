### JDBC:

**JDBC** stands for "**Java Database Connectivity**" and which is used to interact with
database product.

FAQ:
define Storage?
=&gt;The memory location where the data is available for access is known as Storage.

**Types of Storages:**

According to Java Application development,the storages are categorized into
four types:

1.Field Storage
2.Object Storage
3.File Storage
4.Database Storage

**1.Field Storage:**

- The memory generated to hold single data value is known as Field Storage.

- when we use Primitive datatypes like byte,short,int,long,float,double,char

  and boolean will generate Field Storages.

**2.Object Storage:**

- The memory generated to hold group values is known as Object-Storage.
- when we use Non-Primitive datatypes like Class,Interface,Array and Enum will
  generate Object Storage.



The Field and Object Storages which are generated part of JVM while Application execution
will be destroyed automatically when JVM Shutdowns.

when we want to have permanent storage for Applications,then we have to take the support
of any one of the following:

**File Storage**
**Database Storage**



**3.File Storage:**

- The smallest permanent storage of ComputerSystem which is &#39;controlled and managed&#39;

  by the OperatingSystem is known as FileStorage.

- In the process of establishing communication b/w Java-Program and File-Storage,the

  Java-Program must be Constructed using &#39;Classes and Interfaces&#39; available from

  &#39;java.io&#39; package(IO Streams and File API)

  

  **Disadvantages of File Storage:**

  (a)Data redundancy
  (b)Data Inconsistency
  (c)Difficulty in accessing data
  (d)Limited data sharing
  (e)File System corruption
  (f)Security Problems

**(a)Data redundancy:**

Same information will be duplicated in different files known as Data redundancy.
(data duplication)

**(b)Data Inconsistency:**
data can be inconsistent due to data redundancy

**(c)Difficulty in accessing data:**

Difficulty in accessing data,because the data is available in scattered form and there
is no quering process.

**(d)Limited data sharing:**

Limited data sharing because data in scattered form.

**(e)File System corruption:**

File System can be Corrupted due to fragmentation or metadata corruption.

**(f)Security Problems:**File System will have Security Problems.

**Note:**

- Because of Disadvantages in File-Storage,the File-Storage cannot be taken as major

  backend for Java-Applications.

- To overcome all dis-advantages of File-Storage,we use Database Storage.



### Driver

=&gt;The small s/w program which is used to establish communication b/w two end-points is
known as &#39;driver&#39;
Ex:
Audio drivers
Video drivers
N/W drivers
..

## JDBC driver

The driver which is used to establish communication b/w Java-Program and DB-Product is
known as JDBC driver.

#### **Types of drivers:**

=&gt;According Vendor the JDBC drivers are categorized into four types:
1.JDBC-ODBC bridge driver(Type-1 driver)
2.Native API driver(Type-2 driver)
3.Network Protocol driver(Type-3 driver)
4.Thin driver(Type-4 driver)

Note:
=&gt;According to realtime application development,we use only &#39;Thin driver&#39;
