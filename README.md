# Bulletin-Board-Management-System

FrontEnd-->Angular Framework
BackEnd-->Java Spring Boot  version 17
Security-->Spring Security
DataBase FrameWork-->Spring JPA
Database --> My Sql version 8.0

Project Flow
//////////////////////////////////////////////////////////////////////////////////
                                                                                ||
Presentation Layer                                                              ||
--> Angular Framework(localhost:4200/api/v1/)                                   || 
-->Model View Controller                                                        ||  
-->Rest Api                                                                     ||
-->Json Format will response from the service layer                             ||
-->Parent Routing in App_Routing and Redirect Routing in Portal                 ||
-->DataTransfer with dto                                                        ||
_______________________________________________________________________________ ||
                                                                                ||
Application Layer                                                               ||
-->Controller at \src\main\java\com\test\controller package                     ||
-->Including About business Logic                                               ||
_______________________________________________________________________________ ||
Business Layer                                                                  ||
-->Business Layer is Service at \src\main\java\com\test\service                 ||
-->Service Layer implement about Business logic code in controller              ||
_______________________________________________________________________________ ||
Persistence                                                                     ||
-->Repository at \src\main\java\com\test\repositroy                             ||
-->That's have Native Query adapt about database with extend jpa repository     ||
_______________________________________________________________________________ ||
DataLayer                                                                       ||
-->DataLayer is Entity                                                          ||
-->That's Create Table and Join Column                                          ||
/////////////////////////////////////////////////////////////////////////////// ||
