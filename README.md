# gCSR
most likely stands for customer service relations and the "g" perhaps to Great Plains

The application is written in C# and Visual Basic. AS it stands it will build in vusal Studio 2017. Its a mature piece of code that was left to deteriorate for many years. 

I have a passing understanding of how to code but never really got the gist of oop. 

What I am hoping for here is to identify an expert or two to help me develop the code. In exchange you have the source code for an application that lays the foundation for an intriguing type of ERP.

There are perhpas 50,000 lines (or more) of Stored Procedures, Functions, and Views spanning multiple databases that I am willing to share as well if there is a SAFE WAY for me to do so. Perhpas I can truncate the tables; even there I will need some help how to provide the back end so it is possible to see that the code really works while not providing sensitive financial or client data.

Do not pass this over lightly - this is a functioning ERP with ASP.NET security, a remarkably robust reporting mechanism (SSRS), modules that support attaching orders to specific users, attaching (recorded) phone calls to orders, a ticketing system that follows the orders from input to factory (its a manufacturing concern), a very sophisticated suite of modules that perform an override commission calculation  for a hierarchy that spans dealers to VP's of sales. The suite of stored procedures that calculate the monthly override and bonus include hundreds of lines of t-sql/cursor code that functions and involves manipulation that CAN NOT be done via set operations )

There are inventory modules; there are reporing modules, lookup features, you name it, and theyall work!!!

First things first, the code as it is will build because a number of modules are excluded. Ironically those modules work (I can serve up the .aspx file in a browser) they just wont compile for arecane reasons.

If you are willing to jump in; help me document the code. Figure out a way to provide the SQL database strucutre back end so that the application can really function, help me to get the code to compile the way it should so I can port to an updated Windows Server/SQL Server combination, help me crack the telerik Rad Script stuff, how to develop a new viewing module for some 2 million documents, and a whole lot more.

I am absolutely handing over a really bitchen piece of code ... this is basically a PhD thesis in Data Science project because the next move is to develop a BI suite.


