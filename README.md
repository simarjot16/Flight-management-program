# Flight-management-program
Flight Management Project


'Flight' Database


1. Table 'Cancellation'

bookingid   			int		(PK, Auto Increment)
userid					int
flightno 				int
bookingdate				date
cancellationdate		date



create table Cancellation
(
	bookingid int PRIMARY KEY auto_increment,
	userid int,
	flightno int,
	bookingdate date,
	cancellationdate date
)




2. Table 'Login'

userid					int     (PK, Auto Increment)
name 					varchar(20)
password 				varchar(20)
type 					int


3. Table 'Flight'

flightno				int (PK, Auto Increment)
flightname 				varchar(50)
source					varchar(50)
destination				varchar(50)
fare					decimal(10,2)
availability			varchar(100)


4. Table 'Booking'

bookingid				int (PK, Auto Increment)
userid  				int
flightno 				int
bookingdate				date


