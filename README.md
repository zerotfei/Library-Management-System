=================================================================

Library-Management-System-LMS-

=================================================================


<< Description >>
---------------------
Library-Management-System-LMS- is a simple program to help users keep the book records for a library.

<< Installation >>
---------------------

  1. Install the latest Java SE Runtime Environment 
        -You can get it from here: http://www.oracle.com/technetwork/java/javase/downloads/index.html
  2. (Optional)Set the JAVA_HOME variable
	-You may only need to perform this step if the program is not working correctly. (e.g .jar is an unknown format)
	-You may follow the instruction from here: http://www.baeldung.com/java-home-on-windows-7-8-10-mac-os-x-linux
3. Extract the program to a location you prefer

Windows
----
  4. Double Click 'library.bat'

Mac or Linux 
----  
  4. Open the terminal and input ‘java -jar (PATH_TO_PROGRAM)/library.jar’

PATH_TO_PROGRAM = the directory library.jar is located


<< User Guideline >>
---------------------------

Getting Started
After launching the program, the user will see a command line program, where teh users may input various commands to perform the action they wish

Commands (Case-sensitive)
1. Adding a book into the library
arrive [BOOK_ID] [BOOK_NAME]
2. Adding a new member
register [MEMBER_ID] [MEMBER_NAME]
3. List all books in the library
listBooks
4. List all members in the library
	listMembers
5. Borrow a book
	checkout [MEMBER_ID] [BOOK_ID]
6. Return a book
	checkin [MEMBER_ID] [BOOK_ID]
7. Request a book
request [MEMBER_ID] [BOOK_ID]
8. Cancel a book request
cancelRequest [MEMBER_ID] [BOOK_ID]
9. Undo last command
undo
10. Redo last command
	redo
11. Start a new day
startNewDay dd-mmm-yyyy (e.g. 01-Jan-2017)




-----------------------------------------------------------------


<<End>>
