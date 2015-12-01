#FINAL-PROJECT (LAST DELIVERABLE)

1. Implement a MySQL persistent storage for the repositories. **25 points**
    - Database table schema is up to you.  In other words, I don't care and will not grade.
    - The MySQL database server can either be local or remote.  Which-ever is easier for you.
    - I will be somewhat lenient on this part.  Please ask questions during the remaining labs.
2. Implement the unit-tests for all remaining classes. **25 points**
    - This is very important!  I will review closely!  Please write these first.
3. Implement code that makes all the unit-tests pass. **40 points**
4. Create two endpoints that use the domain objects. **10 points**
    - First endpoint: add a user and the related information in JSON payload using a POST call.  (POST) http://domain.com/users
    - Second endpoint: return all the users with their username, name in a JSON payload using a GET call. (GET) http://domain/users
      - You must have one option to sort by username either ascending or descending. (GET) http://domain/users?sort-username=ASC/DSC
    - Use the code at [http://sleep-er.co.uk/blog/2013/Creating-a-simple-REST-application-with-Silex/](http://sleep-er.co.uk/blog/2013/Creating-a-simple-REST-application-with-Silex/) as an example.
    - Please ask questions during the remaining labs on how to autoload your domain classes to be used in the API.
