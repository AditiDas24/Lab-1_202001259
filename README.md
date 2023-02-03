# Lab-1																																																																													[IT314]                                                                                                                                                        
<h3> Name : Aditi Das </h3>                                                                                                                                 
<h3> Student ID : 202001259

  
 <br>

  
  <h3>Q1 Identify FRs and NFRs:</h3>
  
  <h4> Functional Requirements </h4>
  
   - <h5> Login/ signup, signout and authentication of users :</h5> Anybody who wants to issue books from the LIS must be a member of the institute in some capacity, i.e either as a student or an employee. If the member does not have an account, option to create an account must be available and verfication for new members should be available. Contact details must be provided in case the LIS wants to contact any user.
    
  - <h5> Records of all the books present in the library :</h5> The database should contain all pertinent details of all books. This would include unique book id, ISBN number, name of the book, name of the author, edition number, genre, type of book, date of purchase, date of last issue and id of the user who last issued it.
    
  - <h5> Search bar for users :</h5> Users should be able to look up books by id, title, genre, type of book and author's name. A filter must be provided for users to persue through the catalogue.
  
  - <h5> Highlights page : </h5>All trending books and new arrivals should be displayed at the beginning of the catalogue.
    
  - <h5> Issue/return books : </h5> Two cases can arise : <br>
    1. Requested book is available : Number of copies of the book along with date of issue and expected return date must be displayed.<br>
    2. Requested book is not available : In this case, expected return date must be displayed. Also, the user must be allowed to make a booking for the book.
  
  
   - Allowance to extend the deadline of issued books if no prior deadline has been found : Incase a user wants to extend the deadline for a book, it should be allowed provided there are no previous bookings for that particular book.
    
   - Update Records : New arrivals must be added to the system and books must be removed from the database if required. This access should be given to only the library staff.
    
   - Generating monthly reports : All transactions must be updated monthly and a report should be generated.
  
  <h4>Non Functional Requirements </h4>  
  
  - <b>Security</b>:- No user should be able to find out other user's personal details such as id, password, mobile number etc.
  - <b>Scalability</b>:- The system should be able to handle a large number of users and be able to handle multiple requests at a time.
  - <b>Availability</b>:- It is supposed to be available 24X7 as it is an online system.
  - <b>Ease of use</b> The interface should be easy to use and understand.
  - <b>Reliability</b>:- The system should be reliable and any changes to the databse should show up everywhere.

