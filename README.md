The Program "Courier Management ” is a menu driven program which gets the details of the station, stores it in a file, and generates amount to be paid and report  based on the requirement . C++ is the programming language used for this purpose, which is an Object Oriented Programming Language. 
The menu of the program is as follows:
1. STATION INFORMATION
2. BOOKING
3. SEARCH STATION
4. CUSTOMER RECORD
5. REPORTS
6. EDIT STATION
0. QUIT

1. Station Information:
The program displays the details of all the stations present in the file in the above mentioned format.
2. Booking:

This is the main part of the program where the booking is done .The program gets basic information of the consignor, the consignee and the parcel and generates the amount to be paid according to that particular courier station.

3. Search Station:
For the user entered station code, the complete details of the particular station will be displayed .

4. Customer Record:
The program displays the details of the consigner and the consignee of a particular service with the customer code present in the file in the above mentioned format.

5. Reports:
Displays the report of a station (on daily and monthly basis).The program asks for the date or month of whose report has to be printed, and then prints:
o	Code
o	Name of the Consignor
o	Name of the Consignee
o	Station code
o	Type 
o	Weight 
o	Amount

6. Edit Station:
•	Add the station details
If the user chooses this option, the user will be asked to enter the details of   the following:
	Station code
	Station name
	Amount for up to 500g (for dutiable)
	Additional amount  for the next 500g (for dutiable)
	Amount for up to 500g (for non-dutiable)
	Additional amount for the next 500g (for non-dutiable)
Doc (non-dutiable) 
these are consignments with no monetary value and are known as documents or general correspondence.
Non-Doc (dutiable)
All other consignments classified as dutiable by Customs may be levied customs duties and taxes for entrance into the destination country.
•	Deletes existing station records:  
The program asks the station code of the station whose record has to be deleted, and deletes the record.
•	Modify station's details: 
The program asks the station code of the station whose record has to be modified. Then the record is printed and changed details are asked. If the user wants to retain the old values for a certain field, he/she can enter ‘y’ or ‘n’ accordingly.

0. Quit
This option stops the execution of the program.

